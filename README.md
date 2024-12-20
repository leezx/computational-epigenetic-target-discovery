# computational-epigenetic-target-discovery
computational epigenetic target discovery

Phenotype-Cellular state-CEM-GRN-epiDriver-PROTAC

how to find a good cancer target?
- human population genetic data (e.g. KRAS mutation)
- human population bulk RNA-seq (e.g. TCGA)
- human population scRNA-seq (e.g. CRC-Atlas, SOX9)

A pipeline to find a good target in cancer:
- cancer patient stratification by transcriptome
- OE in the cancer
- Dep in the cancer
- Low side effects
- ligand available, but not too hot
- Pan cancer

Key web lab experiments for cancer target validation:
1. Overexpression in cancer (mouse models and human patients) (qRT-PCR, immunohistochemistry) (TCGA, scRNA-seq, survival)
2. Cancer dependence (DepMap, cell line/Organoids CellTiterGlo by KD/KO, colony formation assay, cell line/Organoids xenograft in nude mice)
3. Molecular mechanisms (differentiation, signaling pathway, NGS multi-omics, new up/down-stream regulators)

ref:
- An Enhancer-Driven Stem Cell–Like Program Mediated by SOX9 Blocks Intestinal Differentiation in Colorectal Cancer
- Identifying regulators of aberrant stem cell and differentiation activity in colorectal cancer using a dual endogenous reporter system

De novo target discovery
1. cancer subtyping and biomarker
2. single-cell cancer atlas
3. cancer module discovery (intertumor and intratumor heterogeneity)
4. module clustering and annotation
5. master epigenetic regulator discovery
6. evaluation of module and target
7. de novo target-cancer relationship [Database]

module identification and annotation
1. cell type levels (organ/major cell type)
2. Level module
3. UMAP
4. projection with known non-redundant gene sets

target validation:
1. DepMap rank (conditional dependence/subtype)
2. TCGA overexpression

epigenetics
- the relationship between two peak sets/motif binding (x: peak distance cutoff, y: number of nearby peaks)
- epigenetic factor distance analysis

find key regulators of a module,
- ChIP-Atlas-based prioritization of epigenetic factors (SCENIC)
- motif and public ATAC-seq-based TF prioritization
- a custom figure, considering peak distance to TSS and target number

AI structure
1. in silico protein-protein interaction prediction (protein docking, co-IP)
2. fine mapping target-cancer relationship

AI text mining
1. Known target-cancer relationship [Database]

experiment repeat validation 
- Perturbseq
- Cell line/patient-derived organoid xenograft (growth/mRNA/protein/IHC)

others:
- normal human single-cell atlas for side effect evaluation (normal GRN)
- gene expression in different tissues, tissue toxic score
- biomarker-guided targeted therapy (known biomarkers in CRC)

ref:
- Gavish, A., Tyler, M., Greenwald, A.C. et al. Hallmarks of transcriptional intratumour heterogeneity across a thousand tumours. Nature 618, 598–606 (2023). 
- Liu, J., Dang, H. & Wang, X. The significance of intertumor and intratumor heterogeneity in liver cancer. Exp Mol Med 50, e416 (2018). 
- https://github.com/carmonalab/GeneNMF
