# FBCTF

https://github.com/facebook/fbctf

## What is FBCTF?

The Facebook CTF is a platform to host Jeopardy and “King of the Hill” style Capture the Flag competitions.

<div align="center"><img src="https://github.com/facebook/fbctf/raw/master/screencapture.gif" /></div>

## How do I use FBCTF?

* Organize a competition. This can be with as few as two participants, all the way up to several hundred. The participants can be physically present, active online, or a combination of the two.
* Follow setup instructions below to spin up platform infrastructure.
* Enter challenges into admin page
* Have participants register as teams
    * If running a closed competition:
        * In the admin page, generate and export tokens to be shared with approved teams, then point participants towards the registration page
    * If running an open competition:
        * Point participants towards the registration page
* Enjoy!

## Start it

```
sloppy start -var=URI:mydomain.sloppy.zone fbctf.json
   
Example:
   
sloppy start -var=URI:myctfhost.sloppy.zone fbctf.json
```