# ProjectU

![ProjectU Logo](/frontend/src/Images/ProjectU.png)

By [Ana Paredes](https://github.com/anagparedes)

Web application for Technical Test workshop in [Solvex](https://solvex.com.do/). The goal was to build a project management site where users can create new projects, add tasks, and update their progress as they work.

## Screenshots

![Landing Page](/frontend/src/Images/landing.png)

![Dashboard](/frontend/src/Images//dashboard.png)

![Profile Page](/frontend/src/Images//profile.png)

![Sign Up Page](/frontend/src/Images/register.png)

![Login Page](/frontend/src/Images/login.png)

## How to Start

Download or clone this repository. Then in both the ProjectU folder and frontend folder use:

```js
npm install
```

in order to download the dev tools and packages used in this application. We used Prettier to format this code and the project was linted with ESLint.
In order to get the MongoDB working, create a ".env" file in your project folder. Create variables in the .env file called MONGO_URL and SESSION_SECRET and set it equal to your Mongo connection string and secret phrase respectively. To run this program open up terminal to the main folder and another terminal window then cd frontend.
In main use:

```js
npm test
```

In frontend use:

```js
npm start
```

## Folders

- auth: contains Passport.js set up/config files
- db: contains a js file that connects the functionality established in the routes to respective collections in MongoDB
- frontend: contains all frontend material
  - public: houses index.js
  - src: contains javascript files and corresponding stylesheets used to build the site pages (organized by page/component)
- routes: contains the js files that run the express routing
