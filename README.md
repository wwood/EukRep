# EukRep #
Classification of Eukaryotic and Prokaryotic sequences from metagenomic datasets
# Installation #
* Requires Python3
* Easy install with pip
```
$ pip install EukRep
```
# Example Usage #
* Identify and output sequences predicted to be of eukaryotic origin from a fasta file:
```
$ EukRep -i <Sequences in Fasta format> -o <Eukaryote sequence output file>
```
* Identify and output both sequences of eukaryotic and prokaryotic origin from a fasta file:
```
$ EukRep -i <Sequences in Fasta format> -o <Eukaryote sequence output file> --prokarya <Prokaryote sequence output file>
```

To obtain high quality gene predictions for and bin identified eukaryotic contigs as described in "Genome-reconstruction for eukaryotes from complex natural microbial communities" (West et al. in review), see methods section https://doi.org/10.1101/171355

