# BIO 410 Final Project
## Background
The data consist of 6 samples from the organism Ebola virus. This organism is a filovirus that can cause Ebola disease, a serious and often deadly illness in humans. According to the Centers for Disease Control and Prevention, Ebola disease is caused by infection with orthoebolaviruses, which are found mainly in sub-Saharan Africa and can cause severe disease (Centers for Disease Control and Prevention, 2026).
 (Centers for Disease Control and Prevention. (2026, May 15). Ebola disease basics. U.S. Department of Health and Human Services. https://www.cdc.gov/ebola/about/index.html
## Purpose
The purpose of this project was to create a phylogenetic tree from 6 samples of Ebola virus in order to determine the evolutionary relationships between the samples.


## Methods
The data used in this project came from next-generation sequencing reads from 6 Ebola virus samples. Next-generation sequencing produces many short pieces of genetic information called reads. These reads were used to compare the genetic similarities and differences between the Ebola virus samples.
The raw sequencing reads were first assembled into longer sequences called contigs using MEGAHIT. MEGAHIT is a program that takes short sequencing reads and combines overlapping reads into longer assembled sequences. This step was important because longer sequences make it easier to compare the samples.
After the assembly step, the contig files were brought into RStudio and analyzed using the DECIPHER package. The sequences were aligned so that similar regions lined up with each other. This made it possible to compare differences between the 6 samples more accurately.
After the alignment was completed, a phylogenetic tree was created using the maximum likelihood method in DECIPHER. This method estimates the tree that best represents the evolutionary relationships between the samples. The final tree was then used to identify which Ebola virus samples were most closely related and which samples were more genetically different.

The assembled reads are located in (eyad Final Project.htm)
 and the raw sequencing reads are located in [eyad.zip](https://github.com/user-attachments/files/27943304/eyad.zip). The final phylogenetic tree image is saved as (EyadTree.png)



## Results

Here is the phylogenetic tree:

![Example image of a phylogenetic tree](EyadTree.png)

Explain

The phylogenetic tree shows that **samples 4 and 5 are the most closely related** because they connect at the lowest branch point and have almost no distance between them. This means their genetic sequences are very similar.

Samples **2 and 3** are also closely related because they branch together near the bottom of the tree. Sample **1** is closely related to samples 2 and 3, and sample **6** is also part of that same larger group, but it branches off a little earlier.

Based on the phylogenetic tree, the 6 Ebola virus samples probably came from **two main individuals or groups**. One group includes **samples 1, 2, 3, and 6**, while the other group includes **samples 4 and 5**. This is because samples 4 and 5 are separated from the other samples by a much larger branch distance, showing they are more genetically different from the rest.


