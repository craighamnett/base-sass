# About

A set of sass files that resets elements, builds up defaults and supplies common mixins for front-end development projects. Just clone it into your sass folder and @import it.


# Setup

You need to be familiar with [Sass](http://sass-lang.com/) and have the Haml gem installed.

    gem install haml
    

# Usage

Clone the base-sass project into your local project, in it's own folder.

    git clone git://github.com/mitchellbryson/base-sass.git sass/base

Import the main base styles in your project's main sass file.

    // e.g. in sass/styles.sass
    @import base/styles
  
Run the sass watcher to compile the css every time you save a sass file.

    sass --watch sass:css
