# Marketplace

#### By Matt Miller

##Description

An app to manage a record store marketplace and inventory.

## Setup/Instillation
* Clone repository from https://github.com/mattfmiller/record-store-firebase-query

#### Node.js Prerequisites
* Install Node.js https://nodejs.org/en/
* Install Node Angular Cli package, open terminal and run `npm install -g @angular/cli` https://cli.angular.io/
* Install Node TypeScript package, open terminal and run `npm install typescript -g`
* (Optional for Atom users) Install Atom TypeScript package, open terminal and run `apm install atom-typescript`
* Open terminal, navigate to project root folder and run `npm install`

#### Firebase Setup
* Navigate to https://firebase.google.com/
* In console view click + Add project
* Enter project name and country then click Create Project
* Go back to project page in Firebase and click Database under Develop on the left sidebar
* Go to Realtime Database and click Get Started, toggle Start in test mode and click Enable
* Click the vertical ellipsis icon to the right of the + - icons and select Import JSON
* Browse to the project folder sample.json file and click Import
* Go to Firebase project page and click Add Firebase to your web app
* Copy the following section of data from the window that opens:<br><br>
  &nbsp;&nbsp;&nbsp;&nbsp;apiKey: "",<br>
  &nbsp;&nbsp;&nbsp;&nbsp;authDomain: "",<br>
  &nbsp;&nbsp;&nbsp;&nbsp;databaseURL: "",<br>
  &nbsp;&nbsp;&nbsp;&nbsp;projectId: "",<br>
  &nbsp;&nbsp;&nbsp;&nbsp;storageBucket: "",<br>
  &nbsp;&nbsp;&nbsp;&nbsp;messagingSenderId: ""<br><br>
* Open cloned project folder and create file src/app/api-keys.ts
* Go to api-keys.ts file and enter the following with the information from your Firebase project<br><br> export const masterFirebaseConfig = {<br>
  &nbsp;&nbsp;&nbsp;&nbsp;apiKey: "...",<br>
  &nbsp;&nbsp;&nbsp;&nbsp;authDomain: "...",<br>
  &nbsp;&nbsp;&nbsp;&nbsp;databaseURL: "...",<br>
  &nbsp;&nbsp;&nbsp;&nbsp;projectId: "...",<br>
  &nbsp;&nbsp;&nbsp;&nbsp;storageBucket: "...",<br>
  &nbsp;&nbsp;&nbsp;&nbsp;messagingSenderId: "..."<br>
};<br><br>
* To view project in development mode, navigate to project root folder and run `ng serve --open`

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.

## Technologies Used

* CSS _(Bootstrap 4.1)_
* jQuery
* Node.js
* Angular CLI
* Firebase

## License

* GPL

Matt Miller © 2018

## Further help
For help with this app, contact matt.f.miller@live.com
<br>
To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
