# Nanopore sequencing of CEN.PK113-7D: a biotech-relevant S. cerevisiae strain

Our paper is published here: http://dx.doi.org/10.1093/femsyr/fox074

And accessible through our pre-print in bioRxiv: https://www.biorxiv.org/content/early/2017/08/14/175984

All data is available under project accession number PRJNA393501: https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA393501

The nature of the raw data is as follows:
  - MinION long read data from single R9 run of CEN.PK113-7D: https://www.ncbi.nlm.nih.gov/sra/SRX3058151[accn]
  - Corresponding Illumina paired-end data from the same stock: https://www.ncbi.nlm.nih.gov/sra/SRX3058150[accn]
  
The assembly from the long reads above followed by long-read polishing using Nanopolish (https://github.com/jts/nanopolish) and short-read polishing with Pilon (https://github.com/broadinstitute/pilon) can be found under project code PCYP01: https://www.ncbi.nlm.nih.gov/Traces/wgs/?val=PCYP01&display=contigs&page=1. GFF annotations are hosted in this github respository.
  
In our study, we also discovered that a local stock of CEN.PK113-7D actually harboured a mix population of with two distinct genome architectures due to a translocation between chromosomes 3 and 8. MinION long read data for this stock can be found here: https://www.ncbi.nlm.nih.gov/sra/SRX3084768[accn]. Note that the data contains mixture of reads from ligation-based R7.3 and R9 chemistries as well as reads from the first rapid-library kit. 

To cite our paper:

Alex N. Salazar, Arthur R. Gorter de Vries, Marcel van den Broek, Melanie Wijsman, Pilar de la Torre Cortés, Anja Brickwedde, Nick Brouwers, Jean-Marc G. Daran, Thomas Abeel; Nanopore sequencing enables near-complete de novo assembly of Saccharomyces cerevisiae reference strain CEN.PK113-7D, FEMS Yeast Research, Volume 17, Issue 7, 1 November 2017, fox074, 
