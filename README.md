# Cepheid-Variable-Star-Photometry
Photometry of Cepheid variable stars from raw FITS files to actual apparent magnitudes.
The sources used are V* V508 Mon and V* Y Aur.
Masterflats and normalised masterbiases were used to reduce the raw fits files of the two sources. 
The sources are found using DAOStarFinder from Photutils and the aperture that gives the optimal signal-to-noise ratio of the source is determined for each file.
The instrumental magnitude to actual magnitude calibration is carried out using data from reference stars taken from the VizieR Apass9 catalogue.
The light curves of the sources are created using the calculated magnitudes.
