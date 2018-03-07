# HomeKit for Homey

### Support for new exclusive services: [HomeCenter for HomeKit](https://itunes.apple.com/ru/app/homecenter-for-homekit/id1329662539?mt=8)
![ScreenShot](https://github.com/sprut666666/graphics/blob/master/homecenter/ScreenShot.png)

![Image of paircode](https://github.com/sprut666666/graphics/blob/master/homekit/code.png)

After Homey is paired, go to "settings" -> "HomeKit". There select the devices you want to pair with "HomeKit" and wait =)
Example of work: https://www.youtube.com/watch?v=yZWt6jDCl7E (New video from Homey the work)

Forum => https://forum.athom.com/discussion/3958/app-homekit-app-sprut

Remote access in HomeKit: https://support.apple.com/en-us/HT207057

If you have problems update your "I" device & Apple TV. On iOS 11 everything works perfectly. If you don't see for example the "SPEAKER" look here https://itunes.apple.com/us/app/elgato-eve/id917695792?mt=8

If the problem remained fully describe the situation. If you found any bugs, any other feature you can create an issue on [com.sprut.homekit](https://github.com/sprut666666/com.sprut.homekit)

You can add any device and if it supported device types they will be added to HomeKit. If the device is not supported device types will be added to the device "NOT SUPPORTED" - If you want I added a new device type send me "full info:" the device from the log on sprut666666@gmail.com

Now supports the types:
- Light (On-off, dim, Temperature control, RGB)
- Fan
- Switch
- Outlet
- Doorlock
- Curtains
- Motion sensor
- Humidity sensor
- Light sensor
- Carbon dioxide sensor
- Temperature sensor
- Leak sensor
- Smoke sensor
- Contact sensor (door/window sensor)
- AirQuality sensor
- Thermostat
- Volume speaker
- Vacuum cleaner
- Button (simple and Play/Pause etc)
- Doorbell button (as Motion sensor)
- Occupancy sensor
- Atmospheric Pressure sensor
- Noise Level sensor
- Ultraviolet sensor
- Power Meter sensor
- Security System sensor

+ Battery service for all

---

### About
Many thanks to the developer who wrote the library [has-node](https://github.com/abedinpour/HAS) Without which the application cannot run ;)
Many thanks [abedinpour](https://github.com/abedinpour) so much for the work done.

The basis of this application is taken development [com.swttt.homekit](https://github.com/swttt/com.swttt.homekit)
Many thanks [Swttt](https://github.com/swttt) so much for the work done.

And I [Sprut](https://github.com/sprut666666) - engaged in ongoing app development =)

---

### Changelog

#### 1.5.0
- update has-node@0.4.13
- update athom-api@2.0.108
- Support temperature is less than zero
- Fix Error: Homey Offline
- Add lib new-types-for-homekit@1.0.1
- Add support Atmospheric Pressure
- Add support Noise Level
- Add support Ultraviolet
- Add support Power Meter
- Add support Security System

#### 1.4.0
- update has-node@0.4.11
- update athom-api@2.0.93
- Now you can add 150 devices
- Memory optimization

#### 1.3.5
- update has-node@0.4.9
- critical fixes

#### 1.3.3
- update has-node@0.4.8

#### 1.3.2
- update has-node@0.4.6
- update athom-api@2.0.92
- fix "No response"

#### 1.3.1
- update has-node@0.4.5
- update athom-api@2.0.91

#### 1.2.4
- update has-node@0.3.4

#### 1.2.3
- update has-node@0.3.3
- update athom-api@2.0.72

#### 1.2.2
- update has-node@0.3.1
- update athom-api@2.0.71
- fix delete device

#### 1.2.1
- update has-node@0.2.6
- update athom-api@2.0.61

#### 1.2.0
- Fix & add OccupancySensor
- update has-node@0.2.5
- update athom-api@2.0.37

#### 1.1.9
- Fix README

#### 1.1.8
- Fix info & README

#### 1.1.7
- If wakeup interval > 15 seconds - no online state

#### 1.1.6
- Extended support for status updates of devices

#### 1.1.5
- Verification of successful installation of the new parameters in Homey
- Fix for MiLight

#### 1.1.4
- Small fixes

#### 1.1.3
- Critical bugfix when adding many devices

#### 1.1.2
- update has-node 0.2.3

#### 1.1.1
- fix WindowCovering

#### 1.1.0
- update has-node 0.2.2
- new ColorTemperature
- fix RGBW

#### 1.0.5
- fix bugs in Thermostat & expansion of functionality

#### 1.0.4
- fix Thermostat not measure_temperature

#### 1.0.3
- Add Doorbell button (as Motion sensor)

#### 1.0.2
- Add full device info for debug

#### 1.0.1
- Support 2 bridges for example com.swttt.homekit

#### 1.0.0
- Initial release
