# backlightctl

`backlightctl` is a simple replacement for xbacklight written in python. 
If xbacklight is troubbeling you somehow this might be helpful for you. 

## Install
just copy the backlightctl to `/usr/local/bin` and make sure you have python3 
as well as the python package argparse installed. 

## Usage

````
usage: backlightctl [-h] [-i] [-d] [-a INT] [-m INT] [-s INT]

Change displays backlight intensity.

optional arguments:

-   -h, --help         show this help message and exit
  -i, --inc          Increment brightness by 1
  -d, --dec          Decrement brightness by 1
  -a INT, --add INT  Add INT to brightness
  -m INT, --sub INT  Substract INT from brightness
  -s INT, --set INT  Set brightness to INT
```

