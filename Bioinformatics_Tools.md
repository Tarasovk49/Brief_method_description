# BIOINFORMATICS TOOLS OF ANY KIND FOR PHYLOGENY ANALYSIS, MULTIPLE SEQUENCE ALIGNMENTS, FILE CONVERTION, VISUALIZATION, ETC.


## First of all check this [REVIEW!!!!!!!!](https://cran.r-project.org/web/views/Phylogenetics.html)


| Tool Name | Language | Input | Output | What does it do? | Comments |
|:---|:---:|:---:|:---:|:---:|:---:|
| ape | R | Tree | Picture | Drawer of phylogenetic trees, Basic tool, other use it, *phylo* objects | [MANUAL](https://cran.r-project.org/web/packages/ape/vignettes/DrawingPhylogenies.pdf) |
| ClustalOmega |  | - | 7 | 8 | 9 |
| ClustalW |  | - | 7 | 8 | 9 |
| Dendroscope | standalone | Newick | Picture | Visualization of trees with GUI | [Manual in main directory after installation](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/algorithms-in-bioinformatics/software/dendroscope/) |
| ETE toolkit | Python | Newick, NEXUS | Picture | Tree manipulation, analysis and drawing | Python interface!!!! and excellent [MANUAL](http://etetoolkit.org/docs/latest/_downloads/ETE.pdf) |
| FastTree | R | - | 7 | 8 | 9 |
| ggtree | R | - | 7 | Annotating trees with data | [MANUAL](https://guangchuangyu.github.io/ggtree-book/chapter-ggtree.html) |
| GraPhlAn | Python | - | - | Circular Tree Builder | phylophlan uses it |
| GTDB-Tk |  | - | 7 | 8 | 9 |
| MrBayes | standalone, available as R package | NEXUS alignment | 7 | Bayesian Inference for Phylogeny, MCMC methods, Bootstrapping | [HOME PAGE](http://nbisweden.github.io/MrBayes/) |
| msa | R | - | 7 | ClustalW, ClustalOmega, and MUSCLE MSA tool entirely in R, LATEX rendering | Beautiful DRAWINGS of MSA |
| pplacer |  | - | 7 | 8 | 9 |
| phylogram | R | - | 7 | Convertion of trees to *dendrogram* objects from *phylo* objects | [MANUAL](https://cran.r-project.org/web/packages/phylogram/vignettes/phylogram-vignette.html) |
| phangorn | R | - | 7 | 8 | 9 |
| phylotools | R | Fasta or PHYLIP msa | RAxML supermatrix | -1.2 | -1.7 |
| phytools | R | - | 7 | 8 | [TUTORIAL](http://www.phytools.org/Cordoba2017/ex/15/Plotting-methods.html) |
| phyML | R | PHYLYP, NEXUS msa | Newick?? | 8 | Doesn't work for >4000 sequences, Various models of substitution  |
| phylophlan | Python, Perl | Fasta's + Reference Database (need to be prepared) | msa, phylogeny | FastTree builds approximate maximum likelihood tree, then RAxML builds maximum likelihood tree based on it | Python interface!!! |
| phylo-cgi converter | online | - | - | Fasta msa to Phylip msa | [Web Page](http://phylogeny.lirmm.fr/phylo_cgi/data_converter.cgi) |
| RAxML | standalone | Phylip (relaxed) or Fasta msa, Newick for trees | Trees with bootstrap values, Starting Tree, Final tree | Sequential and parallel Maximum Likelihood based inference of large phylogenetic trees | [Step-by-step Tutorial](https://cme.h-its.org/exelixis/web/software/raxml/hands_on.html), [Manual](https://cme.h-its.org/exelixis/resource/download/NewManual.pdf)|
| treeio | R | almost any formats of phylogenetic trees and outputs of common services | Tree object for future work with ggtree | parsing trees | BEAST, RAxML, HyPhy, PAML, pplacer, RevBayes, FPA, PHYLODOG, phyloT, r8s, ...[MANUAL](https://guangchuangyu.github.io/ggtree-book/chapter-treeio.html) |
