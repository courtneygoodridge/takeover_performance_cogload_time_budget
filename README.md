# The Impact of N-back-Induced Cognitive Load and Time Budget on Takeover Performance

## Overview: experimental design

The data associated with this manuscript was obtained from the same experiment as the one highlighted in the [gaze_entropy_heterogenous](https://github.com/courtneygoodridge/gaze_entropy_heterogenous) repo. However, the analysis within this repo focuses on understanding how cognitive load and time budget of a critical event influences eye movements, and the timing and quality of takeovers from Level 2 hands-off system. Participants experienced Level 2 hands-off automation using the University of Leeds driving simulator with their feet and hands away from operational controls. Participants took part in two drives, with each drive containing 10 events. Each event was comprised of 2 minutes of automated driving, followed by a takeover request (TOR). Upon the TOR, the driver would have to takeover control of the vehicle and drive manually. 4 events were critical and 6 were non-critical. Of the 4 critical events, 2 were severe (TTC = 3 s) and 2 were less severe (TTC = 5 s). During one drive, participants completed an auditory 2-back during automated driving; during the other drive they did not. The data analysed in this manuscript focuses on takeover response times and the vehicle dynamics during manaual driving following the automated driving. We also analysed eye movements during automation and in the manual driving following a takeover. 

![image](https://github.com/courtneygoodridge/gaze_entropy_heterogenous/assets/44811378/81f88195-4c04-42b0-acb9-0f61d6335bc3)

## Code and analysis

The data and code needed to replicate this analysis can be found within the repo. The file for the analysis is contained within the data file is is called `takeover.responses.critical.lat.long.csv`. These contain the individual trial responses for each participant, including manual and automated driving. In order to re-run plots and the models, the data can be analysed within the `manuscript_and_modelling_plots_takeovers.Rmd` script. However, the models may be computationally heavy so they can be loaded within the same script. 

To run this script, clone the `takeover_performance_cogload_time_budget` repository into your working directory (you can find this by running the `here::here()` function in the R command line). For more information on using the `here::here()`, see the [documentation](https://here.r-lib.org/). Once the repository is in your working directory, run each chunk of code to run the models and analysis.

Raw data for pre-processing is not available due to IP restrictions. If more information is needed regarding this, please contact me (c.m.goodridge@leed.ac.uk). 

