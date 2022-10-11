# Sex Test Workflow

[Rakeiora](http://rakeiora.ac.nz)

---
This study, commensurate with the author's knowledge of human biology,
addresses a burning question of human biology:

> Did a given genomic sample come from a male or female participant?

---

Previous research has demonstrated that when we request positions
20,000,000-30,000,000 of Chromosome Y, we find a BAM file of
approximately 70MB from males, while a female's BAM file of
the same region of Chromosome Y yields a file smaller than 10MB.

So if we request this region from each sample (use the bed file
provided, y_20M_30M.bed, or its multi-region version),
we can test the resulting size (we use 30MB as a threshold)
and determine the sex of the participant from whom the sample came.
