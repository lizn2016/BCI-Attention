# BCI-Attention
A repository including multiple attentional modules designs for brain signal recognition tasks.
Scripts should run with `tensorflow>=2.8.0`

------

### File Briefs  
  ##### Training
`cv_exp.sh`: Bash script for calling `exp_5CV_SEED.py` with data from different subjects in SEED dataset.  
`DEAP_benchmark.sh`: Bash script for calling `DEAP_test_gen.py` specifying different subjects, experiment types and models with DEAP dataset.  
`exp_5CV_SEED.py`: Main script for training with SEED dataset. One should manually change models used in the script.  
`DEAP_test_gen.py`: Main script for training with DEAP dataset.  

  ##### Explorations, Analysis and Visualizations 
  These are less organised scripts. They were written as our experiments goes. So you probably will not use all contents in a given script, but just some parts of it for your purpose. 
  
  `DEAP_Plots.py`: Gather metrics from trained models with DEAP for benchmarking, analysis and make some visualizations.  
  `SEED_extra_plot.py`: Gather metrics from trained models with SEED for benchmarking, analysis and make some visualizations.  
  `sigma_effect.py`: Scripts for exploring the Kernel Attention Module (KAM)'s effect on backbone network with SEED dataset.
  
  ##### Other supporting files  
  `Modules.py`: Contains custom layers used for constructing network models.  
  `Models.py`: Contains different network models.
  ``
   `Utils.py`: Some utility functions
   `Visual.py`: Some function for general visualization purpose.  
   
------
### Demo Plots
