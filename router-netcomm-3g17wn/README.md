# NetComm 3G USB 11n Router (3G17Wn)

## Images

![The side of the router with "NetComm 3G USB 11n Router" written on it](images/side.jpg)
![The front of the router with status LEDs](images/front.jpg)
![The back of the router with a Wi-Fi antenna, WPS/reset button, USB 2.0 port, three ethernet ports, and a power jack](images/ports.jpg)
![The bottom of the router, with model, serial number, MAC address](images/bottom.jpg)

## Hardware notes
- DC jack is 12V - from bottom of device and in user manual
- There are pins for a serial port on the PCB with a header already soldered on.
    - This is 3.3 V serial at 57600 baud.
- SoC is MIPS little endian

## Links
- Product page: https://support.netcommwireless.com/legacy-products/3G17WN

## Disassembly
1. Unscrew and take off the Wi-Fi antenna to get it out of the way.
1. Rotate the stand on the bottom out and undo the two screws underneath.
1. Pry the plastic shell apart by the seams on the back where the ports are, on each side of the port bank - there are clips there.

## Getting a shell
Firmware 1.0.52.0 (Oct 13 2011)

I could receive on the serial port but not transmit anything.

There is a telnet daemon running - just `telnet <router IP>` and log in with the admin credentials.
