## MOLGENIS R-api

The MOLGENIS R-api can communicate with a MOLGENIS host.

## Usage

You can import this project by executing:

```r
library(molgenisRApi)
```

When you want to install the package and it's depodencies automatically you can execute:

```r
install.packages("molgenisRApi", dependencies = TRUE)
```

This will import the right dependencies when you have installed them in your own environment.

With ```molgenis.``` you can view which functions are available to use with a MOLGENIS instance.

## Development

With the devtools and the roxygen2 library you can develop on this package. By importing the two libraries you can document the code and generate other dev-stuff.

```r
library(devtools)
library(roxygen2)
```

You can install the R-pacakge via Github when you have loaded the devtools-package (see above). Just run:

```r
install_github("#username#/#repo#")
```

Example:

```r
install_github("sidohaakma/molgenis-client-r-api")
```

@@ Todo

- Make the pacakge releasable (Jenkins)
- Perform Rstudio check
- Move general documentation to molgenis docs
- 