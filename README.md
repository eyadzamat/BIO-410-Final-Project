# BIO 410 Final Project
## Background
The data consist of 6 samples from the organism Ebola virus. This organism is a filovirus, which is an RNA virus that can cause Ebola virus disease, a severe illness in humans. Ebola virus disease can lead to symptoms such as fever, weakness, headache, vomiting, diarrhea, and in serious cases, bleeding. Ebola virus has been connected to major outbreaks in Africa [citation](Centers for Disease Control and Prevention. (2026, May 15). Ebola disease basics. U.S. Department of Health and Human Services. https://www.cdc.gov/ebola/about/index.html
## Purpose
The purpose of this project was to create a phylogenetic tree from 6 samples of Ebola virus in order to determine the evolutionary relationships between the samples.


## Methods
The data used in this project came from next-generation sequencing reads from 6 Ebola virus samples. The raw sequencing reads were first assembled into longer DNA sequences called contigs using MEGAHIT. This helped combine the short sequencing reads into larger pieces of genetic information.
After the assembly step, the contig files were brought into RStudio and analyzed using the DECIPHER package. The sequences were aligned so that similarities and differences between the 6 samples could be compared. After the alignment was completed, a phylogenetic tree was created using the maximum likelihood method in DECIPHER. This tree was used to show which samples were more closely related and which samples were more genetically different.
The assembled reads are located in the eyad.zip file, and the raw sequencing reads are located in the folder/file named eyad in the repository. The final phylogenetic tree image is saved as (EyadTree.png)



## Results

Here is the phylogenetic tree:
(Insert the image, see the markdown cheat sheet for how to do that)

![Example image of a phylogenetic tree](EyadTree.png)

Explain

The phylogenetic tree shows that **samples 4 and 5 are the most closely related** because they connect at the lowest branch point and have almost no distance between them. This means their genetic sequences are very similar.

Samples **2 and 3** are also closely related because they branch together near the bottom of the tree. Sample **1** is closely related to samples 2 and 3, and sample **6** is also part of that same larger group, but it branches off a little earlier.

Based on the phylogenetic tree, the 6 Ebola virus samples probably came from **two main individuals or groups**. One group includes **samples 1, 2, 3, and 6**, while the other group includes **samples 4 and 5**. This is because samples 4 and 5 are separated from the other samples by a much larger branch distance, showing they are more genetically different from the rest.


