Heroku buildpack: Poppler
=======================

This [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) provides Poppler.

## Current version

* Fontconfig 2.13.94
* Poppler 21.09.0

## Tips for development

To flush cache:

    heroku plugins:install https://github.com/heroku/heroku-repo.git
    heroku repo:purge_cache -a appname
