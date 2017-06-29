# hack-dell-recovery

[dell-recovery](https://github.com/dell/dell-recovery)

--------------------------------------------------------------------------------
# Table of Contents
  * [Usage](#usage)

# Usage
## /usr/bin/dell-driver-installer
"Dell Driver Installation", please refer to [Dell Latitude E7240/E7440 Ubuntu driver package Driver Details](http://www.dell.com/support/home/us/en/19/Drivers/DriversDetails?driverId=0WKFN) as an example. Installation:
  * By choosing the driver tarball in /usr/bin/dell-driver-installer, user could install the latest drivers.
  * By double-clicking the driver tarball, /usr/bin/dell-driver-installer will be started automatically. And then user could install drivers.

## /usr/bin/dell-recovery
features:
### Build OS Media
this is a feature provided from dell-recovery to build a recovery media onto usb or iso image which could be used to recover the system. We could refer to the README of dell-recovery:
In End User mode, the tool will simply create an image from an existing recovery partition with no customizations.
https://github.com/dell/dell-recovery

### Restore system
This is a feature provided by dell-recovery to restore the entire system. There is document providing instruction to restore the entire system from recovery partition: [How to recover a Dell-Ubuntu Image on your Dell PC
](http://www.dell.com/support/article/us/en/19/SLN265750/how-to-recover-a-dell-ubuntu-image-on-your-dell-pc?lang=EN)
