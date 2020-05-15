# rDNA_reference

The repository contains FASTA sequence and curated BED annotation files for
complete ribosomal DNA units in human (and soon to be added: mouse).

1. FASTA sequences are taken from GenBank

2. BED annotation files were derived from the list of GenBank sequence features
and manually curated.


## Changes/additions to the GenBank annotation

1. Where possible, the annotation was extended to include the CORE promoters
and upstream control elements (UCE). CORE promoters and UCEs are located
upstream of the 5'ETS transcription start site.

    - In human, the CORE promoter is located between -45 and +18, the UCE is located
    between -156 and -107.
    - In mouse, the CORE promoter is located between -39 and +9, the UCE is located
    between -150 and ???.

2. Pseudo-genes were removed

3. Low complexity repeat regions were removed; these include

	- mono-, di-, tri-, tetra-, penta-, hexanucleotide repeat regions
	- N-rich and NN-rich repeat regions (e.g. T-rich, GC-rich, AT-rich etc.)
	- low complexity compound repeat regions

4. Where possible, repeat regions were labelled according to their respective
repeat family (i.e. LINE, SINE, ...)

Note that the CORE promoter is also sometimes referred to as the core promoter
element (CPE), and the UCE is sometimes referred to as the upstream promoter
element (UPE).


## References:

**BK000964.3**

- [GenBank BK000964.3 reference](https://www.ncbi.nlm.nih.gov/nuccore/BK000964)
- [Grozdanov, Complete sequence of the 45-kb mouse ribosomal DNA repeat: analysis of the intergenic spacer, Genomics 82, 637 (2003)](https://www.ncbi.nlm.nih.gov/pubmed/14611805)


**KY962518.1**

- [GenBank KY962518.1 reference](https://www.ncbi.nlm.nih.gov/nuccore/KY962518.1)
- [Kim et al., Variation in human chromosome 21 ribosomal RNA genes characterized by TAR cloning and long-read sequencing, NAR 27, 6712 (2018)](https://www.ncbi.nlm.nih.gov/pubmed/29788454)


**U13369.1**

- [GenBank U13369.1 reference](https://www.ncbi.nlm.nih.gov/nuccore/U13369.1)


**Further references**

- [Learned et al., Human rRNA Transcription Is Modulated bythe Coordinate Binding of Two Factors to an Upstream Control Element, Cell 45, 847 (1986)](https://www.ncbi.nlm.nih.gov/pubmed/3708692)
- [Goodfellow and Zomerdijk, Basic Mechanisms in RNA Polymerase I Transcription of the Ribosomal RNA Genes, Subcell Biochem. 61,  10.1007/978-94-007-4525-4_10 (2012)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3855190/)
