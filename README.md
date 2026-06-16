# Fetal meconium microbiota analysis

Analysis code accompanying:

> Kennedy KM, Gerlach MJ, Adam T, Heimesaat MM, Rossi L, Surette MG, Sloboda DM, Braun T. *Fetal meconium does not have a detectable microbiota before birth.* Nature Microbiology. 2021. doi:[10.1038/s41564-021-00904-0](https://doi.org/10.1038/s41564-021-00904-0)

**What this does:** Tests whether bacteria are detectable in fetal meconium collected before birth, comparing sequencing and culture against technical and procedural controls.

**Methods:** 16S rRNA gene sequencing analysis; comparison of fetal meconium against negative/contamination controls, neonatal meconium, and infant stool; low-biomass contamination-control workflow alongside aerobic/anaerobic culture results.

**Stack:** R (16S analysis, tidyverse, ggplot2), written as a single R Markdown report.

**Repository layout** (default branch: `main`)
- `meconium_analysis.Rmd` — full analysis report (sequencing and culture comparison against controls)
