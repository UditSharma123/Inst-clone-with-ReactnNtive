# Welcome to InstagramClone 👋
![Version](https://img.shields.io/badge/version-0.1-blue.svg?cacheSeconds=2592000)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![runs with expo](https://img.shields.io/badge/Runs%20with%20Expo-000.svg?style=flat-square&logo=EXPO&labelColor=f3f3f3&logoColor=000)](https://expo.io/)
[![image](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/simcoder_here)
[![image](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/simcoder_here/)
[![image](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCQ5xY26cw5Noh6poIE-VBog)

> Main repository of the SimCoder's youtube series &#34;Make an App like INSTAGRAM&#34;

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

