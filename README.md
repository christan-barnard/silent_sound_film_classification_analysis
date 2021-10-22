# silent_sound_film_classification_analysis
## Repository content

The repository contains five python scripts, corresponding to the following sections of this thesis: 

1. The preliminary analysis conducted to assess model performance in respect of the shot scale data, 
2. The hyperparameter optimisation with respect to the k-NN model,
3. The hyperparameter optimisation with respect to theMLP model (as described in Section 4.3.2), 
4. The final performance evaluation of the MLP model with the Adam optimisation algorithm, and 
5. The 5x2 cross-validated paired t-test comparison of the L-BFGS-B and Adam optimiser MLP models (as described in Section 4.3.3).

The repository further contains:

1. An electronic copy of the thesis
2. The labelled silent-sound shot scale data set
3. The example model comparison data set which elucidates the required format of the classification performance results
   for the purpose of utilising the aforementioned 5x2 cross-validated paired t-test python script.
4. The Orange Data Mining Software concept demonstrator project file, 
   which forms the basis of the SHAP value analysis described in Section 5.1.1.

## A note regarding the naming of the shot scale data:

The title of the shot scale data was changed from "1.2 SilentSoundScale_asl_count30+" (as it appears in the code) to
"1.1_silent_sound_labelled_shot_scale_data" for the purpose of making the navigation of the GitHub repository more intuitive.

The same was done for the example model comparison data set: The title was changed from "L-BFGS-B vs Adam boxplot data test auc"
(as it appears in the code) to the more intuitive "1.2_example_model_comparison_data".
