# PSClip

PowerShell module for clipboard manipulation. It provides two functions:

* `Set-ClipboardText`: Sets clipboard content with provided text, which can be passed as parameter, or read from pipeline
* `Get-ClipboardText`: Returns clipboard content;

This module also provides two aliases:

* `scb`: alias to `Set-ClipboardText`
* `gcb`: alias to `Get-ClipboardText`

## Installing

Windows 10 users:

    Install-Module PSClip -Scope CurrentUser

Otherwise, if you have [PsGet](http://psget.net/) installed:

    Install-Module PSClip
  
Or you can install it manually coping `PSClip.psm1` to your modules folder (e.g. ` $Env:USERPROFILE\Eduardo_Sousa\Documents\WindowsPowerShell\Modules\PSClip\`)
