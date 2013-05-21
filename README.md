etchasketch.py
==============

The backstory
-------------

This happened late on a school night. It was a dark and dreary day, and I wasn't entirely sure what the hell I wanted to program.  
_"F IT! CURSES TIEMMMMM!"_ I proclaimed to nobody at all - my one true friend.  
So I rode valiantly into my text editor of choice, as well as the Python documentation for the `curses` module.
Armed with nothing more than the PEP8 specs, Python documentation and some mountain dew, I went at it.  

And so it was born: `etchasketch.py` - not quite good, not quite bad; sitting somewhere in between was my new child. I had spent a good _20 minutes_ on this project, and it had turned out __OK-ish__.  
_"Dear lord, what have I created?!"_ I muttered again - clearly talking to my good friend _nobody_.  
_"It's.. It's... IT'S GENIUS!"_ the cry came from my voice. This was pure genius. Nothing in the history of the internet could ever be this amazing, this glorious; __this sketchy__.

Notes
-----

I feel like the source is a bit messy, but it's sort of managed how you'd expect it to be managed:  
A `while` loop with some stacked `if` and `elif` checks. That's the best I can think to do.

Sample drawing
--------------

This took way too damn long to do well. _I really should have just cheated.._
```
#####################################################################################
#####################################################################################
####   #####   ##           ####  ########  ###   ###################################
####   #####   ##   ############   ######   ### + ###################################
####   #####   ##   #############   ####   ####   ###################################
####   #####   ##   ##############   ##   #####   ###################################
####   #####   ##   ###############      ######   ###################################
####           ##           ########    #######   ###################################
####   #####   ##   ################   ########   ###################################
####   #####   ##   ###############   #########   ###################################
####   #####   ##   ##############   ##########   ###################################
####   #####   ##   #############   ############ ####################################
####   #####   ##   ############   ############   ###################################
####   #####   ##           ###   #############   ###################################
############# #### ###########   ############### ####################################
#############                                    ####################################
#####################################################################################
```

Usage
-----

It's fairly simple, but there are some less intuitive things about it all:

+ To run: `python etchasketch.py`
+ __Use your arrow keys to draw!__
+ `s` will __shake__ the board (resetting and making it refill your terminal (if you resize it at all))
+ `q` will __quit__ your board. Why you'd ever want to do that is beyond me.

License
-------

This is MIT licensed, so you can do whatever the hell you want. Sell it, buy it, rewrite it, use it as a bartering token with the Devil for your soul; it's up to you!
