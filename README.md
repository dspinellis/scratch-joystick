This command when run will read the values from a joystick and send them
as broadcast messages to a running Scratch programming environment.

# Installation
## Scratch setup
* [Enable remote sensor connections](http://wiki.scratch.mit.edu/wiki/Remote_Sensor_Connections)

## Adding a joystick on a Mac
* [Disable key signing on Yosemite](http://apple.stackexchange.com/questions/163059/how-can-i-disable-kext-signing-in-mac-os-x-10-10-yosemite)
* [Disable key signing in El Capitan](http://apple.stackexchange.com/questions/191421/can-i-make-my-own-kernel-extensions-on-el-capitan)
by executing the following on the recovery mode command line
```
csrutil disable
```
* Install the [HID driver](https://macman860.wordpress.com/2013/05/03/xbox-driver-for-mac-os-x-lion/)
