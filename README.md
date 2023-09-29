# FilterChromosomes
# Language: Python
# Input: TXT
# Output: FASTA
# Tested with: PluMA 1.1, Python 3.6

PluMA plugin to filter chromosomes from FASTA input

The plugin takes as input a tab-delimited file of keyword-value pairs:
inputfile: FASTA file
filterfile: TXT file of assembly taxonomy table
dbversion: Ensembl version

Chromosomes will be sent to output FASTA
