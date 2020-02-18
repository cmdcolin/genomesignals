# genomesignals

This README is motivated by the idea that the way scientists see the genome is much different from just the letters ACGT, there are many ways of decoding the data


## NGS

- RNA-seq - gene expression, transcript expression, isoform detection, gene fusion detection
- Hi-C chromatin conformation
- WGS alignment sequence depth, indicating CNV/DUP/DEL
- ChIP-seq peaks, the sequencing depth enriched for transcription factor or histone binding to the DNA
- Methylation

## Sequence

- GC content, important for gene body, or sequencing bias
- GC skew, important for replication oriding
- Genes/kbp, or variants/kbp or other measures of feature density


## Population genomics or evolution

- Topology weight, a signal showing the match to a particular evolutionary tree topology across the genome https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-1938-2/figures/6
- Conservation score e.g. phastCons, phyloP, from multiway alignments
- Tajimas D https://www.g3journal.org/content/6/9/2867 https://en.wikipedia.org/wiki/Tajima%27s_D
- Genome-wide nucleotide diversity https://www.g3journal.org/content/6/9/2867
- Fixation index, for comparing two populations https://en.wikipedia.org/wiki/Fixation_index
- Haplotype homogeneity or selective sweep https://messerlab.org/resources/
- Variant age e.g. https://human.genome.dating
- Fitcons http://compgen.cshl.edu/fitCons/


## Traits

- Genome wide association test e.g. Manhattan plot
- Recombination rate
- Linkage disequilibrium (LD)
