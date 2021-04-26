## Background
The Internal Transcribed Spacer (ITS) is the spacer DNA situated between the small-subunit ribosomal RNA (rRNA) and 
large-subunit rRNA genes in the chromosome or the corresponding transcribed region in the polycistronic rRNA precursor transcript.
In bacteria and archaea, there is a single ITS, located between the 16S and 23S rRNA genes. Conversely, there are two ITSs in eukaryotes: 
  - ITS1 is located between 18S and 5.8S rRNA genes, while 
  - ITS2 is between 5.8S and 28S (in opisthokonts, or 25S in plants) rRNA genes. 
 
ITS1 corresponds to the ITS in bacteria and archaea, while ITS2 originated as an insertion that interrupted the ancestral 23S rRNA gene.

ITS has been used in metabarcoding experiments to allow simultaneous identification of many taxa within a sample. Since this metabarcoding doesnot focus 
on a single organism, it aims to determine the species composition within a sample.

## Project description
Stingless Bees and Apis melifera pollen Metabarcoding data generated using ITS are available. The samples were collected from Madagascar, etc...
The initial study sought to understand how pollen Metabarcoding can determine what they forage and if the stingless bees can pollinate 
the same plants as Apis. Since the pollen Metabarcoding used ITS markers, they also amplify the fungi, which is of interest in this study. 
There are beneficial fungi for the bee larva and others that cause diseases. 

## Project Questions
The objective of this project is to create a pipeline to filter out the fungi data and then answer the following questions:
  - What kind of fungi is in the feed?
  - Identify the beneficial and the harmful fungi species
  - How does the abundance of the fungi differ between species? 
  - Is there an observed location-specific difference in fungi species?

## Pipeline development
The pipeline major steps include;
  1. Quality check and control
  2. Filtering, trimming and clustering reads
  3. Chimera detection
  4. Biodiversity classification and Taxonomic assignment

## Project tasks

1. Create a road map for your mini project
2. Create an analysis pipeline for ITS data from the Illumina sequencing platform
3. The pipeline can utilize many tools but the primary tool should be **Qiime2**
4. Compare the different tools that can be utilized at each step and write a short critique summary on performance, pros, and cons
5. Document your scripts and work on GitHub ensuring it is reproducible
    
Throughout the project, demonstrate project organization, documentation, collaborative working, and report writing.




