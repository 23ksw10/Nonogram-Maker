# Nonogram-Generator

## About the Project

**Nonograms** are picture logic puzzles. Mode details about Nonogram(https://en.wikipedia.org/wiki/Nonogram)


**Nonogram-Generators** can 
## Usage
---
GenNonogram.py [-h] [-d MAXDIM] [-b] [-n [NUMCOLOR]] [-r [GETRESULT]] image

    positional arguments:
        image: path to image to be processed

    optional arguments:
        -h, --help: show this help message and exit
        -d MAXDIM, --maxDim MAXDIM: maximum no. of squares in any dimension in the nonogram (default = 80)
        -b, --blackAndWhite: indicate the image should be converted to black and white
        -n [NUMCOLOR], --numColor [NUMCOLOR], --numColour [NUMCOLOR]: positive integer to denote the number of colors that should appear in your nonogram IN ADDITION to your background color. A 0 or negative integer means the algorithm will choose this number for you. (default = 0)
        -r [GETRESULT], --getResult [GETRESULT] boolean to indicate whether you want a separate file containing the finished picture (default = True)
