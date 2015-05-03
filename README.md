A command line interface for interacting with the 1-wire sensor from Maxim.

Based on https://github.com/timofurrer/w1thermsensor

# Requirements
Python

Add
`dtoverlay=w1-gpio` to `/boot/config.txt` and reboot

# Usage
Command line example:

```
$ ./install
installing...
done.
$ ./detect
Found temper1 at path:
28-0000052fc128
28-0000053055be
$ ./pull --path 28-0000053055be
42
```
