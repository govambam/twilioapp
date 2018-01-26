# Static Resume Website + Twilio App

Here are a few notes/steps on how to get your application (pun intended) noticed at Twilio. 

## Getting Started

Every employee at Twilio has made a Twilio app. In this tutorial we'll get your application on a website hosted by Bitballoon, integrated with Rollbar, and add a Twilio SMS workflow for good measure. Little to no coding required. 

### Create Accounts

First, we'll need to sign up for a few free trials. Just go ahead and sign up for these, and confirm your identity through email. We'll start using 'em later. 


* [Github](https://github.com/join) - For version control and duh. 
* [Twilio](https://www.twilio.com/try-twilio) - Also duh.
* [Zapier](https://zapier.com/sign-up/) - This'll make it much easier to get Rollbar to talk to Twilio. No code required.
* [Rollbar](https://rollbar.com/signup/) - Honestly this should have been at the top. 
* [Bitballoon](https://www.bitballoon.com/login) - This will host your resume online. Easy. Also if you did these in order you could have created your account using your Github credentials.  



### Downloads

Now we'll need to download and install a few things. 

* [Atom.io](https://atom.io) - Awesome text editor. This one is pretty self exmaplanitory. 
* [Github Desktop](https://desktop.github.com/) - We'll clone the template here and the UI makes life easier for a beginner.


## Getting Started (for real this time)

Now that we've got all of our accounts set up, let's clone the repo with our website template. 


```
https://github.com/RyanFitzgerald/devportfolio
```

Click on `Clone or Download` and then `Open in Desktop`. This should open Github desktop if everything worked correctly. In the window that pops up, click `open this repository`.

This should open the repo in your Finder. Open up Atom, go back to finder, select all the files and folders, then drag and drop into the empty Atom window. This should open all the trees on the left. We'll work on updating the information with your personal details later. 


## Installing Rollbar

Go back to rollbar.com and select `Browser JS` from the options on the left. Copy the code snippet that appears on the right, and open Atom again. 

Navigate to the `index.html` file. At the top of the file, find the `<header>` section. Paste the Rollbar code snippet directly under the `<header>`.Save the file and this should intitialize Rollbar on the page and error data should be sent to the project right away. To test that the integration worked. 

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
