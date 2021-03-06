### Prior preferences beneficially influence social and non-social learning
Data, code, and materials for Tarantola, Kumaran, Dayan, & De Martino. Prior preferences beneficially influence social and non-social learning. <i>Nature Communications</i> (2017).
Stan fit objects and response time model predictions are too big for GitHub, but are available on request (contact <a href='mailto:tor.tarantola@gmail.com'>tor.tarantola@gmail.com</a>). They can also be run locally using the Stan scripts (Stan models; see ***Analysis*** below) and the script in the "analyses" Jupyter notebook in the analysis_code folder (response time model predictions). Running models locally will result in slightly different outputs due to the stochastic nature of the sampling algorithm.

### Organization
* ***Data*** Raw and processed data files are contained in the 'data/' folder. Data from the social experiment are in the 'social' subfolder, and data for the non-social experiment are in the 'non_social' folder. Pilot data are in the 'social_pilot' folder. The 'combined' folder contains the processed data from both the social and nonsocial experiments, combined into a single data file. The participant log includes details on each participant, along with contemporaneous notes on the testing session.
* ***Analysis*** 'analysis_code/' contains IPython notebooks showing the data analysis and simulations included in the manuscript, as well as the Stan models and related scripts ('analysis_code/stan'). Each model is sampled by its matching 'sample_*.py' script.  
* ***Task Code*** The PsychoPy task scripts and stimuli are in the 'task_code/' folder. Participants in the social experiment completed 'infer_design1.py' and participants in the nonsocial experiment completed 'infer_design1_no_eyetracking.py.' (Participants in the social group underwent eye tracking to pilot a different study.) Item pairs were generated randomly by the 'pair_generator.py' script, and underlying choices for the practice block were generated by the 'inference_practice_choice_generator.py' script. These pairs and choices were kept the same for all non-pilot participants.


### Authors
<a href='http://www.tortarantola.com/'>Tor Tarantola</a> (Department of Psychology, University of Cambridge)<br>
<a href='https://sites.google.com/site/dharshankumaran1/'>Dharshan Kumaran</a> (Institute of Cognitive Neuroscience, University College London)</a><br>
<a href='http://www.gatsby.ucl.ac.uk/~dayan/'>Peter Dayan</a> (Gatsby Computational Neuroscience Unit, University College London)<br>
<a href='http://www.bdmlab.org'>Benedetto De Martino</a> (Institute of Cognitive Neuroscience, University College London)

### Contact
<a href='mailto:tor.tarantola@gmail.com'>tor.tarantola@gmail.com</a>

### Figshare
A copy of this repository is also on Figshare (DOI: 10.6084/m9.figshare.5198572), versioned to the git release tags.