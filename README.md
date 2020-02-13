Live App: [https://bookstore-53917.firebaseapp.com/](https://bookstore-53917.firebaseapp.com/)

## How can you run this application locally?

I assume, you have Node.js on your computer. [Node.js installation](http://yoember.com/nodejs/the-best-way-to-install-node-js/)

* Please create an app on [Firebase](http://www.firebase.com) first. You can register there with one click and create a new app. You have to setup this app name in `config/environment.js`. (This will be your own cloud based database.)

* Clone this repository in your project folder
```
$ git clone https://github.com/juannaranjodev/bookstorember.git
```
* Change to the application directory
```
$ cd bookstorember
```
* Install node packages
```
$ npm install
```
* Setup in `config/environment.js` Firebase settings. ([Setup firebase in your Ember project](http://yoember.com/#setup-a-server-on-firebase))

* Launch the application with Ember server.
```
$ ember server
```
* Open the application in your browser
```
$ open http://localhost:4200
```
