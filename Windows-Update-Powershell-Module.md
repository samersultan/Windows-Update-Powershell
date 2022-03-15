## Install Module 

````
Install-Module PSWindowsUpdate

Install-Module -Name PSWindowsUpdate -Force
````

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
