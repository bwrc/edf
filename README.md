edf
=======

`edf` is an [R-package](https://www.r-project.org/) for reading physiologic data recorded in the [European Data Format (EDF)](http://www.edfplus.info/).

Installation
------------
To install the `edf` package in R, proceed as follows in R.

First install the `devtools`-package and load it:
```
   install.packages("devtools")
   library(devtools)
```

You can now install the `edf` package:
```
   install_github("bwrc/edf")
```

Usage
-----
To read data data recorded in the EDF format:

```
library(edf)
datafile <- "/tmp/signal.edf"
recording <- read.edf(datafile)
```

License
-------
The `edf` R-package is licensed under the [MIT-license](http://opensource.org/licenses/MIT).
