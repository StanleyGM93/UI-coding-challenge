---
Learning node and SASS
---
1. Download NodeJS
1. Install NodeJS onto machine
1. Close any terminal windows
1. Check that node is running by typing `node` into terminal window
---
Initialising node for the project
---
1. Only run `npn init` if it hasn't been run before and the project hasn't been started
1. `npm init` was used to set up and store dependancies for the project
1. Enter and custom values at the prompts or press enter until complete
---
Installing dependencies
---
1. Run `npm i --save-dev sass`
1. A node_modules folder is created with all the dependencies held within
---
Setup of directories
---
1. Created a `scss` folder that acts as our _input_ folder
1. Scss files will be stored within the `scss` folder
1. Created a `css` folder that acts as our _output_ folder
1. Css files will be stored within the `css` folder
---
Workflow
---
1. Created an `index.html` and linked it to the stylesheet `./css/styles.css`
1. The `styles.css` file is produced by Sass
1. Use npx to run sass by using the `npm start` line
1. Look at the scripts section in the `package.json` file(in the `package.json` file a new script was added that outputs the `styles.css` file from the scss file)
1. Refresh in the browser to view any changes
1. The `npm start` command calls the `scss:watch` command that runs sass with a watch flag that automatically outputs a `stlyes.css` file after every saved change in a Sass file.
---
Bootstrap
---
1. Install the Bootstrap dependencies using `npm i bootstrap`
1. In the local sass input file add the line `@import "../node_modules/bootstrap/scss/bootstrap";` to include bootstrap into output file produced

