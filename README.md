# Prosodylab-AlignerModels

Models to be used in conjunction with Prosodylab-Aligner, v. 1.1 for alignment of laboratory speech production data

* Kyle Gorman <gormanky@ohsu.edu>
* Michael Wagner <chael@mcgill.ca>

## Funding

* FQRSC Nouvelle Chercheur NP-132516
* SSHRC Canada Research Chair 218503
* SSHRC Digging Into Data Challenge Grant 869-2009-0004

## Using Github

### Sign Up 

Go to [Github's home page](https://github.com) to make an account if you do not have one. 

### Installation

Open the Terminal application on your computer. In Terminal enter:

	$ git config --global user.name "YOUR NAME"
	$ git config --global user.email "YOUR EMAIL ADDRESS"

The first line tells Git how you would like to appear. The email address is where notifications are sent and should be the same email as the one in your email settings in your account. Privacy settings can be found on the website under ["Keeping your email address private"](https://help.github.com/articles/keeping-your-email-address-private/).


### Make a Copy (Fork)

On GitHub, navigate to [Prosodylab-AlignerModels](http://github.com/prosodylab/Prosodylab-AlignerModels). In the top-right corner of the page is a button "Fork". Click on it. You now have your own fork of the set of models.

### Create Local Clone of Your Fork

To use, edit, and create models on your computer, use git clone: 

	$ git clone WEB_ADDRESS_TO_YOUR_FORK
	$ cd Prosodylab-AlignerModels

Or, if your would rather avoid using Terminal, on your fork's page, find the "Clone in Desktop" button on the right side menu and click on it.

You can now edit everything on your computer!

### Commit Your Changes

To add your changes to the online version, you can commit your code by entering the following in Terminal while in your model folder:

	$ git commit -m "Commit message"

Include a message to describe the changes made and any information for future reference in the message.

### Create a Pull Request

To update your folder with other models and the main folder with your models, you can create a pull request. In your Terminal application enter the following to merge and fetch updates from the Prosodylab-AlignerModels:

	$ git pull origin master

If you would prefer to make a pull request on GitHub, go to your fork's page. There should be a green button "Compare & pull request" near the top-right corner. Follow the instructions on the page to complete your pull request. 


## What Should Be Included in Your Model

To create models, see the [Prosodylab-Aligner README](https://github.com/prosodylab/Prosodylab-Aligner). The [Prosodylab-Aligner](https://github.com/prosodylab/Prosodylab-Aligner) will create a .zip containing the model. This model is generated from a dictionary, .yaml file, and training data. 

When you merge your model with [Prosodylab-AlignerModels](http://github.com/prosodylab/Prosodylab-AlignerModels), it should include the model .zip, dictionary used to generate the model, a couple of .wav and .lab files for testing, and model documentation