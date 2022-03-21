# FRB_subsecond_periodicity

Software used in preparing the paper by the CHIME/FRB Coll. "Sub-second periodicity in a fast radio burst".

- `profile_model.ipynb` has been used to model the FRB profiles after correcting for dispersion, as explained in the paper. For every FRB, it estimates the amplitude, width and position (or times of arrival, ToAs) for each peak, plus a global scattering timescale.
- `Timing_analysis.ipynb` uses the FRB profiles and ToAs to calculate a periodicity.
- `Plots.ipynb` is used to produce the plots visible in the paper.
- `plots` contains the output plots included in the publication.
- `data` should contain archives with numpy arrays used in the notebooks. The files are available at www.TEMP
