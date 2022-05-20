A FITS file is a Flexible Image Transport System. Using `astropy` we can look at the header of a FITS file.

```python
from astropy.io import fits

hdulist = fits.open('image.fits')
hdulist.info()
```

#### Writing a `load_fits` program
```python
from astropy.io import fits

def load_fits(fits_file):
	with fits.open(fits_file) as hdul:
		hdul = fits.open(fits_file)
		data = hdul[0].data
	return data
```