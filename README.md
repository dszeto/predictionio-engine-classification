# [PredictionIO](http://predictionio.incubator.apache.org) classification engine for Heroku

Demo engine for the [PredictionIO Heroku buildpack](https://github.com/heroku/predictionio-buildpack). See the 📚 [README](https://github.com/heroku/predictionio-buildpack/blob/master/README.md) for how-to.

Based on the [attribute-based classifier template](https://github.com/apache/incubator-predictionio-template-attribute-based-classifier), minimally modified  machine learning on Heroku.


## [Data](data/) shape

Service plans are:

* `0` **Low Usage**: all usage capped at 300 minutes|megabytes|texts
* `1` **More Voice**: `0` + expanded voice to 1000 minutes
* `2` **More Data & Text**: `0` + expanded to 1000 megabytes|texts
* `3` **No Limits**
