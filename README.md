# Heroku Buildpack Tesseract

This package provides a custom Heroku buildpack with [Tesseract OCR](https://code.google.com/p/tesseract-ocr/) binary and all required libraries for Heroku apps.

Currently, only training data for English is supported.

# Usage:

Before deploying app to Heroku, run:

```
heroku buildpacks:set heroku/LANG
``` 
where LANG can be (ruby, python, scala, ... )
```
heroku buildpacks:add https://github.com/lnguyen46/heroku-buildpack-tesseract.git
```

# Example:

Here is [simple web app] (https://github.com/lnguyen46/tesseract-with-python-flask) using this buildpack.

# License

MIT.
