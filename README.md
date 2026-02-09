# Galaxy1 — HST XDF FITS Visualizer (Matplotlib)

A small Python script that loads the **Hubble eXtreme Deep Field (XDF)** FITS image from STScI and visualizes it using **Matplotlib** with **log-stretch normalization** to bring out faint galaxy detail. Uses **Astropy CCDData** + masking for clean handling of image data.

## Features
- Downloads/opens a public HST XDF `.fits` file (direct URL)
- Masks zero-valued pixels
- Log-stretch display for faint structure
- Matplotlib render with a formatted colorbar

## Requirements
- Python 3.9+ recommended
- `astropy`
- `numpy`
- `matplotlib`
- `photutils`

## Install
```bash
pip install astropy numpy matplotlib photutils
