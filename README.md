# kpc-toolbox
KPC-Toolbox: MATLAB toolbox to fit Markovian Arrival Processes

Current version: 0.3.2

Website: http://www.cs.wm.edu/MAPQN/kpctoolbox.html

This software is released under the MIT license, see LICENSE.TXT.
Inside MATLAB, use the command 'help Contents.m' to list the available commands. 

If you are using the KPC-Toolbox for scientific papers and reports, please consider citing the following publications:

[1] G.Casale, E.Z.Zhang, E.Smirni. 
KPC-Toolbox: Best Recipes for Automatic Trace Fitting Using Markovian Arrival Processes 
Elsevier Performance Evaluation, 67(9):873-896, Sep 2010.

[2] G.Casale, E.Z.Zhang, E.Smirni. 
Trace Data Characterization and Fitting for Markov Modeling
Elsevier Performance Evaluation, 67(2):61-79, Feb 2010.

**GETTING STARTED**

Add all directories to the MATLAB classpath, for example using the command:

 addpath(genpath('MY_INSTALLATION_PATH/kpc-toolbox')) 

A demonstrator of the tool can be run using the command

 demo_run 

To get help for the Markovian arrival process fitting tool, type

 help kpcfit_auto 

For the phase-type distribution fitting tool, type

 help kpcfit_ph_auto
