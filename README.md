# RNAseq_Workflow
Workflow of RNAseq analysis starting with raw files

In Jupyter notebook: prep raw files for later analysis in R.
**CODE**
%%bash #this tells the notebook that all future code will be interpreted as Python code

#make symbolic link to the directory you're working in:
cd ~/ #cd="change directory to" ~/ = "home directory"
ln -s /home/research/snyder42/ #ln creates a link to the directory you want to be working in
  **If this does not work:**
  mkdir experiment_name/raw/reports #mkdir = "make directory," a manual method of setting up your working directory

