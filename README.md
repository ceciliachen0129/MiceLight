# MiceLight
A python script that automatically detect the number of mice and calculates photo flux for IVIS Spectrum readout. Tested on data acquired by IVIS Spectrum 200.

## Requirements
- Python (> 3.7)
    https://www.anaconda.com/products/distribution
- Jupter Notebook
- pandas
```
pip install pandas
```
- numpy
```
pip install numpy
```
- scipy
```
pip install scipy
```
- matplotlib
```
pip install matplotlib
```
- pillow
```
pip install pillow
```
- opencv
```
pip install opencv-python
```
## User input
- FilePath: An absolute path or relative path of a project folder containing multiple sub-folders; each sub-subfolder contains one or more IVIS image folders.
```
# Folder structure:
# > Selected folder<  <-
#    |-A
#    | |- IVIS image folder 1
#    | |- IVIS image folder 2
#    |-B - ....
#   ...
```
- LuminScanMode: "BoundaryFit" or "CircularFit", determind the ROI signal recognition pattern. "BoundaryFit" creates ROIs that fit tightly around the signal peaks. "CircularFit" creates ROIs of circular contours around the signal peaks.
## License

The source code for the site is licensed under the MIT license in the LICENSE.txt file.
