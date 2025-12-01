# 2025Dec01 Concepts in Parasitology Genomics II materials

To access the slides that accompanies this workshop: [click here!](https://kirstymccann.github.io/ggplotly_workshop_website/)

## Contents
- `metadata_samples.txt` - this file contains the name of the dataset samples and information recording the collection site, country and if there are any drug resistant mutations present.
- `SEA_180snp_DR.vcf` - Southeast Asia dataset
- `AFR_180snp.vcf` - African datatset

## DISCLAIMER

The following tutorial is simulated for workshops purposes.

This workshop should only be used for training purposes.

## The Scenario

In early 2025, an unexpected cluster of approximately 200 Plasmodium falciparum malaria cases was reported in a district of Namibia, Africa that had previously achieved malaria-free status in 2019. This district is a popular tourism destination, attracting visitors from across the world, making imported infections a key concern for surveillance teams.

Although local transmission in Namibia had been largely interrupted, bordering countries particularly Angola continue to experience substantial malaria transmission, including recent surges in case numbers. Because of the region’s interconnected human movement and historical importation events, rapid genomic investigation was initiated to determine whether this new outbreak represented:

- A resurgence of local parasite circulation,

- Ongoing regional transmission from neighbouring endemic countries, or

- An imported outbreak from outside Africa.

To investigate, all cases were genotyped using a global **180-SNP barcode**, providing a compact yet highly informative set of markers for population structure, relatedness, and transmission inference.

## How to use this workshop?

**1. Clone this repository**
- Open Terminal (Mac/Linux) or PowerShell (Windows), then run:
- git clone https://github.com/KirstyMcCann/2025Dec01_Concepts_in_Parasitology_GenomicsII_materials.git
- Then move into the project folder:
- cd 2025Dec01_Concepts_in_Parasitology_GenomicsII_materials

OR

**Option 2 — download as ZIP**

- Go to the GitHub repository page
- Click Code (green button)
- Click Download ZIP
- Extract the ZIP file locally


**2. Install Required Software**
- You will need at least:
- R (≥4.2)
- Download from: https://cran.r-project.org/

**3. Install Required R Packages**

Start RStudio
Then run the following in the Console:

required <- c(
  "vcfR", "adegenet", "poppr", "ape", "pegas", "ggplot2",
  "dplyr", "reshape2", "ggtree", "viridis", "dartR.base",
  "hierfstat", "tidyr", "sf", "rnaturalearth",
  "rnaturalearthdata", "scales", "purrr"
)

install.packages(required)

**4. Place the Data Files**

Required input files are availble in:

/data/


Specifically:

- metadata_samples.txt
- SEA_180snp_DR.vcf
- AFR_180snp_DR.vcf

(You can find them in the workshop repo or download from Workshop Drive)

**You can then work through the Rmarkdown script during the workshop while we go through it**

The workshop can be repeated and the slides presented during the workshop will be provided following the workshop and found here.

## **Credits**

Developed and maintained by Dr Kirsty McCann for teaching 2025 Concepts in Parasitology Course - Genomics II in R.

