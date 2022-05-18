# sturg-snps

R markdown files and companion files associated with the manuscript "Haploid gynogens facilitate disomic marker development in paleotetraploid sturgeons."

Description of R markdown files:
1. HaploidGenomicReference.Rmd: R markdown for production of reduced-representation genomic reference from haploid sturgeon + identification of paralogous sequence variants in haploids.
2. DiploidSNPProcessing.Rmd: R markdown for demultiplexing diploid sturgeon reads, mapping reads to haploid reference, calling SNPs, filtering SNPs, and haplotyping SNPs.
3. SpeciesDiscrimination.Rmd: R markdown for performing DAPC and PCA on the genomic and microsatellite datasets. 

Description of companion files for haploid sturgeon sequence data analyses (files needed for HaploidGenomicReference.Rmd):
1. Spla_MiSeq_Barcodes.txt: Text file of barcodes for haploid sturgeon sequencing.
2. Spla_MiSeq_IDs_Barcodes.txt: Text file for matching barcodes to sample IDs in haploid sturgeon. 
3. trim_config.file: Script for trimming reads in haploid sturgeon. 
4. ReferenceOpt.sh: Script for optimizing reference to choose c value.
5. RefMapOpt.sh: Script for optimizing reference to choose K1 and K2. 
6. assembly_config.file: Script for building the haploid reference.
7. map.file: Script for mapping haploid reads onto the reference. 
8. flagstats.sh and idxstats.sh: Scripts for statistics related to mapping the haploid reads onto the reference. 
9. snpcall.file: Script for calling SNPs in haploid sturgeon.
10. MiSeq_Sample_Data.csv: Metadata for haploid sturgeon.
11. psv.txt: Text file of paralogous contigs identified in haploid dataset. 

Description of companion files for diploid sturgeon sequence data analyses (files needed for DiploidSNPProcessing.Rmd and SpeciesDiscrimination.Rmd:
1. AS_HiSeq_Barcodes.txt: Text file of barcodes for diploid sturgeon sequencing.
2. HiSeq_1.1_IDs_Barcodes.txt, HiSeq_1.2_IDs_Barcodes.txt, HiSeq_1.3_IDs_Barcodes.txt, and HiSeq_1.4_IDs_Barcodes.txt: Text files for matching barcodes to sample IDs in diploid sturgeon. 
3. config.file: Script for trimming, mapping, and calling reads in diploid sturgeon. 
4. AS_HiSeq_Sample_Data.csv: Metadata for diploid sturgeon.
5. Spa_HiSeq1.gen: Genepop file of filtered, haplotyped SNPs in diploid sturgeon. 
6. Spa_usats.gen: Genepop file of microsatellites in diploid sturgeon. 
