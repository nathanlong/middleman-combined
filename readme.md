# Middleman Combined

A bare-bones template for [Middleman](http://middlemanapp.com/) that combines:

- The smart defaults of [H5BP](https://github.com/h5bp/html5-boilerplate)
- [normalize.css](https://github.com/necolas/normalize.css)
- Mobile-first, inline media queries with [IE support](http://jakearchibald.github.io/sass-ie/)
- [Easy deployment](https://github.com/indirect/middleman-heroku-static-app) as a static app to Heroku for review and testing


Built for rapid responsive prototyping.

## To install:

    git clone https://github.com/nathanlong/middleman-combined.git
    mv middleman-combined ~/.middleman/combined

## Then to use with Middleman:

    middleman init my-new-project --template=combined
    cd my-new-project
    bundle install

## To push to Heroku:

    heroku create && git push heroku master
