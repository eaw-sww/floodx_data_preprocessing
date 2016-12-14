# floodx_data_preprocessing
Python script for preprocessing floodx data into uniform and readable format.

## Dependencies
 - Python 2.X
 - Optical character recognition (OCR) is used to read sensor values from images. The pytesseract (https://pypi.python.org/pypi/pytesseract) package used is requires that you install tesseract-ocr. The following Wiki is the reference guide: https://github.com/tesseract-ocr/tesseract/wiki.
 - The following Python packages are required:
  - **pandas** for working with time series
  - **os** for working with filesystem
  - **Image or PIL** for working with images
  - **pytesseract** for doing ocr
  - **glob** for selecting files with wildcards
  - **csv** for writing csv files
  - **re** for using regular expressions
  - **datetime** for working with datetime stamps
  - **tkinter** for creating GUIs
  
## Executing the script
 - Make sure the dependencies mentioned above are installed. 
 - Download and extract the following packages from the Zenodo data repository:
  - `floodX Datasets` (doi: ...)
  - `floodX Datalogger Images` (doi: ...)
 - The `floodX Datasets` package contains the default version of this script in the `code` folder.
 - If you wish to update the files in the `code` folder, you can replace them with the files of this Github repository.
 - Rename `settings.pyTEMPLATE` as `settings.py`, and update the paths in `metadata/metadata_ocr.csv` to point to where you unpacked the `floodX Datalogger Images` package.
