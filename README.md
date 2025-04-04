# genomesignals

This README is motivated by the idea that the way scientists see the genome is much different from just the letters ACGT, there are many ways of seeing the "signals" in these letters


## NGS

- RNA-seq - gene expression, transcript expression, isoform detection, gene fusion detection
- Hi-C chromatin conformation
- WGS alignment sequence depth, indicating CNV/DUP/DEL. Can also indicate SNP, indel, etc. Paired end sequencing, long read sequencing, 
- ChIP-seq peaks, the sequencing depth enriched for transcription factor or histone binding to the DNA (can reveal sequence motifs in the peaks)
- Methylation
- ATAC-seq accessible chromatin and DNA footprinting
- Nucleosome occupancy

## Markers

- Cut sites (restriction enzyme recognition sites) https://en.wikipedia.org/wiki/Restriction_enzyme#Recognition_site
- Microsatellite https://en.wikipedia.org/wiki/Microsatellite

## Mutational process (CNV, others)

- Loss of heterozygosity https://en.wikipedia.org/wiki/Loss_of_heterozygosity
- B-allele frequency
- Sequence clipping
- Sequence depth

## Sequence

- GC content, important for gene body, or sequencing bias
- GC skew, important for replication origin
- Genes/kbp, or variants/kbp or other measures of feature density


## Population genomics or evolution

- Topology weight, a signal showing the match to a particular evolutionary tree topology across the genome https://genomebiology.biomedcentral.com/articles/10.1186/s13059-020-1938-2/figures/6
- Conservation score e.g. phastCons, phyloP, from multiway alignments
- Tajimas D https://www.g3journal.org/content/6/9/2867 https://en.wikipedia.org/wiki/Tajima%27s_D
- Genome-wide nucleotide diversity https://www.g3journal.org/content/6/9/2867 https://en.wikipedia.org/wiki/Nucleotide_diversity
- Fixation index, for comparing two populations https://en.wikipedia.org/wiki/Fixation_index
- Haplotype homogeneity or selective sweep https://messerlab.org/resources/
- Variant age e.g. https://human.genome.dating
- Fitcons http://compgen.cshl.edu/fitCons/


## K-mer

- Mappability e.g. https://genome.ucsc.edu/cgi-bin/hgFileUi?db=hg19&g=wgEncodeMapability
- Ploidy detection and assembly characteristics via k-mer e.g. GenomeScope https://github.com/schatzlab/genomescope

## Traits

- Genome wide association test e.g. Manhattan plot
- Recombination rate
- Linkage disequilibrium (LD)

## Genome assembly characteristics

- N50 https://en.wikipedia.org/wiki/N50,_L50,_and_related_statistics
- BUSCO score
- Genome size
