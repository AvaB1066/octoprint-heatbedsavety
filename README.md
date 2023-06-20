# OctoPrint-Hotend-Fan-Control

# What is it
This plugin is designed for turning on a fan when your hot end reaches a certain temp. What I used this for was switching the 'always on' heatsink fan on the Ender 3 to be controlled from a GPIO pin so it would only turn on when printing. This was a replacement for a PSU switcher plugin, as I didn't want to printer to lose connection each time it turned off. I will add the schematic for the circuit below. I also wired this up to the motherboard fan too. Another use woulod be for turning on an led when the hotend heats up as in indicator. I also added a hotbed fuction to this for those who would like it. Feel free to change this code and do what you want with it but know that this code is heavily based off of the plugin HeatBedSavety by linux-paul. Huge thanks to them! And as allways, I am not repsonable if you fry your pi. Please take precautions when wireing this up and test the circut without the pi first. 

## Setup

Install via the bundled [Plugin Manager](https://docs.octoprint.org/en/master/bundledplugins/pluginmanager.html)
or manually using this URL:

https://github.com/avabeck-ley/OctoPrint-temp-triggered-fan/archive/master.zip

## Configuration

