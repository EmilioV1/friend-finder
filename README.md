# Friend Finder

The user can take a survey and find a friend that has the highest compatibility based on a number of survey questions. Click [here](https://super-friend-finder.herokuapp.com/survey) to try it.

## Tools Utilized
* Express
* Path
* body-parser
* Bootstrap
* Chosen
* jQuery
* Heroku

## Instructions
1. Go to the home page and click on the "Go to Survey" button
2. You will be brought to a new page where you need to add your name and a photo url to associate with yourself
3. The following is a 10 question survey where you answer each one on a scale of 1 (Strongly Disagree) to 5 (Strongly Agree).
4. The app will then use an algorithm to calculate the friend that has the highest compatibility with you and display their name and photo back to you on a modal

## How It Works
The app stores each friend as a JSON object and once a new user takes the survey, it compares their answers with the rest of the friends in the friend list. The way this is calculated is by finding the absolute difference between the two users' scores and the one with the lowest difference has the highest compatibility.

You can also click on the "API Friends List" button towards the bottom of the page to view all the friends API in JSON format.

### App View
![friend](https://user-images.githubusercontent.com/33468221/71553058-37350200-29bd-11ea-8d50-4aed47734e59.png)

## Author
[Emilio Valladares](https://github.com/emiliov1/)
