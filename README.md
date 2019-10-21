# pwa_simple_public

This repository contains the end goal of the making a PWA workshop.  This code is run locally using "npm start".  It can be viewed in a browser on localhost:8080.  When running locally the if statement at the beginning of the app.js file will need to be commented out.  This code redirects HTTP requests to HTTPS to ensure the app is always delivered over a secure connection.  You will want this when deploying live but it needs to be removed (commented out) to run and test locally.

This Progressive Web Applciation registers a service worker in order to be used offline and contains a manifest file that defines certian attributes of the application.  

In order to get this application to run on your mobile device, first you need to deploy the application to a server or a cloud provided server.  From there navigate to the domain name where the live application is running from the built in browser application on your mobile device.  You will be able to "bookmark" the webpage and add it to your homescreen where it will function like a standalone mobile application.  

Tone analyzer and cloudant DB functions are also set up for a few simple tasks: Adding documents to a database, viewing database documents, and analyzing the tone of a block of text.  Credentials are required and need to be filled out in the appropriate fields in app.js.  These can be obtained from the respective instance dashboards on the IBM Cloud platform.

