# BIOINFORMATICS TOOLS FOR ALL OCCASIONS: PHYLOGENY ANALYSIS, MULTIPLE SEQUENCE ALIGNMENTS, FILE CONVERTION, VISUALIZATION, ETC.


## First of all check this [REVIEW!!!!!!!!](https://cran.r-project.org/web/views/Phylogenetics.html)


| Tool Name | Language/Interface | Input | Output | Brief Description | Comments |
|:---|:---:|:---:|:---:|:---:|:---:|
| ape | R | Tree | Picture | Drawer and analyzer of phylogenetic trees, Basic tool, other use it, *phylo* objects | [MANUAL](https://cran.r-project.org/web/packages/ape/vignettes/DrawingPhylogenies.pdf) |
| ClustalOmega | command-line | Fasta files | msa | UPGMA with HMM | Fast MSA tool for huge number of sequences and/or large sequences |
| Dendroscope | GUI | Newick | Picture | Visualization of trees with GUI | [Manual in main directory after installation](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/algorithms-in-bioinformatics/software/dendroscope/) |
| ETE toolkit | Python | Newick, NEXUS | Picture | Tree manipulation, analysis and drawing | Python interface!!!! and excellent [MANUAL](http://etetoolkit.org/docs/latest/_downloads/ETE.pdf) |
| FastTree | command-line | Fasta or interleaved Phylip sma | Newick | Approximately Maximum Likelihood Tree | [Web Page](http://www.microbesonline.org/fasttree/#Usage) |
| ggtree | R | Any trees parsed with treeio | Picture | Annotating trees with data | [MANUAL](https://guangchuangyu.github.io/ggtree-book/chapter-ggtree.html) |
| GraPhlAn | Python | - | - | Circular Tree Builder | **phylophlan** uses it |
| GTDB-Tk | command-line | Fasta | Fasta msa and Newick Tree | MSA + building Tree with **pplacer** to reference database GTDB | [GIT](https://github.com/cerebis/GtdbTk), [EXAMPLE](https://ecogenomics.github.io/GTDBTk/examples/classify_wf.html) |
| iTOL | online | Newick, Nexus, PhyloXML or Jplace Tree | Picture | Visualization Tool | - |
| MrBayes | command-line, available as R package | NEXUS alignment | 7 | Bayesian Inference for Phylogeny, MCMC methods, Bootstrapping | [HOME PAGE](http://nbisweden.github.io/MrBayes/) |
| msa | R | - | - | **ClustalW**, **ClustalOmega**, and **MUSCLE** MSA tool entirely in R, LATEX rendering | Beautiful DRAWINGS of MSA |
| pplacer | command-line | Fasta files | Maps of sequences to Reference Database | Pplacer places query sequences on a fixed reference phylogenetic tree to maximize phylogenetic likelihood or posterior probability according to a reference alignment | [Tutorial](http://fhcrc.github.io/microbiome-demo/) |
| phylogram | R | - | - | Convertion of trees to *dendrogram* objects from *phylo* objects | [MANUAL](https://cran.r-project.org/web/packages/phylogram/vignettes/phylogram-vignette.html) |
| phangorn | R | - | - | - | - |
| CheckM | R | - | - | - | - |
| MitoBench | Java | - | - | MitoBench is a tool aimed at helping researchers to organize, visualize and maintain their mitochondrial datasets | - |
| AMBER | R | - | - | - | - |
| HMMER | R | - | - | - | - |
| prodigal | R | - | - | - | - |
| phylotools | R | Fasta or PHYLIP msa | **RAxML** supermatrix | - | - |
| phytools | R | - | - | - | [TUTORIAL](http://www.phytools.org/Cordoba2017/ex/15/Plotting-methods.html) |
| phyML | R | PHYLYP, NEXUS msa | Newick?? | Maximum Likelihood | Doesn't work for >4000 sequences, Various models of substitution |
| phylophlan | Python | Fasta's + Reference Database (need to be prepared) | msa, phylogeny | **FastTree** is used to build approximate maximum likelihood tree, then **RAxML** is used to build maximum likelihood tree based on it | Python interface!!! |
| phylo-cgi converter | online | - | - | Fasta msa to Phylip msa | [Web Page](http://phylogeny.lirmm.fr/phylo_cgi/data_converter.cgi) |
| RAxML | command-line | Phylip (relaxed) or Fasta msa, Newick for trees | Trees with bootstrap values, Starting Tree, Final tree | Sequential and parallel Maximum Likelihood based inference of large phylogenetic trees | [Step-by-step Tutorial](https://cme.h-its.org/exelixis/web/software/raxml/hands_on.html), [Manual](https://cme.h-its.org/exelixis/resource/download/NewManual.pdf)|
| treeio | R | almost any formats of phylogenetic trees and outputs of common services | Tree object to process with **ggtree** | parsing trees | Services whose output can be parsed: BEAST, RAxML, HyPhy, PAML, pplacer, RevBayes, FPA, PHYLODOG, phyloT, r8s, ...[MANUAL](https://guangchuangyu.github.io/ggtree-book/chapter-treeio.html) |
