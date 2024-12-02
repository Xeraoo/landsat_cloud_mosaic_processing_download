# Landsat Cloud Mosaic Processing

This repository contains codes for downloading Landsat satellite images (Landsat 5 and Landsat 8) from Google Earth Engine. The scripts allow for the automatic selection of images with the least cloud cover in a defined region of interest (ROI) and the creation of mosaics from these images. They also include functions for exporting all spectral bands to Google Drive.

## How to Use?

### Steps in Google Earth Engine:
1. Open Google Earth Engine [here](https://code.earthengine.google.com/).
2. Create a new project and paste the code from this repository.
3. Define your region of interest (ROI) and the date range (e.g., for Landsat 5: March 1984–May 2012, for Landsat 8: April 2013–Present).

### Running the Code:
1. Click **"Run"** in Google Earth Engine. The code will automatically select images with the least cloud cover and create a mosaic.
2. The resulting file (with all spectral bands) will be exported to your Google Drive.

### Customizing the Code:
1. You can adjust the date range, ROI, and other parameters to suit your needs.
2. Use different configurations for different satellites (Landsat 5 or Landsat 8).

## How the Code Works:
- **Sorting by Cloud Cover**: The code sorts images based on cloud cover in the ROI and selects the one with the least amount of cloud cover.
- **Mosaic Creation**: If the ROI spans multiple images, they are combined into a single mosaic.
- **Export**: The final image with all bands is exported to your Google Drive account.

## Requirements:
- Google Earth Engine account.
