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
Get-WindowsUpdate
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
