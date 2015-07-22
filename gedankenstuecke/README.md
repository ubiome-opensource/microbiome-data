# My Microbiome Data
I underwent sequencing of the microbiome of my gut (4475), mouth (4471) and my genitals (4483) via the service of [uBiome](http://ubiome.com/), a little venture I crowdfunded a while back. They were so nice to provide me the raw sequencing results. As far as I can tell so far this isn't standard practice, but it seems to work if you contact their support and ask nicely for it. 

## How was the sequencing done? 
According to their FAQ it is done using some _Illumina_ Next-Generation Sequencing method that amplifies the 16S rRNA. The 16S rRNA is one of the standard loci you want to look at for identifying species as [it's highly conserved between Bacteria & Archaea and thus is an ideal sequencing target](http://en.wikipedia.org/wiki/16S_ribosomal_RNA). _Illumina_ has [a couple of ways to generate this data](http://www.illumina.com/applications/microbiology/microbial-sequencing-methods/16S-rrna-sequencing.ilmn), by now I don't know which DNA extraction & Library Preparation methods they've used.

## When were the samples taken?
All samples where taken at around ~11am on January 6th of 2014 and in accordance with the sampling recommendations of _uBiome_. This basically means no brushing teeth, no kissing, no alcohol, no sexual activities for about 24h or so prior to sampling.  

The sequencing itself was done on June 1st of 2014. 

## Sample IDs 
* SSR_4475 - gut
* SSR_4471 - mouth
* SSR_4483 - genitals

## Data
For each sample are two FASTQ files, containing the forward/reverse reads of the sequencing run. Additionally the *count.json files contain the bacteria counts as provided by _uBiome_ 

## Licensing? 
I highly doubt that I could make any claims on owning this data (at least this is how it should be). But still: Use it as [Creative Commons Zero](https://creativecommons.org/publicdomain/zero/1.0/), which is somewhat equivalent of putting it into the public domain. 