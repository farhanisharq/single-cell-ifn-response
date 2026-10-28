# Single-cell RNA-seq analysis of in￾terferon response in PBMCs

This notebook displays a rudimentary analysis of scRNA sequencing data using the scverse Python tools (mainly Scanpy<sup>1</sup>). I used the processed dataset (GEO Accession GSE96583) from Kang _et al_.<sup>2</sup> This was a submission for a techincal assessment as part of a PhD application.

Kang et _al_<sup>3</sup> profiled peripheral blood mononuclear cells (PBMCs) from patients with systemic lupus erythematosus using droplet-based single-cell RNA-seq (10x Genomics). Two different aliquots of cells from each donor were taken: untreated (control) and stimluated with recombinant IFN-β for 6 hours. The samples were pooled and multiplexed with donor identity resolved by genotype-based demultiplexing (demuxlet). The study characterised cell-type-specific interferon responses and the genetic basis of expression variation.

See notebook for further details and findings.

## License

Code in this repository is released under the MIT License (see [`LICENSE`](LICENSE)). The dataset belong to their original source.<sup>3</sup>

## References

1. Wolf, F., Angerer, P. & Theis, F. SCANPY: large-scale single-cell gene expression data analysis. Genome Biol 19, 15 (2018). https://doi.org/10.1186/s13059-017-1382-0
2. Schumacher, Antonia; Heumos, Lukas (2022). Kang HM, Subramaniam M, Targ S, Nguyen M et al. 2017. figshare. Dataset. https://doi.org/10.6084/m9.figshare.19397624.v2
3. Kang, H., Subramaniam, M., Targ, S. et al. Multiplexed droplet single-cell RNA-sequencing using natural genetic variation. Nat Biotechnol 36, 89–94 (2018). https://doi.org/10.1038/nbt.4042

The notebook also provides additional references.
