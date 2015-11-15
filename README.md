# ixeProjectCreator
Shell scrip and boiler plate code to setup base interaction engines

This is a script to help setup interaction engine projects. This code will create a new project directory in the current working directory and will populate it with base project files for setting up a node server, client side javascript, client side html, and Arduino sketch. You can also specify different node packages and bower packages to be included in the project and managed by npm and bower.

# Requirements
1) node.js: some version of node.js must be installed and have npm installed
  - On RPi: I recommend installing through Adafruit Occidentalis: https://learn.adafruit.com/adafruit-raspberry-pi-educational-linux-distro/occidentalis-v0-dot-3

2) bower: bower must be installed to manage front end web packages
  - Install using: `npm install -g bower`

3) Arduino-mk: The will be used to setup the command line arduino tool in your project directory
  - To install see: https://github.com/sudar/Arduino-Makefile
