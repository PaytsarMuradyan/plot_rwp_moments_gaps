# plot_rwp_moments_gaps
**anl05122018_precip**  RWP data read from a binary files for the Vertical beam in Precip mode

**anl05122018_wind**    RWP data read from a binary files for the Vertical beam in Wind mode 
   - Header      - Gives info on time stamp of the measurement, mode parameters
   - Data block  - Gate# Dop SpecWidth SNR Noise
  
**wind_mode_05122018.mat**    Structured **anl05122018_wind** data saved to mat file for ease of use in python

   - Time    -  decimal UTC time
    - TW      -  serial date
    - Height  -  Height in km corresponding to gates for a given mode
    - Vel     -  Doppler
    - SNR     -  Signal-to-Noise ratio
    - Width   -  SpecWidth
