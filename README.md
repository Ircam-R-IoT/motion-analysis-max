# motion analysis max objects

## max objects performing motion analysis on the IRCAM R-IoT's input

#### installation

Drop all subfolders somewhere into `Documents/Max 7/Library`.  
The `max-motion-features` folder contains a collection of max abstractions
computing some feature descriptors specific to gesture signals,
from accelerometer and gyroscope input.  

#### getting started

To see the whole set of abstractions in action, open the 
`riot-analysis-example.maxpat` patch, and connect your R-IoT to get some input.

There are some alternative firmwares on
[this repository](https://github.com/Ircam-R-IoT/motion-analysis-firmware), which
embed the computation of the same set of gesture descriptors implemented as
abstractions in `max-motion-features` in the R-IoT.
