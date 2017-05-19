# BUC_v2
30 species:
	nIndividuals >= 5
	reads2SNP version Ballenghien et al 2017, contam=0.2

data:
	final_output.txt: a table containing statistics for each surveyed species
	one directory per species with:	
		cleaned sequences
		output_contigs_v1.txt: statistics for all loci 
		output_summarized_v2.txt: average + std for statistics over loci, and cor.test between "ENc(p)" and "expression" (GCcorrected or not)

