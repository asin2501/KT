# Gulp Starterkit

## About 
This is a useful starter kit to help you prototype faster. It follows the
opinionated styles and includes our favorite front end tools.

Includes
--------
* [Gulp](http://gulpjs.com): Converts files and task running
* [Coffeescript](http://coffeescript.org):
  Write javascript with simpler syntax
* [Sass](http://sass-lang.com):
  CSS with superpowers
* [Bourbon](http://bourbon.io):
  Sass mixin library
* [Neat](http://neat.bourbon.io):
  Semantic grid for Sass and Bourbon
* [Bitters](http://bitters.bourbon.io):
  Scaffold styles, variables and structure for Bourbon projects.
* [Express](http://expressjs.com): Lightweight Node web server


Getting Started
---------------
Set up your project in your code directory
```
git clone git@github.com:no-two/prototype-gulp.git your-project-folder
cd your-project-folder
git remote rm origin
git remote add origin your-repo-url
```

Install the dependencies
```
npm install
```

Run the server
```
gulp
```

Deploy to Github Pages
```
gulp deploy
```

Stylesheets, images, fonts, and javascript files go in the `/source/assets/` directory.
Vendor stylesheets and javascripts should go in each of their `/vendor/` directories.
The source folders for images and fonts have a `.keep` file in them so they can be in the repo, but you can remove those files.


SCSS Style Guidelines
---------------
Coming Soon

To Do's
---------------
- Favicon and Apple Icons
- Editor Config
- HTML Scaffold
- Shorter Folder Names  