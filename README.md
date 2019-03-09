# quickstarters
Quickstarters make the dream of a "One Click App Store" into a reality for registered users.  
You can see how easy it is by going to your Daskboard and scrolling down to the Quickstarters.  
If you have a good application, Sloppy.io is likely to add you to the Quickstarters.  But you can also initiate 
QuickStarters from your own website.  
You create a webpage with a graphic, and when the user clicks on the graphic, it passes the name of the quickstarter 
json file to the server, and everything is created for you.  

An important feature is that every quickstarter project gets their own unique domain name. 
[How to create unique domain names](https://kb.sloppy.io/getting-started/getting-started-with-the-cli-launch-your-first-dockerized-app/step-3-deploy-your-first-project)

To create your own quickstarter, first clone this repository and create the json file. 
You can launch the quickstarter using the following CLI command. 

...

When everything is working issue a pull request.  Once it is accepted you can launch your quickstarter
with the following URL:

...

If you reference your project using the latest tag, then you can release new versions, and the quickstarter will
always use the newest version. 

One final note:  The major delay in starting a quickstater is the time that it takes to downlaod the repository form 
the often slow DockerHub.  To speed up the user experience, you can host your own public 
reposity on Sloppy.IO, and download the images from there. 

If you don't have an account yet, [sign up](https://sloppy.io) now!
