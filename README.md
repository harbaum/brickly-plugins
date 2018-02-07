# Brickly plugins

These are plugins for [Brickly](https://github.com/EstherMi/ft-brickly-userguide/blob/master/de/brickly/index.md)

Plugins extend the functionality of brickly and add new blocks and new
functions. The plugin infrastructure is still under development and may
change.

## Installation

Since version 1.38 brickly can upload plugins via the main web interface.
In skill leven 5 clicking the "plug" icon will open a menu which allows
to install plugins.

![plugin installation](plugin_install.png)

## The plugins

### ftDuino IO - ftduino.xml

This plugin gives brickly access to the IOs of an [ftDuino](http://ftduino.de)
connected via USB to the TXT or [TX-PI](https://github.com/harbaum/tx-pi).

The ftDuino needs to run the [ftduino_direct sketch](https://github.com/PeterDHabermehl/ftduino_direct).

![ftduino plugin](ftduino.png)

### file IO - fileio.xml

Provides blocks to read and write simple files. The new blocks show up
in the custrom (Spezial) category.

An example program looks like:

![fileio plugin](fileio.png)

### test - test.xml

A simple test plugin without a really useful functionalty. This
shows some of the basic plugin concepts and e.g. implements its own
toolbox sub category as well a button inside the toolbox which
directly interacts with the TXT.

![test plugin](test.png)
