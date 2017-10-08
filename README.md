# Heroku Buildpack for webpack

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for web applications that use webpack.

## Usage

The `bin/compile` script runs webpack with a CoffeeScript file (`webpack.coffee` in your main directory). To use the buildpack:

1. Add both this and the buildpack for nodejs like so:

   ```bash
   heroku buildpacks:add https://github.com/heroku/heroku-buildpack-nodejs
   heroku buildpacks:add https://github.com/erlandsona/heroku-buildpack-webpack
   ```

2. Deploy to Heroku.
