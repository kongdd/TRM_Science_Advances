# TRM_Science_Advances
Scripts for TRM algorithm for the paper published in Science Advances, 2020

1. Download all scripts in this repository.
2. Open A001_dTs_to_dBio.m, A002_dBio_to_dLAI.m, A003_TRM_T_bio.m, change all pathes to your local machine.
3. Prepare all your inputs for the TRM algorithm and put them in their right pathes. Each input file should be a 2-D matrix. For example, if you are using outputs from CLM5 with a resoultion of 0.47x0.63 (f05_g17), the size of the matrix should be 384 (Latitudinal direction)x576 (Longitudinal direction). The inputs for the 001_dTs_to_dBio.m are: albedo, ra, rs, emissivity, incoming shortwave radiation, incoming longwave radiation, specific humidity, air temperature and ground heat flux. When running A002_dBio_to_dLAI.m, an additional input, LAI, is needed. When running A003_TRM_T_bio.m, you may additionally need a vegetation land cover mask and trend for LAI.
4. Open A000_Main_TRM.m, RUN it.
5. Results are saved in .mat files.
