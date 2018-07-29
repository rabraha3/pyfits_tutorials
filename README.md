# pyfits_tutorials
We will go over some ways to look at astronomical data with Python

## HI4PI

This data set is an all-sky survey of neutral Hydrogen (HI). At the time of this writing (2018), it is the highest resolution all-sky dataset. There are a lot of much higher resolution data of specific targets (i.e. individual interstellar clouds or galaxies), but none of them cover the same breadth as this survey. It corrects some known flaws of the previous all-sky survey (the Leiden-Argentine-Bonn survey) and thus provides a consistent dataset. 

I have previously used some of this data in my work on diffuse gamma-ray emission from the interstellar medium. I required an all-sky map of interstellar gas. Since the majority of gas in space is in the form of hydrogen, this HI4PI survey fit the bill!

This set of notebooks will take us through some Astropy tutorials (and maybe HEALPix) to visualize some of this dataset, which was featured on the [24 Oct. 2016 astronomy picture of the day](https://apod.nasa.gov/apod/ap161024.html).

### Steps

1. Make sure we are up-to-date with astropy.
> `conda update -y astropy` or `pip install astropy`
2. Install a separate library to deal with HEALPix projections
> `conda install -c conda-forge -y astropy-healpix`
3. Get APLpy for some image visualizations.
> `pip install aplpy`

