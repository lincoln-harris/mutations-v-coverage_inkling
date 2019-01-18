# mutations-v-coverage_inkling

`Lincoln Harris`           
`CZ Biohub, January, 2019`   

I have a feeling that if i calculate the relationship between number 	
of mutations and expression/coverage, something good will come of it.			
		
#### Method 
1. downsample dataset      
    maybe all of the cells from 2 given clusters    	  	
2. calculate coverage, transcriptome wide    				
      (bedtools?)     			
3. select gene panel of interest   
      start with EGFR and Actin, maybe     
4. normalize expression/coverage across all samples, for GOI  	    
      (FPKM?)    				
5.  plot number mutations v. normalized expression   				
      grab mutation info from makeGeneCounts_parallel.py output     				
	    (s3://darmanis-group/singlecell_lungadeno/non_immune/analysis/geneCellMutationCounts.csv)       				

			
