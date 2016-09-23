
# Conceptual System
## Assumptions
 less than 4 sirens in Assen
 timestamps of the sensors are syncronised
 sampling rate is twice much as the frequency of sirens frequency

 ## Implementation
 Get first sensor(s) that picks up the sound data(by thresholding)
 Set these sensors as origin(s)
 Obtain time intervals at which the sound goes above the threshold for each sensor with timestamps till all working sensors
 have picked up the sound
 Using triangulation techniques approximate the locations of the sirens.

## Classification 
 **Durrant-Whyte**

  cooperative-
   As we are using the data from multiple sound sensors to arrive at a conclusion about a siren location. The sensors
   cannot determine the location of the siren on their own and hence are classified as cooperative.


 **Boudjemaa & Forbes**

 Fusion across domains:-
  All the sensors measure the same attribute (i.e. sound ) over different ranges(distances).
  Hence by the definition this can be considered fusion across domains
