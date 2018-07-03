# The Serial Device Manager (SDM)
This document provides information and instruction related to using the Serial Device Manager (SDM) for iOS, which is built into iScanBrowser.

You can access the SDM by tapping on the SDM icon from the floating taskbar.

![](https://i.imgur.com/zP5L7gP.png)


## Pair with a Bluetooth Device
The main page of the Serial Device Manager is where you'll be able to pair with, manage, and disconnect from your Bluetooth devices.

Scanners in HID mode (already paired with in iOS Bluetooth Settings) will appear beneath "**CONNECTED DEVICES**," scanners in MFi mode, will appear in the section labeled "**MFi DEVICES**," and scanners in BLE (Bluetooth Low Energy) mode will appear beneath "**BLUETOOTH LE DEVICES**."

The Scanfob 2006 in the screenshot below is in BLE mode and appears in the BLUETOOTH LE DEVICES section.

![](https://i.imgur.com/MFCqCQz.png)


## Device Settings
To access a paired device's settings, tap on the gear icon to the far right of the device's Bluetooth name.

![](https://i.imgur.com/S4V4Zzk.png)

The settings available vary by the type of device and the Bluetooth connection type , but generally you'll have access to some basic information about the device (such as the model number, Bluetooth name, or serial number) and a handful of device settings options (as shown below).

![](https://i.imgur.com/x9GYQ0x.png)

## Device Manager Settings

### Enable Auto-reconnecting with Last Device(s)
To configure iScanBrowser to automatically attempt to reconnect to the last paired device(s), toggle the slider to the right of "**Reconnect to last device(s)**."

![](https://i.imgur.com/xCPgYCQ.png)

### Enable the Device Filter
We're often in places where there are many nearby Bluetooth devices. To filter out miscellaneous devices (including unsupported scanners), toggle the slider to the right of "**Enable device filter**."

![](https://i.imgur.com/qoHLyOz.png)


#### Adjust the Device Filter
To show only a specific type of device and/or connection (or handful of devices), tap on the settings option labeled "**Device type filter**." 

![](https://i.imgur.com/pAJKqaR.png)

Here you can select the devices you want to show up in the nearby devices list. Uncheck any device types that you want to filter out.

![](https://i.imgur.com/xyhxtEB.png)


### Enable Keep iOS Awake
To configure iScanBrowser to keep your iOS device's screen awake, tap on the settings option labeled "**Keep iOS awake**."

![](https://i.imgur.com/mI4lqTJ.png)

Then select a pre-defined amount of time or enter in a custom value (in minutes) to keep the screen awake. By default, this option is set to 2 minutes.

![](https://i.imgur.com/G8cQXoI.png)
### Reset Device History
To clear the SDM's record of previously paired devices, tap on the option labeled "**Saved last device(s)**."

![](https://i.imgur.com/zOTk3tu.png)

Then tap on "**Reset**."

![](https://i.imgur.com/ieONgSk.png)
