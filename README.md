![](https://i.imgur.com/DQ2Gc9P.jpg)

Nothing special, this is a simple module that depends on requests, rich, and I add some API. 

## Terminal Installation
```
pip3 install git+https://github.com/sintxcs/PySintx.git
```


## Importing the module in your script
```
try:
    import PySintx
except ModuleNotFoundError:
    os.system("pip3 install git+https://github.com/sintxcs/PySintx.git)
    import PySintx

from PySintx import *
```

## Colors
```
PySintx.yellow
PySintx.cyan
PySintx.blue
PySintx.white
PySintx.black
PySintx.green
PySintx.light_red
PySintx.dark_gray
PySintx.light_purple
PySintx.bold_green
PySintx.red_orange
PySintx.red_blue
PySintx.red_cyan
PySintx.red_green
PySintx.red_purple
```