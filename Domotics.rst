.. title:: Domotics project

.. Objective:: Make an integrated, professional system that manages a smarthome.

Main benefits:
--------------
 * Reduce energy use
 * Security : built in alarm system, turn the lights on automatically
 * Convenience : remote control, mobile app, over internet
 * Automate holiday lightning
 * Whole home Video
 * Whole home audio
 * Access control
 * climate control
 * Home monitoring
 * Irrigation
 * Surveillance
 * Sensors

References & stadards
---------------------
- Communication:
 * `Z-wave` home control system: connects home electronics (appliances, lightning,
   climate control, security systems ...). Z-wave is a protocol for
   communication among devices used for home automation. It uses RF for
   signaling and control. Z-ware is based on the concepts of `Zigbee`.
 * `X10` utilize a home's existing powerline wiring for communication
 * `UPB` Universal powerline bus is a protocol for communication among devices
   using powerline wiring for signaling and control. It is based on `X10` standard
   and has improved transmission rate and higher reliability.
 * `INSTEON`: home control and automation technology. Use both existing wires
   (power line) and radio frequency communication
 * `Zigbee` is a protocol for communication among devices using RF for
   signaling and control operating on IEEE 802.15.4 radios. Zigbee products are
   much more expensive than their primary competition (INSTEON and Zwave)
 * `KNX` standard: OSI-based network communications protocol for building
   automation. Is the successor of three previous standards: European Home
   Systems Protocol (EHS), BAtiBUS and European Installation Bus EIB.

Comparison table:
^^^^^^^^^^^^^^^^^
| Brand                      | INSTEON | Z-wave | Wi-Fi  | Bluetooth | Zigbee |
|----------------------------+---------+--------+--------+-----------+--------|
| max practical network size | 1000's  | 30-50  | 12     | 9         | 12     |
| physical layer 1           | RF      | RF     | RF     | RF        | RF     |
| physical layer 1 frequency | 915MHz  | 915MHz | 2.4GHz | 2.4GHz    | both   |
| to be continued            |         |        |        |           |        |
|----------------------------+---------+--------+--------+-----------+--------|

Operating system / controller / system of systems
-------------------------------------------------
 * OpenHAB
 * Domoticz
 * OpenDomotic

System componement model:
-------------------------

Smarthome system includes:
 * light control switch

Possible shopping list:
-----------------------
- Controller :
- Getway:
- Sensors:
  * Cameras
  * Motion detection cams
  * Contact sensors
  * Smoke sensors
  * temp/humidity/pressure sensors
  * Rain sensors
- Actuators:
  * Find existing devices


Next step
=========
- List of components: part number, link, price...
- Website


