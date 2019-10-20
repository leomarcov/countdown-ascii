# ASCII countdow timer
A Bash countdown timer!

## Demo
<p align="center">
  <img src="https://user-images.githubusercontent.com/32820131/67157323-ebb20800-f32a-11e9-8ca0-63ed0e24f485.gif">
</p>

## Usage
```
$ countdown  -h
Usage: countdown [UNTIL-HOUR] [FROM-HOUR]
Samples:
  countdown		Only show current time
  countdown 10:32	Start countdown from current time to 10:32
  countdown 10:32 9:00	Continue countdown from 9:00 to 10:32
```

## Config
For config banner edit `countdown` file and set `banner1` and `banner2` variables:
```
#!/bin/bash

# BANNER CONIFG
banner1="EXAM TIME!"
banner2="KEEP CALM AND FOCUS"
...
```

## Dependences
  * [toilet](http://caca.zoy.org/wiki/toilet)
  * tput


## Lincense
License is [GPLv3](LICENSE)
