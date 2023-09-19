# Progressive Web App Text Editor

## Description

This project is a progressive web application where users can practice coding within an in-browser text editor. The web app will have an install function that allows users to save local data while remaining offline. The criteria for this project were as follows: 

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```
```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Installation

Installation for this application includes a few steps if using the CLI method. If using the Heroku link, installation involves clicking the ```Install!``` button located on the top left of the page.
If installing using the CLI method:
- Navigate to the root directory after downloading the code.
- run the command ```npm install``` here.
- CD into the /client folder
- run the command ```npm install``` here.
- Finally, CD into the /server folder.
- run the command ```npm install``` here.

- Upon installing all dependencies, navigate back to the root folder and run the command ```npm start```.
- This should build the application and console log a local server link to the web app.

Source code for the application can be found here: [PWA Text Editor code](https://github.com/IVignollesJeong/pwa-text-editor/tree/master/client).

## Usage

```Heroku Deployed Application```
![JATE demo](https://github.com/IVignollesJeong/pwa-text-editor/assets/131202032/68836c15-ee60-427f-b0f6-cbf8325e2c8f)


```Offline Installed Application```
![JATE offline demo](https://github.com/IVignollesJeong/pwa-text-editor/assets/131202032/5077a0ef-e5cb-46b1-8377-6cd1c42c49f5)



The application functions as follows:

- This app is meant to be a sort of "scratch sheet" for code. Users can use the web app to copy and paste code snippets both online and offline.
- The app will save local data upon leaving or refreshing. This functionality is also available offline by installing the app using the ```install!``` button located on the top left.
- Users can use this offline functionality to maintain their code snippets in an offline environment.

## Credits

[Express NPM package](https://www.npmjs.com/package/express) </br>
[WebPack NPM package](https://www.npmjs.com/package/webpack) </br>
[Concurrently NPM package](https://www.npmjs.com/package/concurrently) </br>
[Babel NPM package](https://www.npmjs.com/package/@babel/core) </br>
[CSS Loader NPM package](https://www.npmjs.com/package/css-loader) </br>
[Workbox/Service Worker NPM package](https://www.npmjs.com/package/workbox-sw) </br>
OSU Bootcamp Module 19 Starter Code</br>

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) </br>

MIT License

Copyright (c) [2023] [Ian Vignolles-Jeong]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

