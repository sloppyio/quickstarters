# ClickStarters


ClickStarters make the dream of a "One Click App Store" into a
reality for registered users.  
You can see how easy it is by [logging in to sloppy.io](https://sloppy.io),
going to your Dashboard and scrolling down
to the Clickstarters. All it takes is one click on start one of those images,
and you will have a running application.  Easy!  If you do not actually need
it is also very easy to then delete the whole application and all of its
containers.


An important feature is that every quickstarter project gets its own
unique domain name. 
[How to create unique domain names](https://kb.sloppy.io/getting-started/getting-started-with-the-cli-launch-your-first-dockerized-app/step-3-deploy-your-first-project)

To create your own quickstarter, first clone this repository and create the config.json file. 

You can launch your quickstarter using the following CLI command. 

```
sloppy start -var=URI:mydomain.sloppy.zone config.json
```

...

If you reference your project using the latest tag, then you can
release new versions, and the QuickStarter will
always use the newest version. 

One final note:  The major delay in starting a QuickStater is the time
that it takes to downlaod the repository from 
the often slow Docker Hub.  To speed up the user experience, you can host
your own public 
reposity on Sloppy.IO, and download the images from there. 

If you don't have an account yet, [sign up](https://sloppy.io) now!

