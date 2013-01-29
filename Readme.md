Heroku buildpack: ImageMagick
=============================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for ImageMagick with GS and RAW support.

It installs a custom copy of ImageMagick and Ghostscript to /app/im and includes it in the default paths.

Usage
-----

Example usage:

    $ heroku config:add BUILDPACK_URL=git@github.com:lemurheavy/heroku-buildpack-imagemagick.git