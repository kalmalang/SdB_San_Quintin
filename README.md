# SdB_San_Quintin
Colaboratory project for the determination of shallow water bathymetry from multispectral satellite imagery using deep learning

## Test data set
The data stem from sonar depth soundings and multispectral satellite imagery.

__Sonar data__
- Depth soundings in meter
- Values relative to elipsoid of WGS1984
- All values negative, the more negative, the greater the depth
- Sonar recordings made in March 2019

__Satellite data__
- RapidEye multispectral imagery with 5 m resolution
- Contains 5 bands (blue, green, red, red edge, near infrared)
- Rediometric, sensor, and geometric corrections applied
- Imagery obtained in May 2019

__Sources of error__
- Depth values from interpolated surface, not raw sonar soundings
- 2 month difference in data aquisition
- 5 m satellite resolution coarser than placement of random points (>= 1m apart) and depth surface cell size
