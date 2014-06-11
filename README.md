A collection of scripts and codes to hadronise the VBF_NLO samples. 

There requires further work to decaylhe.f since in the outputted LHE, information on status, mothers, colour flow and spin is lost. 

Also note, the code covers up to 15 particles- from the incident protons, the hard scattering and to the 4 neutrino final state. More particles can be added if necessary.

This shoudln't be a problem if the status array is filled properly, so that Delphes can skip the irrelevant particles. 
