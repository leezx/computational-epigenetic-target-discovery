
Once we know where do TF bind on genome, we want to know what are other proteins that bind to the TF(s) to have function.

Evidence (second layer binding):
1. known PPI from database
2. AlphaFold PPI prediction
3. ChIP-seq analysis (summit distance)

Protein complex (e.g. BAF)
1. known database
2. ChIP-seq prediction

Goal:
1. given a gene program/module, we can get the ATAC-seq peaks
2. get the first layer TF binding based on motif matching
3. get the second layer protein interactions
4. get the putative protein complexes

Final goal:
- find the best target in the module, degrade it to interfere the activity of the GRN
