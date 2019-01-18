# mutations-v-coverage_inkling
I have a feeling that if i calculate the relationship between number <br />		
of mutations and expression/coverage, something good will come of it. <br />			
		
### Method <br />				
1. downsample dataset <br />

   maybe all of the cells from 2 given clusters <br />			
2. calculate coverage, transcriptome wide <br />				
   
   (bedtools?) <br />			
3. select gene panel of interest <br />		
   
   start with EGFR and Actin, maybe <br />			
4. normalize expression/coverage across all samples, for GOI <br />			
   
   (FPKM?) <br />						
5.  plot number mutations v. normalized expression <br />					
   
   grab mutation info from makeGeneCounts_parallel.py output  <br />					
			
   (s3://darmanis-group/singlecell_lungadeno/non_immune/analysis/geneCellMutationCounts.csv)<br />    				

			
