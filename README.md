# Let's Get Started

You will need to install Quasar CLI first. This also requires that you have already installed [NodeJS](https://nodejs.org/en/). We'll be following some of the instructions shown in the [Quasar documentation](http://quasar-framework.org/guide/).

Goal for this section will be to get the initial dev app set up and running.

**Step 1:** In your terminal, enter:

`$ npm install -g quasar-cli`

Once the installation of the CLI is finished, you'll have a number of commands available. Go ahead and see if the CLI is working. 

`$ quasar --help`

or 

`$ quasar -h`

You should see something like this:

***Insert Image of the Help here***

or if you'd like to see the Quasar CLI version you are working with, enter:

`$ quaser -V`


##  The `init` Command

`init [application name] <directory name>`

The `init` command is responsible for creating an initial Quasar application. "[application name]" is optional if you'd like to call your application a different name than the directory. `directory`is the name of the directory where the initial application is stored, relative to the location you are at in the shell.

We'll be covering the other commands later. 

**Step 2:** Create the initial application by entering: 
______

`$ quasar init Radiatum`

You will see Quasar install the app. 

***Insert Image of initial app install here***

**Step 3:** Install the dependencies
_____

Now you can change the directory down to the directory created by the `quasar-init` command.

`cd Radiatum`

Now carry out the installation of the necessary dependencies.

`npm install`

This will take some time, as there are a lot of dev dependencies necessary for Quasar to offer its cool developer experience.


***Step 4:*** Start the Dev Server
______

Once the installation is finished, your ready to get rolling with Quasar application development. 

Enter:

`quasar dev`

Once Node.js is finished running the server scripts, it will automatically open the browser with the initial app page.

***Insert Image of initial app page here***

If you look at the skeleton directory of the application set up by the CLI, you should see the following.


***Insert Image of initial app directories here***

We'll also explain more about each directory as we move further into the tutorial. 

Well done! You've created an initial quasar application.

