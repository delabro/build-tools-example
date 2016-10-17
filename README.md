# Build Tools Example

## Dependancies
Node.js

# Instructions

### Install dependancies in terminal

Change into project directory (folder) `cd /your project/directory`

run: `npm install`

### Run one of the following build scripts

* Compile CSS
run:  `npm run build:css`

Compile Sass to CSS and watches 'src/sass'
directory for changes.

* Lint and Browserify JavaScript 

run: `npm run build:js`

Lint and Browserify JavaScript and watch 'src/js' directory for changes.

* Compile CSS, Lint and Browserify JavaScript 

run: `npm run build:watch`

Compile Sass to CSS, Lint and Browserify JavaScript and watch 'src' directory for changes.

* Browsersync

While watch tasks are running opne a new terminal window to run Browsersync

run: `npm run browser-sync`

Sync browser when all HTML files and files in the 'public' directory change.

* Parallel Shell

run: `npm run build:dev`
Runs both 'npm run build:watch' and 'npm run borwser-sync' at the same time.

## Licence 

Licensed under the MIT Licence