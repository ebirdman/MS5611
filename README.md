Arduino-MS5611
===============

This is a fork from 
Version: 1.0.0
(c) 2014 Korneliusz Jarzebski
www.jarzebski.pl

Fork and Changes by Vladimir Blanshey Nov. 2016:
- Removed Arduino ifdefs for Versions below v1.6
- Wire.begin() has been removed to be included in the user setup() code
as it is also used by other libraries and 
also general approach should be not to initialize neither instantiate 
one library inside another library.
- Added MS5611::getAltitudeFeet() in addition to MS5611::getAltitudeMeters()

