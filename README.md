# to build a web application that can retrieve genomic information of variantsfrom all known associations to T1D and integrate them with population and functional information.It should also be capable to produce informative plots and analyses in this regard.Specifically, the web application should satisfy the following requirements:

1. The user should be able to retrieve SNP information given either its name (rs value), genomic
coordinates (chromosome, start and end), and gene name.

2. The application should return the following information for each query: SNP name(s) (rs value),
genomic position(s) (its location), p-value(s) from the association test, mapped gene(s), variant
(allele) frequency in at least two different human populations of interest, at least one measure of
functional impact and/or clinical relevance for each variant, at least one functional or ontology term
associated with each mapped gene.

3. If multiple SNPs are returned, the user should be able to select the SNPs of interest, calculate
measurements of linkage disequilibrium (LD) for each pair of SNPs, separately for each population,
and plot their values. The user will also be able to download a text file with the LD values.

Remember that results should be presented in a manner that will help answer biological questions.
4. If genomic coordinates are provided in input and multiple SNPs are returned, a Manhattan plot of
p-values should be provided
