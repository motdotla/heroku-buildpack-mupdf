# Heroku buildpack: MuPDF

![](https://raw.githubusercontent.com/motdotla/heroku-buildpack-mupdf/master/heroku-buildpack-mupdf.jpg)

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [MuPDF](http://www.mupdf.com/). 

## Usage

```
heroku create -b https://github.com/motdotla/heroku-buildpack-mupdf.git

# or if your app is already created
heroku config:add BUILDPACK_URL=https://github.com/motdotla/heroku-buildpack-mupdf.git

git push heroku master
```

## Recommended

Use [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi) to combine this buildpack with others. For example, [carve-worker](http://github.com/motdotla/carve-worker) does this.
