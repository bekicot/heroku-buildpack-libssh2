Heroku buildpack: libssh2
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) of libssh2

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack https://github.com/stomita/heroku-buildpack-phantomjs.git

# or if your app is already created:
$ heroku config:add BUILDPACK_URL=https://github.com/stomita/heroku-buildpack-phantomjs.git

$ git push heroku master
```
