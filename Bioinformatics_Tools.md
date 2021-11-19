# BIOINFORMATICS TOOLS FOR ALL OCCASIONS: PHYLOGENY ANALYSIS, MULTIPLE SEQUENCE ALIGNMENTS, FILE CONVERTION, VISUALIZATION, ETC.


## First of all check this [REVIEW!!!!!!!!](https://cran.r-project.org/web/views/Phylogenetics.html) and this [COLLECTION](https://molbiol-tools.ca/Phylogeny.htm)


| Tool Name | Interface | Input | Output | Brief Description | Comments |
|:---|:---:|:---:|:---:|:---:|:---:|
| ape | R | Tree | Picture | Drawer and analyzer of phylogenetic trees, Basic tool, other use it, *phylo* objects | [MANUAL](https://cran.r-project.org/web/packages/ape/vignettes/DrawingPhylogenies.pdf) |
| ARB | GUI | - | - | The ARB software is a graphically oriented package comprising various tools for sequence database handling and data analysis. rRNA-based tool, compatible with **SILVA** | [Web-Site](http://www.arb-home.de/features.html) |
| CIPRES | online, REST API | - | - | GRID resources for Phyloigeny Inference | [CIPRES Science Gateway](https://www.phylo.org/portal2/tools.action) |
| ClustalOmega | command-line | Fasta files | msa | UPGMA with HMM | Fast MSA tool for huge number of sequences and/or large sequences |
| CheckM | command-line | Directory with genome bins in Fasta | different quality plots | CheckM provides a set of tools for assessing the quality of genomes recovered from isolates, single cells, or metagenomes. It provides robust estimates of genome completeness and contamination by using collocated sets of genes that are ubiquitous and single-copy within a phylogenetic lineage. | Available through [KBase](https://www.kbase.us/), **HMMER**, **prodigal**, **pplacer** - dependent, [All information lurks here: GitHub wiki](https://github.com/Ecogenomics/CheckM/wiki) |
| Dendroscope | GUI | Newick | Picture | Visualization of trees with GUI | [Manual in main directory after installation](https://uni-tuebingen.de/fakultaeten/mathematisch-naturwissenschaftliche-fakultaet/fachbereiche/informatik/lehrstuehle/algorithms-in-bioinformatics/software/dendroscope/) |
| ETE toolkit | Python | Newick, NEXUS | Picture | Tree manipulation, analysis and drawing | Python interface!!!! and excellent [MANUAL](http://etetoolkit.org/docs/latest/_downloads/ETE.pdf) |
| FastANI | command-line | Fastas Set | ANI's | Compute Average Nucleotide Identity of sequences | [Git-Hub](https://github.com/ParBLiSS/FastANI) |
| FastTree | command-line | Fasta or interleaved Phylip sma | Newick | Approximately Maximum Likelihood Tree | [Web Page](http://www.microbesonline.org/fasttree/#Usage) |
| FigTree | GUI(Java) | - | - | FigTree is designed as a graphical viewer of phylogenetic trees and as a program for producing publication-ready figures. As with most of my programs, it was written for my own needs so may not be as polished and feature-complete as a commercial program. In particular it is designed to display summarized and annotated trees produced by **BEAST** | [Web-Site](http://tree.bio.ed.ac.uk/software/figtree/) |
| ggKbase| online | - | - | Online Tool for different phylogeny, quality of bins assession analyses | [Web-Site](https://ggkbase.berkeley.edu/) |
| ggtree | R | Any trees parsed with treeio | Picture | Annotating trees with data | [MANUAL](https://guangchuangyu.github.io/ggtree-book/chapter-ggtree.html) |
| GraPhlAn | Python | - | - | Circular Tree Builder | **phylophlan** uses it |
| GTDB-Tk | command-line | Fasta | Fasta msa and Newick Tree | MSA + building Tree with **pplacer** to reference database GTDB | [GIT](https://github.com/cerebis/GtdbTk), [EXAMPLE](https://ecogenomics.github.io/GTDBTk/examples/classify_wf.html) |
| IQ-Tree | command-line, online | Fasta, NEXUS, Clustal, Phylip msa | Newick | Maximum likelihood phylogeny inference, assessing bootstrap supports, can be paralleled | Exellent [Tutorial+Manual](http://www.iqtree.org/doc/iqtree-doc.pdf) |
| iTOL | online | Newick, Nexus, PhyloXML or Jplace Tree | Picture | Visualization Tool | - |
| MAFFT | command-line, online | Fasta | Fasta, Clustal msa | Multiple Sequence Alignment Tool | [Web-Site](https://mafft.cbrc.jp/alignment/software/) |
| Mesquite | GUI | - | - | Mesquite is modular, extendible software for evolutionary biology, designed to help biologists organize and analyze comparative data about organisms. Its emphasis is on phylogenetic analysis, but some of its modules concern population genetics, while others do non-phylogenetic multivariate analysis. | [Web-Site](http://www.mesquiteproject.org/) |
| MitoBench | Java | - | - | MitoBench is a tool aimed at helping researchers to organize, visualize and maintain their mitochondrial datasets | - |
| MrBayes | command-line, available as R package | NEXUS alignment | Cladograms and a huge pile of statistics | Bayesian Inference for Phylogeny, MCMC methods, Bootstrapping | **Tracer**, **AWTY**, **CODA**, **RWTY** read data produced by MrBayes, [HOME PAGE](http://nbisweden.github.io/MrBayes/) |
| msa | R | Fasta files | MSA | **ClustalW**, **ClustalOmega**, and **MUSCLE** MSA tool entirely in R, LATEX rendering | Beautiful DRAWINGS of MSA, [Manual](https://bioconductor.riken.jp/packages/3.1/bioc/vignettes/msa/inst/doc/msa.pdf) |
| MyHits | online | Fasta MSA | Phylip, Clustal MSA | Convertion of MSA to different format | Only for small alignments, [Web-Site](https://myhits.sib.swiss/cgi-bin/reformat) |
| NGPhylogeny.fr | online | Fasta MSA | Phylip, Clustal MSA | Convertion of MSA to different format | Can convert large alignments!, [Web-Site](http://phylogeny.lirmm.fr/phylo_cgi/data_converter.cgi) |
| pplacer | command-line | Fasta files | Maps of sequences to Reference Database | Pplacer places query sequences on a fixed reference phylogenetic tree to maximize phylogenetic likelihood or posterior probability according to a reference alignment | [Tutorial](http://fhcrc.github.io/microbiome-demo/) |
| phylogram | R | - | - | Convertion of trees to *dendrogram* objects from *phylo* objects | [MANUAL](https://cran.r-project.org/web/packages/phylogram/vignettes/phylogram-vignette.html) |
| phangorn | R | NEXUS, Phylip, Fasta msa | Newick | phangorn is a package for phylogenetic reconstruction and analysis in the R language, UPGMA, Maximum Parsimony, Maximum Likelihood, also Bootstrapping | [Tutorial](https://cran.r-project.org/web/packages/phangorn/vignettes/Trees.html#distance-based-methods), [some example](https://cran.r-project.org/web/packages/phangorn/vignettes/IntertwiningTreesAndNetworks.html) |
| AMBER | R | - | - | - | - |
| MUSCLE | R | - | - | - | - |
| HMMER | R | - | - | - | - |
https://www.ebi.ac.uk/seqdb/confluence/display/JDSAT
| Pfam | database | - | - | The Pfam database is a large collection of protein families, each represented by multiple sequence alignments and hidden Markov models (HMMs) | [Web-Site](http://pfam.xfam.org/) |
| phylotools | R | Fasta or PHYLIP MSA | **RAxML** supermatrix | - | - |
| phytools | R | - | - | - | [TUTORIAL](http://www.phytools.org/Cordoba2017/ex/15/Plotting-methods.html) |
| phyML | R | PHYLYP, NEXUS msa | Newick?? | Maximum Likelihood | Doesn't work for >4000 sequences, Various models of substitution |
| phylophlan | Python | Fasta's + Reference Database (need to be prepared) | msa, phylogeny | **FastTree** is used to build approximate maximum likelihood tree, then **RAxML** is used to build maximum likelihood tree based on it | Python interface!!! |
| phylo-cgi converter | online | - | - | Fasta msa to Phylip msa | [Web Page](http://phylogeny.lirmm.fr/phylo_cgi/data_converter.cgi) |
| prodigal | command-line | Fasta MAGs, contigs, genomes | gene positions with meta information | protein-coding GENE PREDICTION software tool for bacterial and archaeal genomes | [Git-Hub](https://github.com/hyattpd/Prodigal) |
| RAxML | command-line | Phylip (relaxed) or Fasta msa, Newick for trees | Trees with bootstrap values, Starting Tree, Final tree | Sequential and parallel Maximum Likelihood based inference of large phylogenetic trees | [Step-by-step Tutorial](https://cme.h-its.org/exelixis/web/software/raxml/hands_on.html), [Manual](https://cme.h-its.org/exelixis/resource/download/NewManual.pdf)|
| RAST | Web annotation server | Contigs in Fasta | - | - | [Presentations](https://blog.theseed.org/servers/rast-workshop-presentations.html) |
| SILVA | database | - | - | SILVA provides comprehensive, quality checked and regularly updated datasets of aligned small (16S/18S, SSU) and large subunit (23S/28S, LSU) ribosomal RNA (rRNA) sequences for all three domains of life (Bacteria, Archaea and Eukarya). | [Web-Site](https://www.arb-silva.de/) |
| treeio | R | almost any formats of phylogenetic trees and outputs of common services | Tree object to process with **ggtree** | parsing trees | Services whose output can be parsed: BEAST, RAxML, HyPhy, PAML, pplacer, RevBayes, FPA, PHYLODOG, phyloT, r8s, ...[MANUAL](https://guangchuangyu.github.io/ggtree-book/chapter-treeio.html) |
| Treemmer | Python | ete3.Tree | ete3.Tree | Trim large trees, different options of trimming, based on **ETE Toolkit** | [GitHub](https://github.com/fmenardo/Treemmer) |
| TreeView | GUI | Newick | Picture | Tree visualization | Some software from the dawn of bioinformatics |
