# Internal waves in Barkley Canyon

Ocean Physics MSc thesis at the University of Victoria, under the supervision of Dr. Jody Klymak. This research seeks to characterise the internal wave field at Barkley Canyon, off the coast of British Columbia, Canada. 

analysis.ipynb hosts primary code used for analysis of velocity data obtained from Ocean Networks Canada; contains processes for velocity, PSD, rotary spectra, and spectrogram plots. Also allows for a selection of specific data ranges for depth and time, and rotates and cleans data.

density_N2.ipynb takes formatted CTD data (from DFO, Line P cruises) and uses the Seawater analysis package to generate temperature, salinity, potential density, and buoyancy (N^2) plots.

'Documents' folder hosts working drafts of the Schedule, Analysis, and Proposal documents, among other useful information.

'GM' folder contains code to locally calibrate the GM spectrum, and the data for plotting.

'X_plots' folders are for plotting output from the analysis notebooks, for their respective analysis type (spectro_plots for spectrograms, etc.).

'Archive' folder contains outdated or no longer in use test-case notebooks, plots, and documents that are useful as a record, but are not regularly used for analysis.

