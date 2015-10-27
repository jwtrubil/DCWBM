# DCWBM
Distributed Climate Water Balance Model

**This is the development version. For the base version, switch back to the master branch**

This is an R package containing the model code for the Distributed Climate Water Balance Model, described in:

**Moore, R.D., Trubilowicz, J.W. and Buttle, J.M. (2012)**, Prediction of Streamflow Regime and Annual Runoff for Ungauged Basins Using a Distributed Monthly Water Balance Model. Journal of the American Water Resources Association, 48: 32–42. doi: 10.1111/j.1752-1688.2011.00595.x

The model described in the paper is an extension to the monthly water balance model from the USGS:

**McCabe, G.J. and Markstrom, S.L. (2007)**. A Monthly Water-Balance Model Driven by a Graphical User Interface. Open-File report 2007-1088. U.S. Geological Survey, 6 pp., Reston, Virginia

To install (for research version):

`devtools::install_github('jwtrubil/DCWBM', build_vignettes=TRUE, ref = 'research')`

If you are on windows, you'll need to install [Rtools](http://cran.r-project.org/bin/windows/Rtools/) along with the `devtools` R package in order to run the 'install_github()' command.

Load:
`library(DCWBM)`

Once loaded:
`?DCWBM`
for help.

Check out the vignette:
`vignette('owikeno', package = "DCWBM")`

For more updates on me, DCWBM, and other projects by me and my collaborators, check out:
[headwateranalytics.com](http://www.headwateranalytics.com)

This is the development version, updated to include using Precip as snow and outputting snow
