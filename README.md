# Find The BARK!
A webpage application that connects dog owners and helps them find dog parks in the Washington, DC area.  This is a full stack application using AngularJS for the front end and Node.js and mongoDB for the backend. The application uses an automated Grunt build process, with automated testing using Karma, Mocha and Chai. The live site reflects the master branch of the team repository: https://github.com/DogParkLocator/DogParkLocator. This repository has been forked from the aforementioned to this repository: https://github.com/BrianFiala/FindTheBARK in order to facilitate changes by this author, Brian Fiala. NOTE: This forked repository will display differently than the live site due to unreflected development within this repository fork.

# Background
The American Society for the Protection and Care of Animals estimates that there are over 87 million dogs in the United States. The pet care industry is thriving and growing rapidly. Dog parks are only the beginning for Find The BARK!. Features to come include adding to the map nearby dog friendly businesses (e.g. a cafe that has a patio where dogs are welcome and bowls from which they can drink), pet related retail locations, training classes and online groups for dog lovers.  

# Getting Started
In order to develop this website for your own personal use, you will have to clone this repository to a directory on your machine. You must have Ruby and Node installed. If you do not, use your favorite package manager to install them. After this, on your command line (terminal), type: bundle install. This will install the Ruby gems listed in the Gemfile. Next, on your command line, type npm install. This will install the node module dependencies listed in the package.json file.

In order to get the database up and running, in your .bash_profile, you will need to set the environment variable: MONGODB_URI To run the web app locally, you can set this value to https://localhost:4000, or another port. Next, you will need to follow these instructions on your command line:  

1. Type: brew info mongoDB
2. Copy the pathway listed at the end of the info readout. 
    It should look something like: mongod --config /usr/local/etc/mongod.conf
3. Get the database started by pasting the command into the terminal
    You will not see a message if the database has started successfully
4. Get your server started by entering: nodemon
    You should see a message, "The server is available" if the express server has started successfully

NOTE: There will be no parks in the database when you initialize it, but you can add parks through the website, or using Postman, or another such database interface. There is a parks.json file in the data directory that can get you started.

Contributors:
Brian Fiala, Ryan Cronin, Alexander Britcliffe

The Iron Yard, Washington, D.C. 2017
