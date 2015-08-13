# OB-POC-Widget
Test Server for OB Widget

To run the local node express server make sure you run:

npm install

and 

bower install

You also need to install Ruby (http://rubyinstaller.org/downloads/) 2.2.2 (x64) and check the add to Path variable option in the installer. Then install the sass gem:

gem install sass

Once all is installed you should be able to start the app server with the following grunt task:

grunt workon

The yeoman generator that was used to create this set up a few defaults for sublime text and chrome that will fail when you start the server so just click ok on those alerts and open http://localhost:3000/ in chrome.