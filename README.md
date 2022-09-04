# Hotel Booking App

This App will help travelers browse and book hotels.
Team Member: Jiajie Yin, Lei Li, Jiyoon Jeong

Appimage: https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage
frontend and backend: https://github.ccs.neu.edu/NEU-CS5610-SU22/SmartBooking-RacoonBread
Heroku frontend: https://smartbooking-racoon-frontend.herokuapp.com/
Heroku backend: https://smartbooking-racoon-backend.herokuapp.com/

Caution for Users : 
1. Our app is CASE SENSITIVE and please type all CITY name in SMALL LETTER when you search.
2. We put three cities which are berlin, madrid, and london in database. Please test the app with those cities as we didn't add a lot of cities in the  world.

## Iter 1 Screenshots & Progress

### _Jiyoon Clover Jeong_
---
- Starter person. Finished setting up all the file structure of api, .env, .gitignore. Mainly worked on backend.
- Set up connection between Node.js and MongoDB and installed necessary modules.
- Set up first API using Node.js and mongoDB CRUD Operations
- Set up Express Error Handling and MongoDB Authentication
- Set up JWT with Cookie

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/BackendSetup-Clover.png)
*Screenshot of api folder structure and some code*

---


### _Lei Li_
---
- Foucs on Frontend part - set up the framework of the frontend using REACT
- set up the connection between frontend and backend. REACT fetch and post/put data via Node express API to do the seach
- register/Login/logout pages and logics. using react login auth context api. The resister will make POST operation, write the new user into the database. 
- Acheive the functions to search hotel and room information based on the filter conditions. (GET operation)
- Reseave rooms in a specific hotel while loged in. (PUT/POST) It will also check the room availability and gray the checkbox if this room has already been booked by others
- Heroku deployment
- Help the team to debug.

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/LandingPage.jpg)
*Landing Page*

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/login.jpg)
*Log-In Page*

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/reserve.png)
*Reserve Page (the gray checkbox means not availability during this time slot)*




---


### _Jiajie Danny Yin_
---
- update cotrollers for room

- add routes for hotels/rooms/user

- update utils


![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/SearchResult.jpg)
*Search Result Page*

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/BookingPage.jpg)
*Booking Page - NOT completed*

---

## Iter 2 Screenshots & Progress

### _Jiyoon Clover Jeong_
---
- Fixed errors in various files in client directory
- Made app to be deployable condition
- Aggregating everyone's work in README

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/Iter2_Clover-fixed%20errors.jpeg)
*Screenshot of modified parts from github repo*

---


### _Lei Li_
---
- Fixed bug in login panel and function
- Added logout and resigter functions to both frontend and backend and the db operation.
- Enable reserve function


![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/Iter2_Lei_selectRoom)
*Select Room page*

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/Iter2_Lei_Loginemail)
*New Log-In Page*

---


### _Jiajie Danny Yin_
---
- Deploying Frontend

- Deploying Backend

- Pushing images to database


![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/Iter2_Danny_DeployingFrontend)
*Heroku Frontend *
![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/Iter2_Danny_DeployingBackend)
*Heroku Backend*

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/Iter2_Danny_PushImage)
*Pushing images to DB*

---

## Iter 3 Screenshots & Progress

### _Jiyoon Clover Jeong_
---
- Set up 'Stays' and 'My reservation' Page by creating Components such as reservationHeader and its css files, Page such as reservation and their routes.

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/Iter3.0%20-%20Clover%20-%20Setup.png)
*Github commit code for new directories and modified files*

- Created and completed the Bootstrap UI component which was not featured in the class demo application. Our Group used Popover and OverlayTrigger from react-bootstrap on 'My reservation' page to show details of hotel information that user booked.

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/Iter3.0%20-%20Clover%20-%20Bootstrap.png)
*Bootstrapped with Popover and OverlayTrigger*

- Pushed correct and useful final version of data from axios to database for hotel and rooms and tested all the APIs that our group used for this project.

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/Iter3.0%20-%20Clover%20-%20Insomnia.png)
*Insomnia records*

---


### _Lei Li_
---
- Achieved Receiving data from frontend when user is booking and wrote the data in user database. Managed to display correct reservation information on 'My reservation' tab.

![Image Link](https://github.ccs.neu.edu/NEU-CS5610-SU22/BookingAppImage/blob/main/Iter3.0%20-%20Lei%20-%20Reservation%20Page.jpeg)
*My Reservation Page*

---


### _Jiajie Danny Yin_
---
- 


![Image Link]()
*Add Caption*

![Image Link]()
*Add Caption*


---

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
