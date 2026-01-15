### This is a quick reference to understand the files used in the UCLA Mono Lake Model (UCLA-MLM). 
##### Note, this is not a user-supported interface, but rather a notebook set-up to run specific export criteria (and emission scenarios), which are output to a csv format that can be used for a simple user interface.

## File Descriptions

**11_UCLA_MLM_Sims_for_Simple_Interface.ipynb**: This is the primary primary python jupyter notebook. After downloading this and the files below, it can be run. No modifications to the code are needed except for user-defined options at the beginning (e.g. Start Year and Initial Water Level, and file input and output paths). The notebook will run the UCLA Mono Lake Model (UCLA-MLM) for three emission scenarios (SSP2-4.5, SSP3-7.0, and SSP5-8.5) and several export criteria that were defined to be of interest for a simple user-interface of the models results. These export criteria includes percent reductions from the existing export criteria, and several increments of post-transition export criteria. Results are output in a csv format expected by the simple user interface.

**data.tar**: This must be unpacked/untarred to run 11_UCLA_MLM_Sims_for_Simple_Interface.ipynb. This contains the climate projections across Mono Basin that are required as critical components for the Mono Lake Water Budget (e.g. precipitation on Mono Lake).

**Mono_Lake_Area_Storage_Elev.txt**: This contains the relationship between Mono Lake storage, water level, and surface area

**details_for_model.csv**: This contains a few fine-tuned parameters that are used by the UCLA-MLM
