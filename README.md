# QuickStarters


ClickStarters make the dream of a "One Click App Store" into a
reality for registered users.  
You can see how easy it is by logging in,
going to your Dashboard and scrolling down
to the Quickstarters. All it takes is one click on one of those images,
and you will have a running application.  Easy!  If you do not actually need
it is also very easy to then delete the whole application and all of its
containers.


An important feature is that every quickstarter project gets their own
unique domain name. 
[How to create unique domain names](https://kb.sloppy.io/getting-started/getting-started-with-the-cli-launch-your-first-dockerized-app/step-3-deploy-your-first-project)

To create your own quickstarter, first clone this repository and create the json file. 

You can launch your quickstarter using the following CLI command. 

```
sloppy start -var=URI:mydomain.sloppy.zone config.json
```

When everything is working issue a pull request.  Once it is accepted you can launch your quickstarter
with the following URL:

...

If you reference your project using the latest tag, then you can
release new versions, and the QuickStarter will
always use the newest version. 

One final note:  The major delay in starting a QuickStater is the time
that it takes to downlaod the repository form 
the often slow DockerHub.  To speed up the user experience, you can host
your own public 
reposity on Sloppy.IO, and download the images from there. 

If you don't have an account yet, [sign up](https://sloppy.io) now!

