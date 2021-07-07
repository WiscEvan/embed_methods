# embed_methods
Comparison of embedding methods on 78.125Mbp simulated community. See [embedding_method_comparisons.ipynb](https://github.com/WiscEvan/embed_methods/blob/main/embedding_method_comparison.ipynb) for additional details

## Generating data used in the notebook

Data was generated using code from [Autometa PR#176](https://github.com/KwanLab/Autometa/pull/176)

## General notes

- It appears some of the contigs do not group together, no matter the embedding method
  - Some examples include *gabonia massiliensis* and *deinococcus maricopensis*
- UMAP appears to perform best with tightly grouping contigs across all canonical ranks.
  - [UMAP embedding colored by phylum](https://github.com/WiscEvan/embed_methods/blob/main/plots/UMAP_embedding_scatterplot_colored_by_phylum.pdf)
  - [UMAP embedding colored by class](https://github.com/WiscEvan/embed_methods/blob/main/plots/UMAP_embedding_scatterplot_colored_by_class.pdf)
  - [UMAP embedding colored by order](https://github.com/WiscEvan/embed_methods/blob/main/plots/UMAP_embedding_scatterplot_colored_by_order.pdf)
  - [UMAP embedding colored by family](https://github.com/WiscEvan/embed_methods/blob/main/plots/UMAP_embedding_scatterplot_colored_by_family.pdf)
  - [UMAP embedding colored by genus](https://github.com/WiscEvan/embed_methods/blob/main/plots/UMAP_embedding_scatterplot_colored_by_genus.pdf)
  - [UMAP embedding colored by species](https://github.com/WiscEvan/embed_methods/blob/main/plots/UMAP_embedding_scatterplot_colored_by_species.pdf)
- TriMap may contain some semantic structure. This may be easily observed within TriMap plot colored by Order.
  - The bacillales and bacteriales appear to be grouped with others of the same class (bacilli and actinomycetia, respectively)
  - [TriMap embedding colored by class](https://github.com/WiscEvan/embed_methods/blob/main/plots/TriMap_embedding_scatterplot_colored_by_class.pdf) -> [TriMap embedding colored by order](https://github.com/WiscEvan/embed_methods/blob/main/plots/TriMap_embedding_scatterplot_colored_by_order.pdf)
  
