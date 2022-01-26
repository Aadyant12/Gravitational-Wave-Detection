# Gravitational-Wave-Detection
The aim of this project was to determine if the data reported, consisted of gravitational waves originating from mergers of binary black holes or just instrument noise.  

For this, data from 3 Earth-based gravitational wave interferometers (LIGO Hanford, LIGO Livingston, and Virgo) was used. Each of the detectors provided several sets of 4096 time-series values captured during a 2 second interval.  

Convolutional Neural Networks comprising layers such as Conv1D, MaxPool1D, GlobalAveragePooling1D etc. were designed and trained in this project. The accuracy was substantially increased from 50.84% to 81.93% using parameter tuning.
