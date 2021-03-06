
# Jukebox

#### Intro

Jukebox is an app tailored to developers that are interested in tapping into a third-party API. At Jukebox, users can find easy access to a consolidated list of popular APIs for their reference. By the click of a button, developers will have direct access to their documentation so that may view their installation instructions without having to scramble through Google searches to find them. This app will provide ratings for an API's documentation, support, tools, and installation difficulty.

#### Data Models
<img src="./project_assets/DataModel1.jpg" style="width: 150px;">
<img src="./project_assets/DataModel2.jpg" style="width: 150px;">
<img src="./project_assets/DataModel3.jpg" style="width: 150px;">



#### Wireframes
<img src="./project_assets/Wireframe1.jpg" style="width: 150px;">
<img src="./project_assets/Wireframe2.jpg" style="width: 150px;">
<img src="./project_assets/Wireframe3.jpg" style="width: 150px;">
<img src="./project_assets/Wireframe4.jpg" style="width: 150px;">
<img src="./project_assets/Wireframe5.jpg" style="width: 150px;">

#### Check out the user stories for this app on our [Trello](https://trello.com/b/LXTSH04c/wdi-sm-43-project-3)!
#### Technologies used:
+ HTML
+ CSS
+ Javascript
+ jQuery
+ AJAX
+ Node.js
+ Express
+ Mongo DB
+ Bootstrap
+ Trello
+ Google OAuth
+ Git & Github
+ Heroku

#### Approach
This project will consist of two models: API and User. Our API model will include ratings for the components of an API that we previously mentioned (installation difficulty, documentation clarity, API difficulty) and will reveal whether there is support offered (such as an FAQ or a forum), as well as the number of tools offered. Full CRUD will be provided for users to create, edit, update, and delete their profile. For the minimum viable product, the ratings will be determined by the creators of this app, Squad Uno.

#### Stretch Goals
- Allow users to make a favorites list of the APIs they like the most ✓
- Allow users to update their ratings ✓
- Search for API by name ✓
- Enable users with permission to rate the API tools, so that we can provide user-ratings as well as pro-ratings ✗
- Allow users to write reviews on APIs ✗
- Build a user forum for Q&A ✗
- Provide notifications for API updates ✗
- Recommendation of API based on experience level ✗

<img src="./project_assets/Stretchgoals.jpg" style="width: 150px;">

#### Unsolved Problems
- Admin setup is not finalized. As a workaround, current admin users are hard-coded into our app
- Search bar is currently case-sensitive

#### Installation Instructions
- Clone the repo
- $ npm install
- $ nodemon
- $ mongod
- Visit localhost:3000
- Enjoy!

#### Link to App on Heroku
[Click to visit the Jukebox App](https://jukebox-squaduno.herokuapp.com/)
