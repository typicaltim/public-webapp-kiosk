# public-webapp-kiosk
Script and related files that will configure a Windows 7 machine to become a basic Kiosk for a webapp.

## Purpose
The original purpose of this was to place a handful of machines in the public lobby of an organization so that visitors could utilize a webapp that required they fill out form data. We wanted it off the domain, with no login, and for visitors to only be able to access the webapp. If they tried to close the webapp and do other things, it would kick them back into the web app.

## Implementation
//This will be how I did it//

## Pre-requisities
* **Windows 7**
  * Other Windows flavors might work, but this was intended for Windows 7
* **Windows Management Framework** (WMF) Version 5.1+
* **Unrestricted Execution Policy** (temporary) Use these in PowerShell:
  ```powershell
      Set-ExecutionPolicy -ExecutionPolicy Unrestricted
      Set-ExecutionPolicy -ExecutionPolicy Restricted
  ```

## Guide
//This will be how to use//

## Other Notes
//This will be info on problems and stuff//
