# Quantifying RT error rates with high throughput sequencing

This repository contains some explanatory material and examples describing the process
and invocation of some methods used to quantify reverse transcriptase error rates.

It combines the results from two small packages I wrote, one for pre-processing the data:

[errrt](https://github.com/abelew/errrt) and one for post-processing:

[Rerrrt](https://github.com/abelew/Rerrrt).

The file errrt_readme.md is the markdown README from the former, which lays out the process, 
installation, and invocation of the tools used to process the reads into a series of
tab-delimited outputs which are provided to Rerrrt.

The index.html is a slightly older vignette from Rerrrt which shows the invocation and
some output from that process.

Finally, error_quant.Rmd and the associated {rundate}_error_quant_{version}.html are
an actual R markdown document performing the analysis and its html report.
