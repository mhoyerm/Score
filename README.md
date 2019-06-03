# Score

Score

In the codon positions 3, 4 and 5 of a genomic sequence, the program finds the respective
GFP score for the sequence of nine nucleotides and generates an output file with the gene 
name, found sequence and GFP score according to Verma et al (2019).

Usage:
score.py <scores_table.xlsx> <genome.txt> <output_file_name.txt>

First input (required): complete file name. The input shall be a Excel file containing
two columns, first column with sequences of nine nucleotides and second column, its respectives
score values.

Second input (required): complete file name. The input shall be the genome you want
to analyze.

Output (required): file name in TXT format.
