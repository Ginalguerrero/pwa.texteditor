# pwa.texteditor

## Description 
The task is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

User/developer should be able to create notes or code snippets with or without an internet connection
so that they can reliably retrieve them for later use
 

## Usage 
Uses IndexedDB to create an object store and includes both GET and PUT methods

## Installation 
``npm run start``

``## DEMO``


``## Code snippet``


## Criteria

The application works without an internet connection

Automatically saves content inside the text editor when the DOM window is unfocused

Bundled with webpack

Create a service worker with workbox that Caches static assets

The application should use babel in order to use async / await

Application must have a generated manifest.json using the WebpackPwaManifest plug-in

Can be installed as a Progressive Web Application
