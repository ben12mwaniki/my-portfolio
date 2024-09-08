# My portfolio

I am ben12mwaniki and this repo hosts code for my software engineering portfolio available [here](https://ben12mwaniki.github.io/my-portfolio/). The portfolio showcases my developer journey highlighting my experiences, projects and continued learning.

This repo evolved from a template by ryanfitzgerald available [here](https://github.com/RyanFitzgerald/devportfolio).

## Features

* Gulp ready (compiles Sass and minifies JS)
* Sass ready
* Static yet fully responsive
* Comes with Bootstrap grid system
* Easy colour changes can be done through simple variable edits

## Setup and Configuration
To setup, simply fork the repo and run `npm install` in order to get all the Gulp dev dependencies. Next, run `Gulp watch` to compile the Sass and minify the JavaScript. Alternatively, if you don't have Gulp installed globally, you can run the npm script `npm run watch`. Any changes done to the JavaScript (js/scripts.js) or Sass (sass/styles.scss) will be autocompiled and ready to go.

If you encounter errors with `npm install` above, you can copy the dependencies from `package.json` and install them one by one. On figuring out which dependency is causing the error, search up its latest version and update it accordingly in the `package.json` file.

All scripts are within `js/scripts.js` and get minified to `js/scripts.min.js`. All styles are in `sass/styles.scss` and get compiled to `css/styles.css`. Both the minified scripts file and compiled CSS file are what is loaded on the page by default.

