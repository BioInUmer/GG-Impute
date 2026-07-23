## GG-Impute

This is a genotype imputation pipeline I built during my [Master’s thesis](https://doi.org/10.5281/zenodo.21242279) at [IR Sant Pau](https://www.recercasantpau.cat/en/).

While working on my thesis, I needed to perform association analysis using raw array genotypes from a cohort genotyped in multiple batches. I couldn’t find a single comprehensive resource, so I ended up piecing together the information from various forums, guides, and documentation. As I ran my own imputation pipeline in the lab, I focused on making the process reproducible to ensure that current and future analyses in the group are consistent and more time-efficient.

I’ve documented every step and decision behind the pipeline here because I believe it can help others avoid the same obstacles and make the imputation process easier to approach. 

If you have any suggestions or ideas to improve this work, I would love to hear from you!

## Documentation

View the complete documentation of the imputation pipeline at: [GG-Impute](https://bioinumer.github.io/GG-Impute/).

![Genotype imputation pipeline](Imputation-pipeline.png)

**Genotype imputation pipeline.** **(A)** Dataset pre-processing. **(B)** Variant-level quality control. **(C)** Sample-level quality control. **(D)** Merging of individually quality-controlled batches. **(E)** TOPMed imputation after verification of dataset’s format and compatibility using McCarthy tools. **(F)** Post-imputation quality control.