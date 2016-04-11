# binomial-test-for-genomic-overlaps


#Usage

<pre>
./binomial2.sh file1.bed file2.bed
Number of unique overlaps of A and B
143
Calculating coverage of ./file2.bed in human genome hg19
Base pair coverage of B in hg19 is: 0.00566281
Calculating binomial p-value with pbinom(143, 42920, 0.00566281)
Binomial p-value:
[1] 2.196093e-12
 num 2.2e-12
</pre>
