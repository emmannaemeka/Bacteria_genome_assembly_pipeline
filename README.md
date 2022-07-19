# Bacteria_genome_assembly_pipeline
Like you I have been struggling with how to assemble my genome. One major problem is having to run each step over and over for each sequence. So I decided to create a script that can take your sequence, create a new directory, check the quality of your reads, trim adapters and assemble using metaSpades.  After which you it then uses another tool viralVerify which  classifies contigs (output of metaviralSPAdes or other assemblers) as viral, non-viral or uncertain, based on gene content. Also for non-viral contigs it can optionally provide plasmid/non-plasmid classification.


Let me know if it helps your work.  if you notice any bug, please write me. 



