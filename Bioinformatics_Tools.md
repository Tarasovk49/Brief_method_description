# BIOINFORMATICS TOOLS OF ANY KIND FOR PHYLOGENY ANALYSIS, MULTIPLE SEQUENCE ALIGNMENTS, FILE CONVERTION, ETC.

| Tool Name | Language | Input | Output | Actions | Comments |
|:---|:---:|:---:|:---:|:---:|:---:|
| ape | R | - | 7 | 8 | 9 |
| phylogram | R | - | 7 | Operation with trees as dendrogram objects instead of phylo objects | 9 |
| phangorn | R | - | 7 | 8 | 9 |
| phylotools | R | Fasta or PHYLIP msa | RAxML supermatrix | -1.2 | -1.7 |
| ggtree | R | - | 7 | Annotating trees with data | [Manual](https://guangchuangyu.github.io/ggtree-book/chapter-ggtree.html) |
| treeio | R | almost any formats of phylogenetic trees and outputs of common services | Tree object for future work with ggtree | parsing trees | BEAST, RAxML, HyPhy, PAML, pplacer, RevBayes, FPA, PHYLODOG, phyloT, r8s, ... |
| MrBayes | standalone, available in R | NEXUS alignment | 7 | Bayesian Inference for Phylogeny, MCMC methods | 9 |
| msa | R | - | 7 | ClustalW, ClustalOmega, and MUSCLE MSA tool entirely in R, LATEX rendering | Beautiful DRAWINGS of MSA |
| GraPhlAn | Python | - | - | Circular Tree Builder | phylophlan uses it |
| phytools | R | - | 7 | 8 | 9 |
| phyML | R | PHYLYP, NEXUS msa | Newick?? | 8 | Doesn't work for >4000 sequences, Various models of substitution  |
| phylophlan | Python, Perl | Fasta's + Reference Database (need to be prepared) | msa, phylogeny | FastTree builds approximate maximum likelihood tree, then RAxML builds maximum likelihood tree based on it | Python interface!!! |
