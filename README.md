# FreeDeck
## This Repo contains all the stuff you need to build your own FreeDeck
- [Walkthrough and tutorial](https://youtu.be/-3Zw8hbpVq4) video from Adam Welch
- [Demo Video](https://www.youtube.com/watch?v=_TcliiU2K48) of my first prototype
### [Discord Community](https://discord.gg/sEt2Rrd)
## Description
The FreeDeck aims to be a Free/OpenSource replacement for Elgatos Streamdeck and similar.
It works by creating a config file with the FreeDeck [Configurator](http://freedeck.gosewis.ch), loading it onto an SDCard and inserting it into the FreeDeck. You don't need to install any software and can use it across reboots on Windows, Linux and MacOS. This was my main reason behind this gadget.
This prototype is made from:
- Perfboard
- Arduino Pro Micro (32u4 16mhz 5v)
- 2x 4051 Multiplexer
- 6x ssd1306 OLEDs
- 6x 3x4x2mm SMD buttons
- SPI-SDcard Reader

The Arduino Code can be found [here](https://github.com/koriwi/freedeck-ino)

The Configurator Repo can be found [here](https://github.com/koriwi/freedeck-configurator)


![Image of first FreeDeck Prototype](http://freedeck.gosewis.ch/prototype1.jpg)
