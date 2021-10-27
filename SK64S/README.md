# Overview
The default config program for the SK64S is just bad and barely useable. Check
below for the binary I use to program this board.

Instructions are simple

0.  [gk6x web gui](https://ukeloop.github.io/gk6x_gui/)
1.  Change the key configuration.
2.  When you open pixeltris/GK6X it will connect to your keyboard. Once it has 
    connected it will create a file `UserData/YOUR_MODEL_ID.txt`.
3.  Copy key configuration to `UserData/YOUR_MODEL_ID.txt` and save.
4.  Use the `map` command to apply your changes to the keyboard. 

# Resources
[GK6X](https://github.com/pixeltris/GK6X)
This is much better than the default configurator. I've included v1.17 of the
binary in the repo as well, but honestly you should probably get the updated
version straight from the Github.