mapGraphColoring
================

Assign distinctive colors to neighboring polygons and map them using ColorBrewer schemes.

The main R command file is coloringWithGcolor in which neighboring polygon index will be created using spdep which is then used to assign 4 different colors to polygons. The main R code to assign 4 different classes was taken from now-archived “gcolor” (ineq.R* - downloaded from: http://cran.r-project.org/src/contrib/Archive/gcolor/). * NOT to be confused with “ineq”“ tool in the ineq library, which has nothing to do with "gcolor” library tools. 

ColorBrewer (http://colorbrewer2.org/) tool was used to assign unique colors - see 8 qualitative color schemes.

I found the following discussion thread useful: http://r-sig-geo.2731867.n2.nabble.com/Colouring-maps-so-that-adjacent-polygons-differ-in-colour-td6237661.html .
