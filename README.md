# Next-generation Mitochondrial Metagenomics Analysis Toolkit (NG-MMAT)

A pipeline for assembly, annotation, and phylogenomic analysis of mitochondrial sequences derived from next-generation sequencing data. The program is designed for metagenomic data but is equally useful for data from individual animals.

![alt text](https://github.com/joseph7e/NG-MMAT/blob/main/img/diagram-NGMMAT.png?raw=true)




# Mitochondrial-Sequence-Database
The program will construct a reference database of complete mitochondrial genomes and inddividual gene sequences automatically, assuming no current datbase exists (with a last update within a month).

```bash
#database location
ls ~/.mitobin/
```

  reference.faa -> amino acid translations of the protein-coding genes
  reference.fasta -> full length source sequences (typically complete mitochondrial genomes)
  reference.fna -> nucleotide sequences for all genes with annotations in source files
  reference.tsv -> metadata and descriptions of database sequences (genetic codes, gene lengths, etc.)
  simulated.fasta -> mitochondrial genomes sequences used to construct read datasets for pipeline testing.


# Mito-genome annotations

## Suported genetic codes https://www.ncbi.nlm.nih.gov/Taxonomy/Utils/wprintgc.cgi
(transl_table=2) - The Vertebrate Mitochondrial Code  
(transl_table=4) - The Mold, Protozoan, and Coelenterate Mitochondrial Code and the Mycoplasma/Spiroplasma Code (Cnidaria/Ctenophora)  
(transl_table=5) - The Invertebrate Mitochondrial Code  
(transl_table=9) - The Echinoderm and Flatworm Mitochondrial Code (Echinodermata, Platyhelminthes)  
(transl_table=13) - The Ascidian Mitochondrial Code (Tunicates)  
(transl_table=14) - The Alternative Flatworm Mitochondrial Code (Platyhelminthes)  
(transl_table=21) - Trematode Mitochondrial Code (Platyhelminthes)    
(transl_table=24) - Rhabdopleuridae Mitochondrial Code (Hemichordata)  
(transl_table=33) - Cephalodiscidae Mitochondrial UAA-Tyr Code (Hemichordata)  
  
