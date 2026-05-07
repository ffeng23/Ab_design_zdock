# README

## zdock_ff.tar

this is the stand alone package to do zdock .
It contains everything to do initial stage docking. I prepared and downloaded and pack together.
See github for detailed running and notes.
(this one has been saved to local S52Linux at hg folder for backup)
done on 4/29/2026

## requirement
(first 4 packages have been packed into tar file. see above)
+ zdock, need the old library lib2gc to run (has been packed into tar file)
+ zrank
+ libzdock
+ hbplus
+ pymol: need for cleaning and showing the structures
+ pdb-tools: need to install or calling as conda environment. See environment.yml

## usage
+ extract or download and install required libraries
+ create a subfolder and copy the receptor and ligand pdb structures into subfolder.
+ clean the pdb structures (see the github post for details, mainly to remove the atoms using pymol)
+ copy the snakemake file (two files to run) to the subfolder. (need to configure the snake file for correctly running)
+ run snake for the pipeline.
