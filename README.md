# Project Overview

HTTP Archive File Viewer also known as HAR Viewer is a React App built With Webpack learnt from Tutsplus. HAR which stands for HTTP ARchive (HAR). It's a JSON format that describes the flow of network traffic into your browser. It is readily available in Chrome DevTools. Infact, if you go into Network Tab and right click you will see an option which reads "Save as HAR with Content". The HAR format has been a standard for several years now. It's also supported by all the modern browsers.


* babel-core, babel-loader and babel-runtime are used to transpile ES6 or ES2015 code to ES5 JavaScript.

* The css-loader, style-loader and sass-loader are used to convert the Sass files into CSS and eventually load them as style tags in the HTML.

* The url-loader is for loading the font files and the json-loader as the name suggest is for loading JSON.

* The html-webpack-plugin automatically creates the script tag and index.html for all the bundles in our project.

* Finally, webpack in itself is a node module. We also have the webpack-dev-server which is used at development time that automatically live reloads the browser based on changes and auto creates the bundle. This is extremely useful and definately a must have in any React project.
