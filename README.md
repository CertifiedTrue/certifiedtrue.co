# website
CertifiedTrue public website | Landing page based on template from ICO Crypto 


~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Currently we are hosting on Firebase a Google service extensive to a realtime webapp
both desktop and mobile using service workers. This will save CertifiedTrue from building 
a mobile app for public web site on Android and iOS.

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

To deploy. git clone or download the certifedtrue website to your on local computer 
(use Clone or download in github)
$ git clone https://github.com/CertifiedTrue/website-main.git

Locally change into website-main

Install Node to automate.
https://nodejs.org/en/download/


$ npm install -g firebase-tools

Sigin in to Google using certrrue@gmail.com (get password from secrets doc) and open the Firebase console.

$ firebase login

Initiate project (since we already created a project use the same settings)

$ firebase init 

You're about to initialize a Firebase project in this directory:

  /Users/YourLocalComputerName/github/website-main

? Which Firebase CLI features do you want to setup for this folder? Press Space to
select features, then Enter to confirm your choices. Hosting: Configure and deploy Firebase Hosting sites

=== Project Setup

First, let's associate this project directory with a Firebase project.
You can create multiple project aliases by running firebase use --add, 
but for now we'll just set up a default project.

? Select a default Firebase project for this directory: CertTrueMainWebsite (certtruemainwebsite)

=== Hosting Setup

Your public directory is the folder (relative to your project directory) that
will contain Hosting assets to be uploaded with firebase deploy. If you
have a build process for your assets, use your build's output directory.

? What do you want to use as your public directory? main-html
? Configure as a single-page app (rewrite all urls to /index.html)? Yes
? File main-html/index.html already exists. Overwrite? No
i  Skipping write of main-html/index.html

i  Writing configuration info to firebase.json...
i  Writing project information to .firebaserc...

✔  Firebase initialization complete!

from website-main 

$ firebase deploy

Check web site updated ok. 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Commit your changes to github

$ git add *
$ git commit -m "Commit message"
$ git push origin master

Check your commit on github 

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~









