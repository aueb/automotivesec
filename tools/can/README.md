# CAN

## Sources

* [https://de.wikipedia.org/wiki/Controller\_Area\_Network](https://de.wikipedia.org/wiki/Controller_Area_Network)
* [https://en.wikipedia.org/wiki/CAN\_bus](https://en.wikipedia.org/wiki/CAN_bus)
* [https://www.can-cia.org/can-knowledge/](https://www.can-cia.org/can-knowledge/)
* [https://www.hackers-arise.com/single-post/2017/08/04/Automobile-Hacking-Part-1-The-CAN-Protocol](https://www.hackers-arise.com/single-post/2017/08/04/Automobile-Hacking-Part-1-The-CAN-Protocol)
* [https://www.csselectronics.com/screen/page/simple-intro-to-can-bus](https://www.csselectronics.com/screen/page/simple-intro-to-can-bus)
* [https://makezine.com/2016/04/08/car-hacking-tools-trade/](https://makezine.com/2016/04/08/car-hacking-tools-trade/) Excerpt from the Car Hackers Handbook \([http://opengarages.org/handbook/](http://opengarages.org/handbook/)\)
* [https://github.com/mortedamos/vehicle-hacking/wiki](https://github.com/mortedamos/vehicle-hacking/wiki) from [ASRG-D](https://github.com/aueb/automotivesec/wiki/ASRG-Meetup-Detroit)
* [https://www.cowfishstudios.com/blog/canned-pi-part1](https://www.cowfishstudios.com/blog/canned-pi-part1)
* Work in Progress [https://canb.us/](https://canb.us/)
  * [https://www.canb.us/tutorials/Quick Start](https://www.canb.us/tutorials/Quick%20Start)
* [http://obdtester.com/downloads](http://obdtester.com/downloads)

## Basics

* [https://makezine.com/2016/04/08/car-hacking-tools-trade/](https://makezine.com/2016/04/08/car-hacking-tools-trade/)
* [https://canb.us/tutorials/Tapping into a bus](https://canb.us/tutorials/Tapping%20into%20a%20bus)
* When CAN CANT - Tim Brom and Mitchell Johnson \(GRIMM\) [https://archive.org/details/youtube-oS-6xDc\_pP4](https://archive.org/details/youtube-oS-6xDc_pP4)

## Standards

* [https://pinoutguide.com/CarElectronics/car\_obd2\_pinout.shtml](https://pinoutguide.com/CarElectronics/car_obd2_pinout.shtml)
  * Skoda [https://pinoutguide.com/CarElectronics/skoda\_obd2\_diagnostic\_pinout.shtml](https://pinoutguide.com/CarElectronics/skoda_obd2_diagnostic_pinout.shtml)

### ISO 11898

* ISO 11898-1:2015 Road vehicles — Controller area network — Part 1: Data link layer and physical signalling
* ISO 11898-2:2016 Road vehicles — Controller area network — Part 2: High-speed medium access unit
* ISO 11898-3:2006 Road vehicles — Controller area network — Part 3: Low-speed, fault-tolerant, medium dependent interface
* ISO 11898-4:2004 Road vehicles — Controller area network — Part 4: Time-triggered communication
* ISO 11898-5:2007 Road vehicles — Controller area network — Part 5: High-speed medium access unit with low-power mode
* ISO 11898-6:2013 Road vehicles — Controller area network — Part 6: High-speed medium access unit with selective wake-up functionality

  **SAE J2284**

* SAE J2284-1:2016 High Speed CAN for Vehicle Applications at 125 kbps
* SAE J2284-2:2016 High Speed CAN for Vehicle Applications at 250 kbps
* SAE J2284-3:2016 High Speed CAN for Vehicle Applications at 500 kbps
* SAE J2284-4:2016 High Speed CAN for Vehicle Applications at 500 kbps with CAN FD Data at 2 Mbps
* SAE J2284-5:2016 High Speed CAN for Vehicle Applications at 500 kbps with CAN FD Data at 5 Mbps

### Higher Protocols

* 1992: CiA 201 series \(CAN Application Layer\)
* 1994: IEC 62026-3 \(DeviceNet\)
* 1994: SAE J1939 series
* 1994: EN 50325-4 \(CANopen\)
  * [https://www.can-cia.org/canopen/](https://www.can-cia.org/canopen/)
  * [https://www.can-cia.org/services/canopen-vendor-id/](https://www.can-cia.org/services/canopen-vendor-id/)
  * [https://www.csselectronics.com/screen/page/canopen-tutorial-simple-intro](https://www.csselectronics.com/screen/page/canopen-tutorial-simple-intro)
* 1999: ISO 11992 series
* 2000: IEC 61162-3 \(NMEA 2000\)
* 2002: ISO 11783 series \(Isobus\)
* 2004: ISO 15765 series \(OBDII/ISO-TP\)
* 2007: Arinc 825/826

#### Links

* [https://www.can-cia.org/can-knowledge/hlp/higher-layer-protocols/](https://www.can-cia.org/can-knowledge/hlp/higher-layer-protocols/)

### On-board diagnostics

* [https://en.wikipedia.org/wiki/On-board\_diagnostics](https://en.wikipedia.org/wiki/On-board_diagnostics)

#### OBD2

#### Fault Codes

* [http://wiki.ross-tech.com/wiki/index.php/Category:Fault\_Codes](http://wiki.ross-tech.com/wiki/index.php/Category:Fault_Codes)

#### Steering wheel angle

* [https://github.com/brendan-w/python-OBD/issues/40](https://github.com/brendan-w/python-OBD/issues/40)
* [http://wiki.ross-tech.com/wiki/index.php/VW\_Golf\_\(1K\)\_Steering\_Assist\#Channel\_009:\_Steering\_Angle\_Sensor](http://wiki.ross-tech.com/wiki/index.php/VW_Golf_%281K%29_Steering_Assist#Channel_009:_Steering_Angle_Sensor)
* [https://mechanics.stackexchange.com/questions/17634/read-steering-angle-data-in-real-time](https://mechanics.stackexchange.com/questions/17634/read-steering-angle-data-in-real-time)

## Chips

### ELM327

* [https://area515.org/elm327-hacking/](https://area515.org/elm327-hacking/)
* alternative Firmware [https://bitbucket.org/drbobbob/elm-lawicel/src/default/](https://bitbucket.org/drbobbob/elm-lawicel/src/default/)

## Tools

* [CANalyze](CANalyze)
* [CANalyzat0r](CANalyzat0r)
* [CANUSB](CANUSB)
* [Flashlogic FLXCAN](Flashlogic_FLXCAN)
* [USB2CAN](USB2CAN)
* [ValueCan4-1](ValueCan4-1)
* [VehicleSpy](VehicleSpy) by Intrepid
* [Easysync](Easysync)
* [Ikalogic SP209 Logic Analyzer](Ikalogic_SP209_Logic_Analyzer)
* [CANtact](CANtact)
* canb.us and [Wireshark](Wireshark) [https://canb.us/tutorials/Wireshark](https://canb.us/tutorials/Wireshark)
* CANiBUS [https://github.com/Hive13/CANiBUS/](https://github.com/Hive13/CANiBUS/)
* [Scapy](Scapy)
* [GreatFET](GreatFET)

## Links

* [https://hackaday.com/2013/10/22/can-hacking-the-in-vehicle-network/](https://hackaday.com/2013/10/22/can-hacking-the-in-vehicle-network/)
* Cyber-attacks on vehicles
  * [http://dn5.ljuska.org/napadi-na-auto-sistem-1.html](http://dn5.ljuska.org/napadi-na-auto-sistem-1.html)
  * [http://dn5.ljuska.org/cyber-attacks-on-vehicles-2.html](http://dn5.ljuska.org/cyber-attacks-on-vehicles-2.html)
* [https://www.can-cia.org/](https://www.can-cia.org/)
  * [https://www.can-cia.org/can-knowledge/](https://www.can-cia.org/can-knowledge/)
  * [https://www.can-cia.org/groups/specifications/](https://www.can-cia.org/groups/specifications/)
  * [https://www.can-cia.org/services/publications/further-information/information-brochures/](https://www.can-cia.org/services/publications/further-information/information-brochures/)
  * [https://www.can-cia.org/services/conferences/icc/](https://www.can-cia.org/services/conferences/icc/)

