Dataset Preparation
=============
## You can follow "Landsat preprocessing workflow" (https://github.com/ceholden/landsat_preprocess) to access, search, download, and unzip your Landsat images, as well as run Fmask with customizable parameters and create spatial subsets. 

## You can also find these locations of existing samples for download

- Harvard Forest, Massachusetts, USA (path13, row030)
    + [Footprint]
    + [Download](http://ftp-earth.bu.edu/public/ceholden/landsat_stacks/p013r030.tar.bz2) 167MB
    + Stack pattern
    + File format
    + Size
- Amazon basin, Brazil (path 255, row 066)
    + [Footprint]
    + [Download]
    + Stack pattern
    + File format: GeoTIFF
    + Size
- Denver, Colorado, USA (path 034, row 033)
    + [Footprint]
    + [Download]
    + Stack pattern: `L*stack`
    + File format: GeoTIFF
    + Size


## Data Format:

- Landsat 4-7 (8 band stacks)
    + Band 1 SR (SR * 10000)
    + Band 2 SR (SR * 10000)
    + Band 3 SR (SR * 10000)
    + Band 4 SR (SR * 10000)
    + Band 5 SR (SR * 10000)
    + Band 7 SR (SR * 10000)
    + Band 6 Thermal Brightness (C * 100)
    + Fmask/cFmask
        * 0 - clear land
        * 1 - clear water
        * 2 - cloud shadow
        * 3 - snow
        * 4 - cloud
        * 255 - NoData
        
- Landsat 8 (8 band stacks)
    + Band 2 SR (SR * 10000)
    + Band 3 SR (SR * 10000)
    + Band 4 SR (SR * 10000)
    + Band 5 SR (SR * 10000)
    + Band 6 SR (SR * 10000)
    + Band 7 SR (SR * 10000)
    + Band 10 Thermal Brightness (C * 100)
    	Notice: TIRS data acquired from January 1, 2016 to March 31, 2016 will be reprocessed and made available in April 2016, due to the detection of anomalous current levels associated with the scene select mirror (SSM) encoder electronics.
    
    + Fmask/cFmask
        * 0 - clear land
        * 1 - clear water
        * 2 - cloud shadow
        * 3 - snow
        * 4 - cloud
        * 255 - NoData

Notice: Your dataset should be in either GeoTIFF or ENVI band-interleave by pixel (BIP) format.



## Dataset directory structure for a Landsat scene

- Directory structure example (p225r066)

## Link Configuration? (https://github.com/ceholden/yatsm/blob/master/docs/guide/configuration.rst)


