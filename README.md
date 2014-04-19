# Heroku buildpack: mupdf

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [mupdf](http://www.mupdf.com/). 

## Usage

```
heroku create -b https://github.com/scottmotte/carve-worker.git

# or if your app is already created
heroku config:add BUILDPACK_URL=https://github.com/scottmotte/carve-worker.git

git push heroku master
```

