# sturg-snps

R markdown files (and companion files) associated with the manuscript "Haploid gynogens facilitate disomic marker development in paleotetraploid sturgeons."
Description of files:
1. HaploidGenomicReference.Rmd: R markdown for production of reduced-representation genomic reference from haploid sturgeon + identification of paralogous sequence variants in haploids.
2. DiploidSNPProcessing.Rmd: R markdown for demultiplexing diploid sturgeon reads, mapping reads to haploid reference, calling SNPs, filtering SNPs, and haplotyping SNPs.
3. SpeciesDiscrimination.Rmd: R markdown for performing DAPC and PCA on the genomic and microsatellite datasets. 
4. Spla_MiSeq_Barcodes.txt: Text file of barcodes for haploid sturgeon sequencing.
5. AS_HiSeq_Barcodes.txt: Text file of barcodes for diploid sturgeon sequencing.
6. HiSeq_1.1_IDs_Barcodes.txt, HiSeq_1.2_IDs_Barcodes.txt, HiSeq_1.3_IDs_Barcodes.txt, and HiSeq_1.4_IDs_Barcodes.txt: Text files for matching barcodes to sample IDs in diploid sturgeon. 
7. config.file: Script for trimming, mapping, and calling reads in diploid sturgeon. 
8. AS_HiSeq_Sample_Data.csv: Metadata for diploid sturgeon.
9. Spa_HiSeq1.gen: Genepop file of filtered, haplotyped SNPs in diploid sturgeon. 
10. Spa_usats.gen: Genepop file of microsatellites in diploid sturgeon. 
