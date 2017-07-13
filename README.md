# flickr_explorer

With this simple javascript app you can search for photos on Flickr and have infinite scroll listing of the resulting search result. Just type some keyword for the photos that you are looking for in the above search bar and the result will appear here. You can then click on each thumbnail and see the large version of the photos (if it's available by Flickr) and alos some details about that photo.

## Demo
https://emkamal.github.io/flickr-explorer/

## Dev
To setup the script on your own machine, clone the repo and then install all the dependencies by using this command on the console:
`npm install`
This will install all the required package, it will take a few minutes so relax and have a cup of coffee while waiting :). After it's done, execute this command:
`npm start`
It will then run the app in the development mode. Open http://localhost:3000 to view it in the browser.

# Build
The build system uses Webpack. It will generate the build folder containing all the optimized and bundled script to be used in production. Builds the app for production to the build folder. Everything would be minified and the filenames include the hashes. It will then ready to be deployed. To build it, use this command
`npm run build`

## Toolchain
Javascript ES6, React, ReactDOM, React Scripts, React Infinite Scroller, Webpack, Babel, Qwest