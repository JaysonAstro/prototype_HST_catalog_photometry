# prototype_HST_catalog_photometry

example with functions based on https://qosmicqi.github.io/XRBID/chapters/photometry.html#sec-runphots
and https://www.astropy.org/ccd-reduction-and-photometry-guide/v/pdev/notebooks/photometry/00.00-Preface.html


TO DOs: 
- transform image and error from electron/s to Jy
- need to include valid mask based on weight image or other metric
- redefine circular apertures for ```aperture_photometry```