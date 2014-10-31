## Application to be solved

The input Earth Observation (EO) dataset will be MERIS Level 1 Reduced Resolution (RR) data and Full Resolution full-Swath (FRS) data, and some of it will have been pre-processed so that the auxiliary meteorological data contained within it varies i.e. there will be identical Level 1 TOA radiances, but varying values for mean sea level atmospheric pressure, surface wind speed, relative humidity and total column ozone.

The baseline AC code, IPF / MEGS (MERIS Experimental Ground Segment) prototype processor that's now run within Optical Data processor of the European Space Agency (ODESA), will be used to derive multi-spectral BOA reflectance data that can act as a Reference Data Set (RDS) alongside available in situ data. 

During the challenge the participants supply their own AC code (either as code compiled on the challenge platform or executables), and once the output BOA reflectance data has been collated it would then be compared to understand:

* Differences from using the same code, but with different meteorological values; as a single meteorological parameter and together as interactions may occur;
* Comparison against the baseline AC, which is the standard ESA MERIS archive processing;
* Comparison of the results against in situ data to determine match-up accuracy.
