# Pre Processing

ROOT / C++ macros used to pre-process the ROOT file data into images.

2 separate scripts to pre-process the signal or background files. 
Background differs by not having a while-loop to filter out the W bosons (particle ID == 24 or -24).
particle ID for gluon is 21 or -21
particle ID for quarks is < 6 or > -6


Output ROOT file will consist of histograms that are used to represent the pre-processed jet-image.

useful code for plotting the images/ histogram averaged over all events is commented out.

Strange bug that does not allow the macro to be run in ROOT version 6, runs fine in version 5, no error is reported by the compiler.


