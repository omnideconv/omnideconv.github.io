# Welcome to omnideconv!

omnideconv is an ecosystem of user-friendly tools and resources for the cell-type deconvolution of any orgnaism and tissue profiled with bulk transcriptomics.

# Estimating immune-cell fractions from bulk RNA-seq data

[Source code](https://github.com/omnideconv/immunedeconv/) | [Issue tracker](https://github.com/omnideconv/immunedeconv/issues) | [Documentation](https://omnideconv.org/immunedeconv) | [Community Forum](https://github.com/omnideconv/immunedeconv/discussions)

![immunedeconv](immunedeconv_logo_sm.png)

Since the performance of in silico approaches for estimating immune-cell fractions from bulk RNA-seq data can vary, it is often advisable to compare results of several methods. Given numerous dependencies and differences in input and output format of the various computational methods, comparative analyses can become quite complex. This motivated us to develop [`immunedeconv`](https://omnideconv.org/immunedeconv), an R package providing uniform and user-friendly access to seven state-of-the-art computational methods for deconvolution of cell-type fractions from bulk RNA-seq data. 

# Robust cell-type deconvolution from any tissue informed by scRNA-seq

[Source code](https://github.com/omnideconv/omnideconv/) | [Issue tracker](https://github.com/omnideconv/omnideconv/issues) | [Documentation](https://omnideconv.org/omnideconv) 

![Omnideconv](omnideconv_logo_sm.png)
     
The possibility to computationally infer the cellular composition of heterogeneous samples profiled with (cheap) bulk RNA (RNA-seq) or DNA methylation (DNAm) sequencing is a powerful way to advance our understanding of tissue and organ development as well as diseases. Building on the success of [`immunedeconv`](https://omnideconv.org/immunedeconv) for in silico deconvolution of immune cells, [`omnideconv`](https://omnideconv.org/omnideconv) will streamline existing methods for cell type deconvolution, facilitate systematic benchmarking, offer multi-species support, and offer user-friendly access to signature generation and comparative analyses. The change in the project's name from [`immunedeconv`](https://omnideconv.org/immunedeconv) to [`omnideconv`](https://omnideconv.org/omnideconv) is owed to the possibility offered by second-generation methods to construct cell-type specific signatures directly from single-cell RNA-seq data, thus possibly extending cell-type deconvolution to any cell type, organism, and tissue profiled with single-cell technology. 

# Simulating in silico ground-truth data with pseudo-bulk RNA-seq

[Source code](https://github.com/omnideconv/SimBu/) | [Issue tracker](https://github.com/omnideconv/SimBu/issues) | [Documentation](https://omnideconv.org/SimBu) 

To facilitate benchmarking of second-generation cell type deconvolution tools we have further created [`SimBu`](https://omnideconv/SimBu), the first dedicated tool for generating faithful pseudo-bulk RNA-seq data sets that serve as an insilico gold standard with known cell type fractions for benchmarking. Pseudo-bulk samples are generated from single-cell RNA-seq data where single cells are aggregated in user-defined fractions. In contrast to existing simulation approaches, [`SimBu`](https://omnideconv.org/SimBu) offers a user-friendly and well-documented tool and is the only approach considering that the total amount of mRNA differs by cell type.

# Contact

If you have questions or comments, reach out to [Francesca Finotello](mailto:francesca.finotello@uibk.ac.at?subject=omnideconv), [Markus List](mailto:markus.list@tum.de?subject=omnideconv), or [Gregor Sturm](mailto:gregor.stum@i-med.ac.at?subject=omnideconv).

