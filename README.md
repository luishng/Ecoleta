<h1 align="center">
  <img src=".github/logo-ecoleta.png" alt="Logo"><br /><br />
  <img src=".github/pessoas-ecoleta.png" alt="Logo Image" height="200">
</h1>

<h3 align="center">
  Ecoleta - The easiest way to throw away your trash
</h3>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/luishng/ecoleta?color=%2334CB79">

  <a href="https://www.linkedin.com/in/luishng/">
    <img alt="Made by" src="https://img.shields.io/badge/made%20by-Luis%20Henrique-%2334CB79">
  </a>
  
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/luishng/Ecoleta?color=%2334CB79">
  
  <a href="https://github.com/luishng/Ecoleta/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/luishng/Ecoleta?color=%2334CB79">
  </a>
  
  <a href="https://github.com/luishng/Ecoleta/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/luishng/Ecoleta?color=%2334CB79">
  </a>
  
  <img alt="GitHub" src="https://img.shields.io/github/license/luishng/ecoleta?color=%2334CB79">
</p>

# :pushpin: Table of Contents

<p align="center">
  <a href="#recycle-about-the-project">About the project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-getting-started">Getting Started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-features">Features</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a>
</p>

## :recycle: About the project

This project was developed on the Next Level Week event by [Rocketseat](https://rocketseat.com.br/) &nbsp;🚀

This software provide a flow to create recyclable garbage collection points and show in a map around you.

## 🚀 Technologies

**Language:**
- [TypeScript](https://www.typescriptlang.org/)

**Backend(Server):**
- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [Knex](http://knexjs.org/)
- [SQLite](https://www.sqlite.org/)

**Web:**
- [ReactJS](https://reactjs.org/)
- [React Router DOM](https://reacttraining.com/react-router/)
- [React Icons](https://react-icons.netlify.com/)

**Mobile:**
- [Expo](https://expo.io/)
- [React Native](https://reactnative.dev/)
- [React Navigation](https://reactnavigation.org/)
- [React Leaflet](https://react-leaflet.js.org/)

## 🔗 Features
- Register new drop-off location
- Search for the nearest drop-off location
- Connect locations to citizens

## 🏁 Getting Started

**Install the requirements**

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en/)
- [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/)
- [Expo](https://expo.io/)

**Clone the project and access the folder**

```bash
$ git clone https://github.com/luishng/Ecoleta.git && cd Ecoleta
```

**Follow the steps below for installation**

### Server

```bash
# Starting from the project root folder, go to server folder
$ cd server

# Install the dependencies
$ yarn

# Use the script to run the migrations
$ yarn knex:migrate

# Use the script to run the seeds
$ yarn knex:seed

# To finish, run the api service
$ yarn dev

# Well done, project is started!
```

### Web

_PS: Before to continue, be sure to have the API running (Backend - Server)_

```bash
# Starting from the project root folder, go to frontend web folder
$ cd web

# Install the dependencies
$ yarn

# Be sure the file 'src/services/api.ts' have the IP to your API

# Start the client
$ yarn start
```

### Mobile

_PS: Before to continue, be sure to have the API running (Backend - Server)_

```bash
# Starting from the project root folder, go to mobile folder
$ cd mobile

# Install the dependencies
$ yarn

# Be sure the file 'src/services/api.ts' have the IP to your API

# Start the expo service and scan the QR code with Expo Client
$ yarn start
```

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Made with 💜&nbsp; by [Luis Henrique](https://github.com/luishng) 👋 &nbsp;[See my linkedin](https://www.linkedin.com/in/luishng/) 👷