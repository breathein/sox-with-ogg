Heroku buildpack: sox
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for using [sox](http://sox.sourceforge.net/) with ogg support in your project.  
It doesn't do anything else, so to actually compile your app you should use [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi) to combine it with a real buildpack.

Lineage
-------

Shamelessly forked from the [ffmpeg heroku buildpack](https://github.com/shunjikonishi/heroku-buildpack-ffmpeg) by [Shunji Konishi](https://github.com/shunjikonishi).


You can verify that sox is installed by calling:

    $ heroku run "sox"

