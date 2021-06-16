# cnv_mapping
A software to analyze and map CNV sites using sequencing read counts in segregating populations. 

## Short Q and A
* What type of software?
The program runs using Python 3.7, Jupyter Notebook, and a set of helper programs, or packages, that can be installed using Anaconda. These programs and packages are defined in each notebook.
* What is the input?
A sequenced population derived from selfing a heterozygous individual, or from a cross. The example provided is a family of dihaploids of potato. If you do not know what these are, do not worry: think of them as a diploid F2 family (they are not, but are equivalent in genetic structure). The sequence data is organized in a table that reports standardized counts of mapped sequence reads. The counts correspond to genomic bins (intervals), which size depends on sequence coverage.  
* What is the output?
A table of loci that are in linkage disequilibrium in the genome of the population you are analyzing. Linkage disequilibrium (LD) is an unusual term. Two loci that are in LD, appear to be linked. 
* How does it work?
It compares copy number states in two loci and determines if they are independent or not. 
* Has this method been published?
A manuscript to be submitted to a peer-reviewed journal is in preparation. A poster was presented at PAG 2020 and is available for download. 
* Where can I get support?
I have tried to annotate the notebooks to provide as much information as possible. I will try to answer questions, but I am pretty busy and it may be some time before I can answer.

## Starting the analysis
This github project is not finished. 
1. Notebook utility to prepare the input table. Not ready
2. Notebook 1 to analyze input table. Available.
3. Notebook 2 to view the output of Notebook 1 as an LD matrix. Available

---
<pre>
Luca Comai
Plant Biology and Genome Center
451 Health Sciences Drive
UC Davis 
Davis, CA  95616
tel: 530-752-8485
email: lcomai@ucdavis.edu
http://comailab.org/
</pre>


    
