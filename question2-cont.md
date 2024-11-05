**Question 2** : Please assign variables to the individual components of your favorite gene! (e.g.
promoter, 5' UTR, start codon, exon1, intron, exon2, stop codon, 3' UTR). Print the entire gene
by using the string concatenation operator, on the standard output! Note: Feel free to create a
fictional gene sequence by randomly filling in the gene components by the characters
corresponding to individual nucleotide bases.
 **Answer**

```python
promoter = "ATAATATCGATCG"
five_utr = "GGGAAATTT"
start_codon = "ATG"
exon1 = "GTCAGTCA"
intron = "CGTACGTA"
exon2 = "TACGATCG"
stop_codon = "TCA"
three_utr = "AAAGGAATCC"

full_gene_sequence = (
    promoter + 
    five_utr + 
    start_codon + 
    exon1 + 
    intron + 
    exon2 + 
    stop_codon + 
    three_utr
)

print("Full Gene Sequence:")
print(full_gene_sequence)
```


