The folder ''Data'' contains the filtered and normalized sEMG signals with movements and repetitions labels from the NinaPro DB2 dataset.

The file ''1_Export_MSC'' creates a folder for each subject containing the MSC matrices for each movement, in the form of 6x1 cell array (for the 6 repetitions). 

The file ''Run_SVM'' imports the MSC matrices, create the feature matrix and train and test a polynomial SVM. It returns the accuracy, precision, recall, F1 score, AUC and the simulation times for each subject. 

The file ''Plots_SVM'' takes the SVM results and plots different graphs and tables.

The file ''Run_SVM_StandardFeatures'' train and test the same SVM with 14 standard featurers extracted from the literature.


%Last modified: 17/03/2025 by Costanza Armanini