# MLTermProject

## Implementation of:
## Dynamic Mode Decomposition for Real-Time Background/Foreground Separation in Video  
### Authors - J. Grosek and J. Nathan Kutz
Group 13  
By-  

Chinmay Parab		2019B4A70708G  
Shivam Chadha		2019B4AA0704G  
Vishesh Agrawal		2020A7PS0967G  

The implementation is done using PyDmd.  
PyDMD is a Python package that uses Dynamic Mode Decomposition for a data-driven model simplification based on spatiotemporal coherent structures.  
Using this we decompose the data into various frequency modes, and we use these modes to seperate the images into it's foreground and background component.

## Dataset 
We didn't use the dataset used by the paper because the Advanced Video and Signal based Surveillance (AVSS) Datasets were unavailable. 
We use the Highway dataset from the baseline category from [2014 ChanegeDetection.Net](http://jacarini.dinf.usherbrooke.ca/dataset2014#) (CDNET) dataset. 
The data is of a video of a cars moving on a highway road. The resolution is 320x240 and the number of frames is 1700.  
Before applying DMD we convert the image to grayscale and downample it by a factor of 2.5.  
Image shape - (320,240,3)  
After Processing - (96,128)
