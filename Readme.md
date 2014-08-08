Heroku buildpack: ImageMagick
=============================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for ImageMagick with GS and RAW support.

It installs: 
- ImageMagick 6.8.9-6
- Ghostscript ??? 
- GraphicsMagick 1.3.18
- UFRAW 0.19
to /app/im and includes it in the default paths.

Usage
-----

Example usage:

    $ heroku config:add BUILDPACK_URL=https://github.com/paulbaker3/heroku-buildpack-imagemagick.git
