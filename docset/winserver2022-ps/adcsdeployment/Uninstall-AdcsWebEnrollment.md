---
description: Use this topic to help manage Windows and Windows Server technologies with Windows PowerShell.
external help file: Microsoft.CertificateServices.Deployment.Commands.dll-Help.xml
Module Name: ADCSDeployment
ms.date: 12/27/2016
online version: https://learn.microsoft.com/powershell/module/adcsdeployment/uninstall-adcswebenrollment?view=windowsserver2022-ps&wt.mc_id=ps-gethelp
schema: 2.0.0
title: Uninstall-AdcsWebEnrollment
---

# Uninstall-AdcsWebEnrollment

## SYNOPSIS
Uninstalls the CA Web Enrollment role service.

## SYNTAX

```
Uninstall-AdcsWebEnrollment [-Force] [-WhatIf] [-Confirm] [<CommonParameters>]
```

## DESCRIPTION
The **Uninstall-AdcsWebEnrollment** cmdlet removes the Certification Authority (CA) Web Enrollment role service.

## EXAMPLES

### Example 1: Uninstall the CA Web Enrollment role service
```
PS C:\> Uninstall-AdcsWebEnrollment -Force
```

This command uninstalls the CA Web Enrollment role service without requiring confirmation.

## PARAMETERS

### -Confirm
Prompts you for confirmation before running the cmdlet.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: cf

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### -Force
Forces the command to run without asking for user confirmation.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: 

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -WhatIf
Shows what would happen if the cmdlet runs.
The cmdlet is not run.

```yaml
Type: SwitchParameter
Parameter Sets: (All)
Aliases: wi

Required: False
Position: Named
Default value: False
Accept pipeline input: False
Accept wildcard characters: False
```

### CommonParameters
This cmdlet supports the common parameters: -Debug, -ErrorAction, -ErrorVariable, -InformationAction, -InformationVariable, -OutVariable, -OutBuffer, -PipelineVariable, -Verbose, -WarningAction, and -WarningVariable. For more information, see [about_CommonParameters](https://go.microsoft.com/fwlink/?LinkID=113216).

## INPUTS

### None

## OUTPUTS

### Microsoft.CertificateServices.Deployment.Common.WEP.WebEnrollmentResult

## NOTES
* Ensure you run Windows PowerShell as an administrator. You can use the *Force* parameter to bypass the prompt for confirmation.

  

## RELATED LINKS

[Install-AdcsWebEnrollment](./Install-AdcsWebEnrollment.md)

