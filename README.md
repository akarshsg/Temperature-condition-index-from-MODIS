# Temperature-condition-index-from-MODIS
This code can be use be used to extract MODIS derived TCI at monthly interval
# Modis_LST_Processing

This project focuses on processing MODIS Land Surface Temperature (LST) data, calculating Temperature condition index (TCI), and exporting the results.

## Overview

The code is written in Google Earth Engine JavaScript API. It includes the following functionalities:

- Filtering and processing MODIS LST data
- Calculating monthly mean, minimum, and maximum LST
- Computing Temporal Composites of Interest (TCI)
- Visualizing the results on the map
- Exporting TCI ImageCollection to Google Drive

## Setup

1. **Google Earth Engine Account**: Make sure you have access to Google Earth Engine. If not, sign up [here](https://earthengine.google.com/).

2. **Earth Engine Code Editor**: Open the code in the [Earth Engine Code Editor](https://code.earthengine.google.com/).

3. **Geometry**: Adjust the `geometry` variable to your region of interest.

4. **Additional Libraries**: Make sure to load any additional libraries required for your specific functions.

## Usage

Run the code in the Earth Engine Code Editor. Visualize the results on the map and export the TCI ImageCollection to Google Drive.

## Acknowledgments

- [Open Earth Engine Library (OEEL)](https://github.com/openearthengine/library): Used for exporting ImageCollections to Google Drive.
- Spatial thoughts : this code is based on the VCI code of spatial thoughts



