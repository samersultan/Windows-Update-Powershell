## More info:

[https://gist.github.com/cfebs/c9d83c2480a716f6d8571fb6cc80fd59](https://christitus.com/install-windows-update-powershell/)

## Install Module 

```
Install-Module PSWindowsUpdate

```
## To Force Install 

```
Install-Module -Name PSWindowsUpdate -Force
````

_________


## Check for updates 

````
Get-WindowsUpdate -ListUpdates
````

## Install Updates

````
Install-WindowsUpdate
````

## Scheduled Task to Install Updates

````
Install-WindowsUpdate -AcceptAll -AutoReboot
````

Get Updates direct from Microsoft Online 

```
Install-WindowsUpdate -MicrosoftUpdate -AcceptAll -Verbose -AutoReboot
```

Get Updates direct from Microsoft Online  -No Reboot 

```
Install-WindowsUpdate -MicrosoftUpdate -AcceptAll -IgnoreReboot -Verbose
```



Testing Optional Updates: https://old.reddit.com/r/sysadmin/comments/m6ao6f/pswindowsupdate_and_optional_quality_updates/
```
get-wulist -criteria "isinstalled=0 and deploymentaction=*"
```
