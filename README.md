## Introduction



## Diversity annotation

![](images/diversity_index.png)
The diversity in memory cells is lower than in naive cells. Thus, according to Normalized Shannon and Chao1 diversity indices calculations — 4 samples (s7, s3, s4, s6) have much lower diversity and can be identified as memory cells. 

## V segment usage profile

### Classification of samples by replicas

The heatmap of overlapped clonotype lists highlights the replicas in the data:

![](images/map.png)

Replicas:
* s3/s7
* s4/s6
* s8/s10
* s1/s5
* s13/s2
* s15/s16
* s9/s14
* s11/s12


## Repertoire annotation

### Annotation of antigen-specific TCR sequences

CMV status annotation:
![](images/antigen_status.png)

On this image the parent species of putative antigens are described. It can be interpreted that s3 and s7 belong to CMV+ donor as they show around 3-4% fraction of the matching reads.

Based on the results of alignment to the specific Homo Sapiens CD8 TRB sequences, we established that s4/s6 (and therefore s11/s12) belong to the CMV- donor because they are not associated with the
antigen to CMV.

### HLA annotation

The final step of the RepSeq investigation is HLA allele identification. 

![](images/HLA_allele.png)

The CMV+ donor has B*07 HLA allele (s3 and s7 samples). Therefore, draw a conclusion using the putative antigen TCR recognition map. 
...
To conclude with, ...

## The final table

| Sample | Donor | Subset | Phenotype | CMV status |
|--------|-------|--------|-----------|------------|
| s1     | D1    | CD4    | memory    | CMV+       |
| s2     | D1    | CD4    | naive     | CMV+       |
| s3     | D1    | CD8    | memory    | CMV+       |
| s4     | D2    | CD8    | memory    | CMV-       |
| s5     | D1    | CD4    | memory    | CMV+       |
| s6     | D2    | CD8    | memory    | CMV-       |
| s7     | D1    | CD8    | memory    | CMV+       |
| s8     | D2    | CD4    | memory    | CMV-       |
| s9     | D1    | CD8    | naive     | CMV+       |
| s10    | D2    | CD4    | memory    | CMV-       |
| s11    | D2    | CD8    | naive     | CMV-       |
| s12    | D2    | CD8    | naive     | CMV-       |
| s13    | D1    | CD4    | naive     | CMV+       |
| s14    | D1    | CD8    | naive     | CMV+       |
| s15    | D2    | CD4    | naive     | CMV-       |
| s16    | D2    | CD4    | naive     | CMV-       |

