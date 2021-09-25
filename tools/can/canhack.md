# CANHack

* [https://kentindell.github.io/2021/02/06/canhack-pico/](https://kentindell.github.io/2021/02/06/canhack-pico/)



### Connecting up the hardware <a id="connecting-up-the-hardware"></a>

First, a bill of materials:

* 1 Raspberry Pi Pico
* 1 [Microchip MCP2562FD](https://ww1.microchip.com/downloads/en/DeviceDoc/20005284A.pdf) \(PDF\) CAN transceiver
* 2 100nF decoupling capacitors
* 1 9-pin D-sub male connector \(if wanting to use standard CAN connectors\)

To talk on a CAN bus all that’s strictly necessary is a CAN transceiver. This converts the CAN H/CAN L analog voltages into digital CAN RX/TX. Here I’m going to show how to wire up a Microchip MCP2562FD transceiver. I use this transceiver because:

* I have a bunch in stock in my components stash
* They come in PDIP packages that can be used directly on a breadboard
* They can be interfaced to 3.3V I/O

![](../../.gitbook/assets/grafik%20%282%29.png)

* [ASRG WWW 20210923 Tindell Demonstration of attacks on the CAN protocol](../../organisations/asrg/asrg-www-20210923-tindell-demonstration-of-attacks-on-the-can-protocol.md)



