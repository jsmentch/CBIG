# Surface plots
This folder contains code to generate the cortical surface figures for the project Task-Rest Behavioral Prediction in Children

# What does this folder contain?
* `CBIG_TRBPC_cortical_surface_projection.m` : This function will generate `.annot` files to generate surface figures for the cortical ROIs. Requires output (`vec_relevance_sum_conjunction.mat`) from `../matrix_plots/CBIG_TRBPC_edges_conjunction.m`
* `CBIG_Ruby_create_annot_r_overlay_Schaefer400.m` : This function written by Ruby Kong is called by the above function
* `CBIG_TRBPC_freeview_annot_fslr164k.sh` : Call this bash script (written by Ruby Kong) to generate surface figures from `.annot` files from `CBIG_TRBPC_cortical_surface_projection.m`



`
