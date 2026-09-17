# default1080-raja-skin-set
A skinset for beatoraja/lr2oraja, BMZ Player and maybe some other BMS player clients that supports beatoraja LUA skins
I haven't came up with a good name yet, maybe at the end of the day it will stay the same.

## Contents

## Music Select ver.0.8
Have been created in JSON, then later on have been rewritten in LUA. 
I've added a bunch of customization options, such as **ability to change the songwheel position**,**deactivate background animations**, **change color of song title** and etc.
Lamp graph have been disabled, I did not find a solution how to implement it the way it will look natural on the screen.
The skin have basic IR (Internet Ranking) support. Your ranking position in leaderboard and basic rivaling. 
No extended rival window have been created that will look similar to beatmania IIDX games doing it. Also there is no support for checking an IR leaderboard
Basic tutorial have been included (top-left corner). Still an placeholder.
Song info section contain many things and to be honest still look kinda messy.

## Decide Screen ver.0.9
The idea here is to do something flashy that will feel good especially backed up by background music. 3 total layers of animations have been done :)
One issue I cannot fix yet. It currently shows genre and song artist during the start of the COURSE (or DANs) instead of just the title of the COURSE

## Result Screen ver.0.9
Result screen have every basic feature included. Also comes wih bunch of customization options such as **1P/2P position**, **ability to deactivate most of the additional parts of the screen (ranking, graphs, chart info)**
You can also click on DETAILS to open bigger xD graphs to look at. 

## Course Result Screen v.1.0
Course result screen is basically stripped down Result Screen with everything necessary including IR ranking. You can also click on the magnified glass icon to see gauge graph more detailed.

## Play SKin (7K)
Not included, currently being in development.

## Usage in BMZ Player
I've included separate edited LUA files that will work with BMZ Player correctly. It mostly an issue with how BMZ handling fonts in the game, so it required a bit of tweaking, here and there. Also DETAILS menu in RESULT SCREEN and COURSE RESULT **doesn't work** in BMZ (maybe just yet) so it was temporarely removed

Choose **bmz_select.luaskin** for Music Select Screen
      **bmz_result.luaskin** for Result Screen
  and **bmz_courseresult** for Course Result
