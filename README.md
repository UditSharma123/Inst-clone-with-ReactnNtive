# Welcome to InstagramClone 👋

Make a web app Like INSTAGRAM
<br>

## ➕ Features

Currently the project has the following features:
  * expo boilerplate
  * Auth system 
  * Post Images w/ descriptions
    * Take pictures directly in app
    * Choose from gallery
  * Profile page
  * Follow/Unfollow users
  * Feed in chronological order
  * Search Users
  * Comment Posts
  * Comment Likes
  * Redesign
  
<br>

## 💻 Install

First you need to install Nodejs and npm, this is different depending on the OS you are running so it is easier to check the node [page](https://nodejs.org/en/download/)

Install [expo](https://expo.io/learn), if it fails run you might need to run this with sudo
```sh
npm install expo-cli --global
```

Install the needed packages while in the root folder of the project
```sh
npm install
```


Install firebase tools
```sh
npm install -g firebase-tools
```

Deploy the project to yout firebase projhect (make sure to have billing enabled for that project). copy the backend/functions/index.js into a different place
```sh
cd backend
firebase login
firebase init (choose functions, javascript, EsLint and install deplendencies)
```

Copy the index.js into the place of the new index.js
```sh
firebase deploy
```
<br>

## 📱 Usage

To Start expo all you have to do is run this line
```sh
expo start
```

>If you want to run on android you'll need to enable developer options and USB Debugging on your device

<br>

