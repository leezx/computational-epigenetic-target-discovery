# computational-epigenetic-target-discovery
computational epigenetic target discovery

De novo target discovery
1. cancer subtyping and biomarker
2. single-cell cancer atlas
3. cancer module discovery
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
1. DepMap rank
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

others:
- normal human single-cell atlas for side effect evaluation (normal GRN)
- gene expression in different tissues, tissue toxic score

experiment repeat validation 
- Perturbseq
- Cell line/patient-derived organoid xenograft (growth/mRNA/protein/IHC)

ref:
- Gavish, A., Tyler, M., Greenwald, A.C. et al. Hallmarks of transcriptional intratumour heterogeneity across a thousand tumours. Nature 618, 598–606 (2023). https://doi.org/10.1038/s41586-023-06130-4
- https://github.com/carmonalab/GeneNMF
