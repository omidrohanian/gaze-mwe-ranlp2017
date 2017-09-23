### Prediction of multiword expressions using eye tracking data

This repository contains the source code, data, and analyses behind the paper "Using Gaze Data to Predict Multiword Expressions".

#### Data

We have annotated the text used in [GECO eye tracking corpus](http://expsy.ugent.be/downloads/geco/) with regards to occurrences of Verb+Noun and Verb+Particle [multiword expressions (MWEs)](https://en.wikipedia.org/wiki/Multiword_expression). For details about the data, please refer to the information file in the data folder.

#### Methodology 

We used the structured prediction model [CRF](https://en.wikipedia.org/wiki/Conditional_random_field) to label the sequences according to the classes defined in the tagged dataset.

THIS IS A TEST
