library (raster)
# MB2
#Learning GIT with EAGLE
germany <- getData ("GADM", country = "DEU", level =2)
plot (germany)
prec <- getData ("worldclim", var ="prec", res = 0.5, lon =10, lat = 51)
