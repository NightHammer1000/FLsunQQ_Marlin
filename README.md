# Updated Marlin for FLSun QQ

## I am not responsible for any Damage done do your Printer by using this. Using anything else than stock firmware requieres quite some knowlege.

## Flashing only works on the QQ with disconnected MKS TFT or with USB Conncted without Power turned on. MKS TFT interferes with the Flashing of the Firmware because it uses Serial Communication

Any Help and Input is appriciated. Just open a Issue.

## Changes
 - Updated to lates bugfix2.0
 - Set the Values for Delta, Steps, Acceleration, Feedrate, etc according to Factory Configuration.h aquired from FLSun Engineer
 - Activated and Configured Lin_Advance (May needs Value Tuning on your System)
 - Deactivated the use of the MKS TFT in Favor of a RepRapDiscount Full Graphics Display.  
 (THIS FIRMWARE DOES NOT WORK WITH THE TFT)  
Best Practice:  
[[Display Mount](https://www.thingiverse.com/thing:3058250)]  
[[Display Case](https://www.thingiverse.com/thing:2368534)]  
- Preconfigured to use the FLSUN intended Delta Calibration and Bed Leveling Methode.
  Best not to use the Leveling Plate. Just get a few of those Conductive Cloths form Aliexpress and stick them directly onto the Bed.
  Make sure the Corners touch the Metal under the Bed to get grounding for the Probe. The Plate with the USB Connection is not needed.
- Activated UBL for Bedleveling using the Standart QQ Probing Methode. Do it right after Delta Calibration.

## Credits

The current Marlin dev team consists of:
 - Roxanne Neufeld [[@Roxy-3D](https://github.com/Roxy-3D)] - English
 - Scott Lahteine [[@thinkyhead](https://github.com/thinkyhead)] - English
 - Bob Kuhn [[@Bob-the-Kuhn](https://github.com/Bob-the-Kuhn)] - English
 - Chris Pepper [[@p3p](https://github.com/p3p)] - English
 - João Brazio [[@jbrazio](https://github.com/jbrazio)] - Portuguese, English

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
