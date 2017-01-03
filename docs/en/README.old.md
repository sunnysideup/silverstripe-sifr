sIFR
================================================================================

Developer
-----------------------------------------------
Nicolaas Francken [at] sunnysideup.co.nz

Requirements
-----------------------------------------------
see composer.json

Documentation
-----------------------------------------------


To customise this module - do the following:

**** Making Fonts ****
go to the source code and create your own flash file
OR, when make one online (easier!)
Save font in mysite/fonts/myfont.swf
--- http://www.sifrgenerator.com/
----- choose the latest version of sifr when asked
----- (see FUTURE PROOFING below).
--- http://www.coffeecup.com/sifr-font-maker/ - not as good)

*** JS CONFIG ****
go to mysite/javascript/sifr-config.js and change the path of the font
--- also see http://wiki.novemberborn.net/sifr3/JavaScript+Configuration
--- also see http://wiki.novemberborn.net/sifr3/JavaScript+Methods

*** STYLING
scroll down to bottom of mysite/javascript/sifr-config.js file and adjust styles
create a themed css file: themes/mytheme/css/sifr-themed.css and edit it
--- also see http://wiki.novemberborn.net/sifr3/Styling

**** FUTURE PROOF ****
we can get the lastest version here (for the future):
--- also see http://dev.novemberborn.net/sifr3/nightlies/


Installation Instructions
-----------------------------------------------
1. Find out how to add modules to SS and add module as per usual.

2. Review configs and add entries to mysite/_config/config.yml
(or similar) as necessary.
In the _config/ folder of this module
you can usually find some examples of config options (if any).

3. go to css folder and copy css file to be themed (make a copy and place in theme folder)

4. go to javascript folder and copy file to be made

5. specify location of javascript files


Thank you
-----------------------------------------------
This module is heavily based on the original
SS sifr module.

