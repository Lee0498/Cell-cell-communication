# Cell-cell communication

Collection of computational tools for [cell-cell communication inference for single-cell](https://pubmed.ncbi.nlm.nih.gov/32435978/) and spatially resolved omics, including epigenomics, transcriptomics, proteomics, metabolomics, etc. Welcome contribution. Please folk this repository and create a pull request if you have an update. Please Cite us by "Shao, X., et al. Collection of computational tools for cell-cell communication inference for single-cell and spatially resolved omics (2022) [DOI: 10.5281/zenodo.7277161](https://zenodo.org/record/7277161)".

<img src='https://github.com/shaoxin0801/Cell-cell-communication/blob/main/img/Cell-cell%20communication.png'>

### Computational tools based on single-cell transcriptomic data
- __[CCCExplorer](https://github.com/methodistsmab/CCCExplorer)__ -[Java]- CCCExplorer is a java-based software that predicts and visualizes the gene signaling network to aid research on crosstalk identification in the tumor microenvironment.
- __[cell2cell](https://github.com/earmingol/cell2cell)__ -[python]- Tensor-cell2cell is an unsupervised method using tensor decomposition, which deciphers context-driven intercellular communication by simultaneously accounting for multiple stages, states, or locations of the cells.
- __[CellCall](https://github.com/ShellyCoder/cellcall)__ -[R]- CellCall integrates paired ligand-receptor and transcription factor activities for cell-cell communication inference.
- __[CellChat](https://github.com/sqjin/CellChat)__ -[R]- CellChat enables inference and analysis of cell-cell communication for systematically detecting dysregulated cell-cell communication across biological conditions.
- __[celltalker](https://github.com/arc85/celltalker)__ -[R]- celltalker can infer putative ligand and receptor interactions from single-cell RNAseq data
- __[CellPhoneDB](https://github.com/Teichlab/cellphonedb)__ -[python]- CellPhoneDB is a publicly available repository of curated receptors, ligands and their interactions.
- __[CommPath](https://github.com/yingyonghui/CommPath)__ -[R]- CommPath is an R package for inference and analysis of ligand-receptor interactions from single cell RNA sequencing data.
- __[COMUNET](https://github.com/ScialdoneLab/COMUNET)__ -[R]- COMUNET uses multiplex networks to represent and cluster all potential communication pathways between cell types.
- __[CrossTalkeR](https://github.com/CostaLab/CrossTalkeR)__ -[R]- CrossTalkeR is a framework for network analysis and visualisation of LR networks. CrossTalkeR identifies relevant ligands, receptors and cell types contributing to changes in cell communication when contrasting two biological states: disease vs. homeostasis.
- __[CytoTalk](https://github.com/tanlabcode/CytoTalk)__ -[R]- CytoTalk algorithm is for de novo construction of a signaling network between two cell types using single-cell transcriptomics data.
- __[exFINDER](https://github.com/ChanghanGitHub/exFINDER)__ -[R]- exFINDER is a method that identifies external signals (received signals from the external system, exSigNet) in the single-cell transcriptomics datasets by utilizing the prior knowledge of signaling pathways.
- __[iCELLNET](https://github.com/soumelis-lab/ICELLNET)__ -[R]- iCELLNET enables dissection of intercellular communication using the transcriptome-based framework.
- __[iTALK](https://github.com/soumelis-lab/ICELLNET)__ -[R]- iTALK is an R toolkit for characterizing and illustrating intercellular communication.
- __[LRLoop](https://github.com/Pinlyu3/LRLoop)__ -[R]- LRLoop is a full-featured R package for analyzing LR-Loops from bulk & single-cell RNA-seq data.
- __[mistyR](https://saezlab.github.io/mistyR/)__ -[R]- mistyR facilitates an in-depth understanding of marker interactions by profiling the intra- and intercellular relationships.
- __[MEBOCOST](https://github.com/zhengrongbin/MEBOCOST)__ -[python]- MEBOCOST is a Python-based computational tool for inferring metabolite, such as lipid, mediated cell-cell communication events using single-cell RNA-seq data.
- __[NATMI](https://github.com/forrest-lab/NATMI)__ -[python]- NATMI (Network Analysis Toolkit for Multicellular Interactions) is a Python-based toolkit for multi-cellular communication network construction and network analysis of multispecies single-cell and bulk gene expression and proteomic data.
- __[NeuronChat](https://github.com/Wei-BioMath/NeuronChat)__ -[R]- The goal of NeuronChat is to infer, visualize and analyze neural-specific cell-cell communication from single cell transcriptomics or spatially resolved transcriptomics data.
- __[NicheNet](https://github.com/saeyslab/nichenetr)__ -[R]- NicheNet can study intercellular communication from a computational perspective. NicheNet uses human or mouse gene expression data of interacting cells as input and combines this with a prior model that integrates existing knowledge on ligand-to-target signaling paths.
- __[NICHES](https://github.com/msraredon/NICHES)__ -[R]- Niche Interactions and Cellular Heterogeneity in Extracellular Signaling.
- __[PyMINEr](https://bitbucket.org/scottyler892/pyminer_release/src/master/)__ -[python]- PyMINEr can fully automate cell type identification, cell type-specific pathway analyses, graph theory-based analysis of gene regulation, and detection of autocrine-paracrine signaling networks in silico.
- __[RaCInG](https://github.com/SysBioOncology/RaCInG)__ -[python]- RaCInG used patient specific bulk RNA-seq input together with non-patient specific prior knowledge on possible ligand-receptor interactions to reconstruct cell-cell interaction networks in an indivudal patient's tumour.
- __[RSoptSC](https://github.com/mkarikom/RSoptSC)__ -[R]- RSoptSC enables cell-cell communication and lineage inference for scRNA-seq data.
- __[scCrossTalk](https://github.com/ZJUFanLab/scCrossTalk)__ -[R]- scCrossTalk can find and visulize significant LR pairs between pairwise clusters and significant crosstalk between pairwise clusters for single-cell RNA-seq data.
- __[scMLnet](https://github.com/SunXQlab/scMLnet)__ -[R/python]- scMLnet is an R package developed to construct inter-/intracellular multilayer singaling network based on single-cell RNA-seq expression data.
- __[scriabin](https://github.com/BlishLab/scriabin)__ -[R]- scriabin aims to provide a comprehensive view of cell-cell communication at the single-cell level without requiring subsampling or aggregation.
- __[scTenifoldXct](https://github.com/cailab-tamu/scTenifoldXct)__ -[python]- scTenifoldXct leverages manifold alignment of gene regression networks to detect LR-mediated cell-cell interactions, including (1) weak but biologically important interactions (2) differential interactions between two different samples
- __[scTensor](https://github.com/rikenbit/scTensor)__ -[R]- scTensor is a R package for detection of cell-cell interaction using Non-negative Tensor Decomposition.
- __[SingleCellSignalR](https://github.com/SCA-IRCM/SingleCellSignalR)__ -[R]- SingleCellSignalR is a R package to study Cell Signaling Using Single Cell RNAseq Data.
- __[SPRUCE](https://github.com/causalpathlab/spruceTopic)__ -[python]- SPRUCE is designed to systematically ascertain common cell-cell communication patterns embedded in single-cell RNA-seq data.
- __[TraSig](https://github.com/doraadong/TraSig)__ -[python]- TraSig (Trajectory-based Signalling genes inference) identifies interacting cell types pairs and significant ligand-receptors based on the expression of genes as well as the pseudo-time ordering of cells. 

### Computational tools based on spatially resolved transcriptomic data
- __[BulkSignalR](https://github.com/jcolinge/BulkSignalR)__ -[R]- BulkSignalR is a R package to infer ligand-receptor networks with downstream pathways from bulk data or spatial data (localized bulk data).
- __[CCPLS](https://github.com/bioinfo-tsukuba/CCPLS)__ -[R]- CCPLS (Cell-Cell communications analysis by Partial Least Square regression modeling) is a statistical framework for identifying cell-cell communications as the effects of multiple neighboring cell types on cell-to-cell expression variability of HVGs, based on the spatial transcriptome data.
- __[CellPhoneDB](https://github.com/ventolab/CellphoneDB)__ -[python]- CellPhoneDB allows the incorporation of spatial information of the cells to define possible pairs of interacting cells (i.e. pairs of clusters sharing/coexisting in a microenvironment).
- __[COMMOT](https://github.com/zcang/COMMOT)__ -[python]- COMMOT uses collective optimal transport to infer CCC in spatial transcriptomics, which accounts for the competition among different ligand and receptor species as well as spatial distances between cells.
- __[DeepLinc](https://github.com/xryanglab/DeepLinc)__ -[python]- DeepLinc is a method for de novo reconstruction of cell interaction networks from single-cell spatial transcriptomic data based on a deep generative model of variational graph autoencoder (VGAE).
- __[GCNG](https://github.com/xiaoyeye/GCNG)__ -[python]- GCNG uses graph convolutional neural network and spaital transcriptomics data to infer cell-cell interactions.
- __[Giotto](https://github.com/drieslab/Giotto)__ -[R]- Giotto introduces a two-way comparison method to identify interaction changed genes by comparing the gene expression pattern between subsets of cells within the same cell type but surrounded by different neighboring cells.
- __[HoloNet](https://github.com/lhc17/HoloNet)__ -[python]- Functional cell–cell communication events (FCEs) is mediated by ligand–receptor pairs and works directly for specific downstream response (expression of FCEs regulated target genes) in a particular microenvironment. HoloNet is designed for decoding FCEs using spatial transcriptomic data by integrating ligand–receptor pairs, cell-type spatial distribution and downstream gene expression into a deep learning model.
- __[ncem](https://github.com/theislab/ncem)__ -[python]- ncem can learn cell communication from spatial graphs of cells.
- __[NeuronChat](https://github.com/Wei-BioMath/NeuronChat)__ -[R]- The goal of NeuronChat is to infer, visualize and analyze neural-specific cell-cell communication from single cell transcriptomics or spatially resolved transcriptomics data.
- __[NICHES](https://github.com/msraredon/NICHES)__ -[R]- Niche Interactions and Cellular Heterogeneity in Extracellular Signaling.
- __[SCVA](https://github.com/damienArnol/svca)__ -[R/python]- SCVA enables quantifying different dimensions of spatial variation and in particular quantifies the effect of cell-cell interactions on gene expression.
- __[SpaCET](https://github.com/data2intelligence/SpaCET)__ -[R]- SpaCET is an R package for analyzing cancer spatial transcriptomics (ST) datasets to estimate cell lineage and intercellular interactions in tumor microenvironment.
- __[spaCI](https://github.com/QSong-github/spaCI)__ -[python]- spaCI, a novel adaptive graph model with attention mechanisms, incorporates both spatial locations and gene expression profiles of cells to identify the active ligandreceptor signaling axis across neighboring cells.
- __[SpaOTsc](https://github.com/zcang/SpaOTsc)__ -[python]- SpaOTsc can infer space-constrained cell-cell communications, infer spatial distance for intercellular signaling, and construct a spatial map of intercellular gene-gene regulatory information flow.
- __[spARC](https://github.com/KrishnaswamyLab/sparc)__ -[python]- spARC, a diffusion geometric framework that integrates in situ location and gene expression information to denoise spatial transcriptomics data and identify paracrine receptor-ligand signaling interactions between cells within their spatial contexts. 
- __[SpaTalk](https://github.com/ZJUFanLab/SpaTalk)__ -[R]- SpaTalk is a spatially resolved cell-cell communication inference method relying on the graph network and knowledge graph to model ligand-receptor-target signaling network for either single-cell or spot-based spatially resolved transcriptomic data, e.g., STARmap, MERFISH, seqFISH, Slide-seq, 10X Visium.
- __[SpatialDM](https://github.com/StatBiomed/SpatialDM)__ -[python]- SpatialDM is a Python package for identifying spatial co-expressed ligand and receptor using Moran's bivariant extension.
