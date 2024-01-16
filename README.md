# Text Editor Web Application
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Description

This is a text editor web application designed for developers. It allows users to create notes or code snippets with or without an internet connection, ensuring reliable retrieval for later use. The application uses  JavaScript, webpack for bundling JavaScript files, and IndexedDB for database storage. It also includes a service worker using workbox for pre-caching static assets and pages. The application can be downloaded as a desktop icon for easy access and is deployable to Render/Heroku with proper build scripts for a webpack application.


## User Story
As a developer, I want to create notes or code snippets with or without an internet connection so that I can reliably retrieve them for later use.

## Acceptance Criteria

- Given a text editor web application, when I open my application in my editor, then I should see a client server folder structure.
- When I run `npm run start` from the root directory, then my application should start up the backend and serve the client.
- When I run the text editor application from my terminal, then my JavaScript files have been bundled using webpack.
- When I run my webpack plugins, then I have a generated HTML file, service worker, and a manifest file.
- When I use next-gen JavaScript in my application, then the text editor still functions in the browser without errors.
- When I open the text editor, then IndexedDB has immediately created a database storage.
- When I enter content and subsequently click off of the DOM window, then the content in the text editor has been saved with IndexedDB.
- When I reopen the text editor after closing it, then the content in the text editor has been retrieved from our IndexedDB.
- When I click on the Install button, then I download my web application as an icon on my desktop.
- When I load my web application, then I should have a registered service worker using workbox.
- When I register a service worker, then I should have my static assets pre cached upon loading along with subsequent pages and static assets.
- When I deploy to Render, then I should have proper build scripts for a webpack application.

## Installation

1. Clone the repository to your local machine.
2. Navigate to the root directory and run `npm install`.
3. Run `npm run start` to start the application.

## Usage

Open the application in your preferred browser. You can create notes or code snippets and they will be saved for later use, even without an internet connection.

## Deployment

The application can be deployed to Render with proper build scripts for a webpack application.

![image](https://github.com/Mohamedamin141/PWA/assets/138842903/88600f92-1b06-4f11-9a15-1d7e67771690)

## Link
https://pwa-applications-d0906edb6e2e.herokuapp.com/

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

