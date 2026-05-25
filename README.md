|       Travis       |   Total downloads   |      Downloads     |     CRAN version   |
| :----------------: | :----------------: | :----------------: | :----------------: |
| [![Travis build status](https://travis-ci.com/WLOGSolutions/r-logging.svg?branch=master)](https://travis-ci.com/WLOGSolutions/r-logging) | [![CRAN total downloads](http://cranlogs.r-pkg.org/badges/grand-total/logging)](http://cranlogs.r-pkg.org/badges/grand-total/logging)| [![CRAN downloads](https://cranlogs.r-pkg.org/badges/logging)](https://cranlogs.r-pkg.org/badges/logging)| [![CRAN version](http://www.r-pkg.org/badges/version/logging)](http://www.r-pkg.org/badges/version/logging)|
 
r-logging
=========

R port of the popular Python logging package.

It implements hierarchical logging, multiple handlers at a single logger, formattable log records...

What you find here behaves similarly to what you also find in Python's standard logging module.

Far from being comparable to a Python standard module, this tiny logging module does include

- hierarchic loggers,
- multiple handlers at each logger,
- the possibility to specify a formatter for each handler (one default formatter is given),
- same levels (names and numeric values) as Python's logging package,
- a simple basicConfig function to quickly put yourself in a usable situation...

- some sample handlers, sending log records
 - to the console, 
 - to a file

for more information, have a look at the [online tutorial] (http://logging.r-forge.r-project.org/sample_session.php) 
on [r-forge] (http://r-forge.r-project.org/).

installation
============
For the last released package:
```
install.packages("logging")
```

if you want the latest from github, you could do:
```
devtools::install_github("mfrasca/r-logging/pkg")
```

if you have cloned the github repository while your working directory
was `BASE`, you may want to use your local, possibly altered copy:
```
devtools::install_local("BASE/r-logging/pkg")
```


<!-- badges: start -->
[![Codecov test coverage](https://codecov.io/gh/mfrasca/r-logging/graph/badge.svg)](https://app.codecov.io/gh/mfrasca/r-logging)
<!-- badges: end -->
