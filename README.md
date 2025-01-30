# Genome assembly and annotation of the white perch (_Morone americana_)

This GitHub repository contains additional information and the genome annotation related to the article:

### Two genomes of the white perch (_Morone americana_), an ecologically important teleost

#### Authors
Josephine R. Paris 1, Megan Criss 2, Jessica Walsh 2, Joan Ferrer Obiol 3, Christopher S Murray 4, Jason Boone 2, Ann M Petersen 5

#### Author Affiliations
1.	Department of Life and Environmental Sciences, Marche Polytechnic University, Ancona, Italy
2.	Floragenex, Inc., Beaverton, Oregon, USA
3.	Department of Biology, Colorado State University, Fort Collins, CO, USA
4.	Biology Department, Woods Hole Oceanographic Institution, Woods Hole, MA 02543, USA
5.	National Oceanographic and Atmospheric Administration, National Marine Fisheries, Northeast Fisheries Science Center, JJ Howard Marine Laboratory, Sandy Hook, New Jersey, USA

#### Corresponding Author: Josephine Paris (parisjosephine@@@@gmail.com)

-----------------
### Access to the data from the article:

* The genome assemblies for the male and female white perch are available on the ENA under the Project Study Accession: PRJEB63122
* The female white perch (_Morone americana_) assembly can be found under the genome accession number GCA_965119275.
* The male white perch (_Morone americana_) assembly can be found under the genome accession number GCA_965119265.
* The female mitochondrial sequence is available on NCBI GenBank under the accession number XXX. This is contig M_amer_fem_259 in the accessioned assembly on ENA.

NB: The ENA upload of the genomes also includes the raw PacBio HiFi data

--------------------------------
### Access to the genome annotations:

Annotation was performed on the female genome using BRAKER3 (https://github.com/Gaius-Augustus/BRAKER), using RNAseq data from ovary and larval tissues and the OrthoDb Vertebrata partition of protein sequences.
This annotation can be found in the folder `female-braker3-annotation`, which includes the following (compressed) files:

* Gff3 file
* Protein fasta file
* Longest isoform per protein fasta file
* CDS fasta file
* Functional annotation: Eggnog2 emapper tsv file
* Functional annotation: InterProScan tsv file 
