scCEM - single-cell co-expressed module

identify gene regulatory network from scRNA-seq data in cancer

gene modules/GRNs - two different things

known tools for module identification
- non-negative matrix factorization (NMF)
- https://github.com/renozao/NMF

my ideas:
- one gene may belong to multiple modules (just like GO/KEGG)
- coexpression highly depends on cell context!!!
- so, one atlas = one set of modules is not reasonable!

de novo module annotation
- UMAP with known genesets
- annotation by known gene sets
- how to calculate the distances of modules is critical

characteristic of modules
- expression ranking along clusters
- frequency of CEM
- survival curve of CEM
- DepMap of CEM
- etc.


refs:
- [Hallmarks of transcriptional intratumour heterogeneity across a thousand tumours](https://www.nature.com/articles/s41586-023-06130-4#Abs1)
- [Progressive plasticity during colorectal cancer metastasis](https://www.nature.com/articles/s41586-024-08150-0) - HTAN CRC metastasis Dana Peer

