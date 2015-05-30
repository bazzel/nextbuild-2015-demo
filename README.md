# NextBuild 2015 demo

This application I used at [NextBuild](http://nextbuild.nl/) 2015 as a demo for [my talk](https://github.com/bazzel/nextbuild-2015) about color schemes with [Sass](http://sass-lang.com/).

## Setup

    git clone git://github.com/bazzel/color-schemes-scss.git
    cd color-schemes-scss
    gem install bundler
    bundle install
    middleman
    
Open your favorite browser and navigate to [http://localhost:4567/demo.html](http://localhost:4567/demo.html).
    

## Instructions

By default, the pages uses color defined in `source/stylesheets/demo/_variabeles.scss`.
Uncomment the lines in `source/stylesheets/demo/_theme.scss` to apply the [Sass](http://sass-lang.com/) defined in the corresponding files:

* `source/stylesheets/demo/theme/_sass.scss` uses Sass functions for base- and complement colors
* `source/stylesheets/demo/theme/_sass-color-schemes.scss` uses my gem [Sass Color Schemes](https://github.com/bazzel/sass-color-schemes) for easy color scheme generation.