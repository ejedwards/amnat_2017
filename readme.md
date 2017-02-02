Description of files (representing data, scripts, and results) associated with Edwards et al. "Convergence, consilience, and the evolution of temperate deciduous forests". American Naturalist, in revision.

The folder in which the README is located contains the following files/subfolders:

README.md : This very file.

/phylogeny/: this subfolder contains the phylogeny, the binary codings, the quantitative climate variables, and the scripts used to contstruct figure 1 and to perform all other viburnum-wide comparative analyses in the paper. All scripts are written for R and are .Rmd files.
	
	*120_taxa_tree.nex (Viburnum phylogeny, as a nexus file)

	*120_taxa_data.csv (trait data for all species included in phylogeny file)

	*comparative_analyses.Rmd (R markdown notebook, including commands for plotting trees, ancestral state reconstruction, and Pagel, PIC, and threshold analyses)

	*MrBayes_max_cred_tree.nex (138-taxon bayesian consensus tree with posterior probability values for all nodes, from Spriggs et al. 2015 (tree from which our 120-taxon tree was pruned))
	
/phenology/: this subfolder contains several further subfolders, each pertaining to a particular analyses of the phenological transect data:

	/fig3/: contains data, script, and subplots required for figure 3.
		
		*phen_sept2016_cleaned.txt (tab delineated text file containing raw leaf flush and senescence data)
		
		*fig3.Rmd (R markdown notebook including commands to produce species-level flushing and senescence curves of figure 3).
		
	/fig5/: contains data, script, and subplots required for figure 5.
		
		*phen_sept2016_condensed.txt (tab delineated text file containing raw leaf flush and senescence data)
		
		*fig5.Rmd (R markdown notebook including commands to produce species-level flushing and senescence curves of figure 5).
		
	/null_analyses/: contains data, script, and outputs generated to examine significance of species-specific flushing and senescece patterns.
	
		*phen_sept2016_cleaned.txt (tab delineated text file containing raw leaf flush and senescence data)
		
		*null_analyses.Rmd (R markdown notebook including scripts to generate null flushing/senescence patterns and test against observed. 
		
/climate/: contains data and scripts to generate figure 4, comparative climate profiles of field sites for phenology transects.

	*clim.txt (tab delineated monthly temp and precip averages for 4 sites)
	
	*climate_figs.Rmd (R markdown notebook including commands to produce climate plots for Figure 4).