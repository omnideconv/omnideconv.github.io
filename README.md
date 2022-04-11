# 

![Omnideconv](omnideconv_logo.jpg)

# Robust deconvolution of cell types from any tissue
     
The possibility to computationally infer the cellular composition of heterogeneous samples profiled with (cheap) bulk RNA (RNA-seq) or DNA methylation (DNAm) sequencing is a powerful way to advance our understanding of tissue and organ development as well as diseases. Building on the success of [`immunedeconv`](https://github.com/icbi-lab/immunedeconv) for in silico deconvolution of immune cells, [`omnideconv`](https://github.com/omnideconv/omnideconv) will streamline existing methods for cell type deconvolution, facilitate systematic benchmarking, offer multi-species support, bridge RNA-seq and DNAm assays, and offer user-friendly access to signature generation and comparative analyses. The change in the project's name from `immunedeconv` to `omnideconv` is owed to the possibility offered by second-generation methods to construct cell-type specific signatures directly from single-cell RNA-seq data, thus possibly extending cell-type deconvolution to any cell type, organism, and tissue profiled with single-cell technology. 

# Simulating in silico ground truth data with pseudo-bulk RNA-seq

To facilitate benchmarking of second-generation cell type deconvolution tools we have further created [`SimBu`](https://github.com/omnideconv/simbu), the first dedicated tool for generating faithful pseudo-bulk RNA-seq data sets that serve as an insilico gold standard with known cell type fractions for benchmarking. Pseudo-bulk samples are generated from single-cell RNA-seq data where single cells are aggregated in user-defined fractions. In contrast to existing simulation approaches, `SimBu` offers a user-friendly and well-documented tool and is the only approach considering that the total amount of mRNA differs by cell type.

# Contact

If you have questions or comments, reach out to [Francesca Finotello](mailto:francesca.finotello@i-med.ac.at?subject=omnideconv), [Markus List](mailto:markus.list@wzw.tum.de?subject=omnideconv), or [Gregor Sturm](mailto:gregor.stum@i-med.ac.at?subject=omnideconv).

