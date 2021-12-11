# Coursera FullStack Specialization

Project to practice along completation of the full stack specialization from Hong Kong University of Science and Technology

## Downloading the project

Clone the project within the desired local folder: https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository 

Next steps assume you are using git bash (or similar tool) and you are located within the project's folder.

----------------------------------------------------------------------------------------------------------------------------------------------------

# 1) Bootstrap 4 practice

## Installing needed packages

- Run 'npm install -g grunt-cli' to install grunt cli globally
- Run 'npm install -g gulp-cli' to install gulp cli globally
- Run 'npm install' for download and install all needed packages from npm repository

## Development server & Build the project

Using NPM scripts
- Run 'npm start' for dev server
- Run 'npm run build'

Using Grunt
- Run 'grunt' for dev server
- Run 'grunt build'

Using Gulp
- Run 'gulp' for dev server
- Run 'gulp build'
- If you are using Node.js 12+ you may encounter an error after lunch any gulp command like this one 'ReferenceError: primordials is not defined':
  - the project is already ready to fix it, you just have to re-run 'npm install"
  - for more info: 
    - https://github.com/gulpjs/gulp/issues/2324
    - https://stackoverflow.com/a/58394828/2933117

## Deploy the project

Using Github pages the web page has been served here: https://naxo85.github.io/Coursera_FullStack_Specialization/

The deployed version has been stored within gh-pages branch thanks to grunt-gh-pages plugin. 

To deploy a new version:
- Checkout to develop branch
- Run 'grunt deploy'


## Resources

- NodeJs:           https://nodejs.org/en/
- Lite-server:      https://github.com/johnpapa/lite-server
- Bootstrap:        https://getbootstrap.com/
- Flexbox:          https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- Font Awesome:     https://fontawesome.com/
- Bootstrap social: http://lipis.github.io/bootstrap-social/
- Jquery:           https://jquery.com/
- Less:             https://lesscss.org/
- Sass:             https://sass-lang.com/guide
- Grunt:            https://gruntjs.com/getting-started
- Gulp:             https://gulpjs.com/

----------------------------------------------------------------------------------------------------------------------------------------------------

