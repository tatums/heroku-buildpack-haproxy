## HAProxy Buildpack

A Heroku buildpack for [HAProxy](http://www.haproxy.org/) buildpack.

### Installation

To install this buildpack run:
```
$ heroku buildpacks:add https://github.com/tatums/heroku-buildpack-haproxy.git -a [YOUR-APP-NAME]
```

OR use a [tagged version](https://github.com/tatums/heroku-buildpack-haproxy/releases)

```
$ heroku buildpacks:add https://github.com/tatums/heroku-buildpack-haproxy.git#1.8.3 -a [YOUR-APP-NAME]
```

The buildpack will be installed on the next heroku deploy.
