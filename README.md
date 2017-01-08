# Let's Get Started

You will need to install Quasar CLI first. This also requires that you have already installed [NodeJS](https://nodejs.org/en/). We'll be following some of the instructions shown in the [Quasar documentation](http://quasar-framework.org/guide/).

Goal for this section will be to get the initial dev app set up and running.

**Step 1: Install the Quasar CLI** 

In your terminal of choice, enter:

`$ npm install -g quasar-cli`

Once the installation of the CLI is finished, you'll have a number of commands available. Go ahead and see if the CLI is working. 

`$ quasar --help`

or 

`$ quasar -h`

You should see something like this:

![](https://github.com/skooppaos/quasar-example-app-and-tutorial/blob/1-0_-_Let's_Get_Started/images/quasar-help.jpg?raw=true)

or if you'd like to see the Quasar CLI version you are working with, enter:

`$ quaser -V`


###  The `init` Command

`init [application name] <directory name>`

The `init` command is responsible for creating an initial Quasar application. "[application name]" is optional if you'd like to call your application a different name than the directory. `directory`is the name of the directory where the initial application is stored, relative to the location you are at in the shell.

We'll be covering the other commands later. 



**Step 2: Create the initial application**
______


Enter in your console:

`$ quasar init Radiatum`

You will see Quasar install the app. 

![](https://github.com/skooppaos/quasar-example-app-and-tutorial/blob/1-0_-_Let's_Get_Started/images/initial-app-install.jpg?raw=true)




**Step 3: Install the dependencies**
_____

Now you can change the directory down to the directory created by the `quasar-init` command.

`cd Radiatum`

Now carry out the installation of the necessary dependencies.

`npm install`

This will take some time, as there are a lot of dev dependencies necessary for Quasar to offer its cool developer experience.


**Step 4: Start the Dev Server**
______

Once the installation is finished, your ready to get rolling with Quasar application development. 

Enter:

`quasar dev`

Once Node.js is finished running the server scripts, it will automatically open the browser with the initial app page.

![](https://github.com/skooppaos/quasar-example-app-and-tutorial/blob/1-0_-_Let's_Get_Started/images/initial-app-page.jpg?raw=true)

If you look at the skeleton directory of the application set up by the CLI, you should see the following.

![](https://github.com/skooppaos/quasar-example-app-and-tutorial/blob/1-0_-_Let's_Get_Started/images/initial-directory.jpg?raw=true)

We'll also explain more about each directory as we move further into the tutorial. 

Well done! You've created an initial quasar application.

Now let's set up the back-end for the application. 

