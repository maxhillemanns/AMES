# AMES
Automated Evaluation of Sarcomere Structures

The following libraries/environments are required:  
pandas, numpy, keras (tf backend), scikit-learn, matplotlib, scikit_image, seaborn, keras_explain

In all files "task_flags" are set as follows:  
0 for sarcomerisation classification  
1 for directionality classification  
2 for cell source classification  

"test_all.py" corresponds to the singular 2D model, "one_vs_all.py" to the 2D ensemble model and "test_all_3D.py" to the singular 3D model.
