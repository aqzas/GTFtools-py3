# GTFtools-py3
Python3 version of GTFtools

#### Examples
Note: the demo.gtf is included in this package

Example 1: For each gene, calculate non-overlapping exons by merging all exons of splice isoforms
```
gtftools.py -m merged_exons.bed demo.gt
```

Example 2: calculate four types of gene lengths:
```
gtftools.py -l gene_length.bed demo.gtf
```


Citation and usage: http://www.genemine.org/gtftools.php
