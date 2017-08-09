# motion analysis max objects

## max objects performing motion analysis on the R-IoT's input

#### installation

Drop all subfolders somewhere into `Documents/Max 7/Library`.  
The `max-motion-features` folder contains a collection of max abstractions
computing some feature descriptors specific to gesture signals,
from accelerometer and gyroscope input.  

The three other folders contain nearly the same patches except that they all use
their own abstraction to receive the R-IoT's input, parse it, format it, etc :

* `max-bitalino-riot` uses the `bitalino-riot` abstraction
* `max-ircam-riot-v1.7` uses the `riot-v1.7` abstraction
* `max-ircam-riot-v1.8` uses the `riot` abstraction

#### getting started

Depending on the version of the R-IoT board you are using, and the version of
the firmware it runs, you should check one of the three subfolders :

* for the BITalino R-IoT, look inside `max-bitalino-riot`
* for IRCAM's R-IoT running firmware v1.7 or lower, see `max-ircam-riot-v1.7`
* for IRCAM's R-IoT running firmware v1.8 or above, see `max-ircam-riot-v1.8`