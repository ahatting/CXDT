## Citrix Xendesktop Toolkit (CXDT)

_CXDT allows you to easily reset stale/broken VDI sessions for a particular user._

The tool will:
- Fetch the last computer the user was logged on to from the Citrix Xendesktop database.
- Reset the VM in VMWare vCenter

The minimal requirements are:
- Domain joined workstation
- Windows PowerShell version 3 or higher
- VMWare PowerCLI 5 or higher
- Login & DB_datareader on the Xendesktop database
- Reset permissions for the VM's in vCenter

***

![Sample](https://github.com/ahatting/CXDT/blob/master/sample.png "ICE")
