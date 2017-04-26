# Brickly plugins

These are plugins for [Brickly](https://github.com/EstherMi/ft-brickly-userguide/blob/master/de/brickly/index.md)

Plugins extend the functionality of brickly and add new blocks and new
functions. The plugin infrastructure is still under development and may
change.

## Installation

Currently there is no automatic way to install plugins. You need to copy
the desired plugin onto your TXT into the directory 

```
/opt/ftc/apps/user/1f2d90a3-11e9-4a92-955a-73ffaec0fe71/plugins
```

and create a matching entry in the file
```
/opt/ftc/apps/user/1f2d90a3-11e9-4a92-955a-73ffaec0fe71/plugins/plugins.list
```

E.g. when installing fileio.xml the ```plugins.list``` should read:

```
; list of installed plugins
fileio
```

## The plugins

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
