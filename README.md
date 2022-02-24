# NoteTaker 

![](https://img.shields.io/badge/license-MIT%20License-brightgreen)
## Description 
The motivation to build this project comes from wanting to build an application that can be used to wite and save notes. This application will use Express.js as a backend and will save and retreive notes from a JSON file. The code does not solve a specific problem, however it creates an application that allows a user to organize their thoughts and keep track of tasks that they may need to complete. Through this project I have learned how to use Express.js sucessfully to create a backend. I then learned how to connect this backend to a pre-made front-end and deploy the whole thing to Heroku.
## Table of Contents
- [Description](#Description)
- [Installation](#installation)
- [Usage](#usage)
- [Collaborators](#Collaborators)
- [License](#license)
- [Tests](#Tests)
- [Questions](#Questions)
## Installation
For this project you had to it was necessary to install two NPM package, Express and UUID. The first, Express.js is what enables Node.js to use javascript to act as a back-end. UUID on the other hand serves to create unique ids for the notes we were going to take in the application. You can install both of these with the `npm i` command, `npm i express` and `npm i uuid`. Because of the fact that I have created a package.json with the necessary dependancies, you couyld just run the `npm i` command and both of these packages will install to your machine automatically.
## Usage
After installing the required Dependancies, to deploy the app locally, all you have to do is run the `node .\server.js` in the file directory that the code lives in. 

You can see the process of deploying to heroku here:

![Heroku Deployment](/public/assets/imgs/Heroku_Deployment.png)


To deploy the app to Heroku, you first have to make sure that you have Heroku installed. Then you run the `heroku create` command int he root of the project. After that you run the following set of commands:

`git add -A`

`git commit -m "Pushing to Heroku"`

`git push heroku main` 

Finally, you can see that your application is successfully running by visiting the application URL that was provieded to you in the terminal you ran these commands.

This is a screencap of the deployed application.
![Screencap of Application](/public/assets/imgs/Screencap_of_application.png)

Click on teh plus sign at the top right to add a new note. Type in a title for the note and then type in the text of the note. To save the note, click on the save sign. 



The link to my deployed app can be found [here](https://radiant-everglades-43640.herokuapp.com/):

[https://radiant-everglades-43640.herokuapp.com/](https://radiant-everglades-43640.herokuapp.com/)

## Collaborators
I had no direct collaborators.
Howerver, I had one main source from which I ripped out a lot of my code from. I had used the in class mini project to base off a lot of the Server code that I wrote.I would also like to thank W3schools who had many informative articles.
## License
 This application is covered under the MIT License.
## Questions
If you have any questions, please reach to me via GitHub:

[Koilparampil](https://github.com/Koilparampil)

Or if you would prefer to email me, please email me at:

[koilparampil0126@gmail.com](koilparampil0126@gmail.com)