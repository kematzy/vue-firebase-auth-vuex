

# Vue Auth Firebase🔥 Vuex in a Progressive Web App (PWA)

> vue authentication firebase🔥 

![alt tag](https://i.imgur.com/5AnRW5j.png)

Simplified Firebase authentication for vue projects with support for Facebook & Google login & Github & Twitter and with support  Progressive Web Apps

## Config

### Step 1 - Enable Firebase Authentication support

![alt tag](https://images2015.cnblogs.com/blog/364241/201610/364241-20161031025159315-140732564.png)

In your [Firebase console](https://console.firebase.google.com/) within the Authentication section, enable your
desired Authentication options.

By default this repo supports the following authentication options:

* Email/Password
* Google
* Facebook
* Github
* Twitter


### Step 2
Rename `src/environments/environment-sample.js` to `environment.js` and replace existing contents with your own [Firebase Credentials](https://console.firebase.google.com/).

```js
export const environment = {
  production: false,
  firebaseConfig: {
    apiKey: 'APIKEY',
    authDomain: 'DEV-APP.firebaseapp.com',
    databaseURL: 'https://DEV-APP.firebaseio.com',
    projectId: 'DEV-APP',
    storageBucket: 'DEV-APP.appspot.com',
    messagingSenderId: '123456789'
  }
}
```


## Installation

```bash
# Git Clone Project
git clone git@github.com:kematzy/vue-firebase-auth-vuex.git

# Cd project
cd vue-firebase-auth-vuex

# install dependencies
npm install || yarn install

# serve with hot reload at localhost:8080
npm run dev || yarn dev

# build for production with minification and to build Progressive Web Apps
npm run build || yarn build
```


## Credit

This repo is a fork of the [vue-firebase-auth-dev](https://github.com/aofdev/vue-firebase-auth-vuex)
by [Aofdev](https://github.com/aofdev). It is he who deserves all the credit for his **great** work.



## Donation

All donations goes to [Aofdev](https://github.com/aofdev).

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=C9L4PNA5WH3LW)
