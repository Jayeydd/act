# Plastid Genome Characterization: Ginkgo biloba

**Student:** Jade Angela Suan

**Course/Section:** Cell & Molecular Biology

**Date:** 2026-09-30

## Genome Information
- **Organism:** *Ginkgo biloba*
- **Family:** Ginkgoaceae
- **NCBI Accession:** MN443423.1
- **Source:** https://www.ncbi.nlm.nih.gov/nuccore/MN443423.1
- **Retrieved:** 2026-09-30
- **Reference:** Yang, X., Zhou, T., Wang, G., Zhang, X., Guo, Q., & Cao, F. (2021). Structural characterization and comparative analysis of the chloroplast genome of Ginkgo biloba and other gymnosperms. Journal of Forestry Research, 32(2), 765–778. https://link.springer.com/article/10.1007/s11676-019-01088-4

## Plastome Summary
 | Feature | Value |
 |---|---|
 | Total genome size | 156,990 bp |
 | GC content | 39.56% |
 | Topology | Circular |
 | LSC size | 88, 923 bp |
 | SSC size | 18, 261 bp |
 | IR size (each) | 24, 903 bp |
 | Total annotated genes | ~133 |
 | Protein-coding genes | ~88 |
 | tRNA genes | 35 |
 | rRNA genes | 8 |
 
 **Notable features:**
 - Quadripartite structure (LSC–IRa–SSC–IRb)
 - *rps12* trans-splicing (5' exon in LSC, 3' exons in IR)
 - Genes with introns: *rps12, atpF, rpoC1, petB, petD*
 - No confirmed pseudogenes or large rearrangements
 **Galaxy analysis:**
 - History name: Plastid_Ginkgo_Suan
 - Tool: Fasta Statistics
 - Screenshot saved in `figures/`
 ---

## Genome Structure
- LSC: ~99,296 bp
- IRa & IRb: ~17,790 bp each
- SSC: ~22,114 bp

## Methods
- Downloaded FASTA & GenBank files from NCBI GenBank
- Uploaded FASTA to Galaxy (usegalaxy.org)
- **Galaxy History:** Plastid_Ginkgo_Suan
- **Tool Used:** Fasta Statistics
- **Results:** 1 sequence, 156,990 bp, GC = 39.56%, N = 0
- Screenshot saved in figures/

## Gene Summary
- Total genes: ~133
- Protein-coding: 88 | tRNA: 35 | rRNA: 8
- Notable features: *rps12* trans-splicing; standard quadripartite architecture
- No confirmed pseudogenes or large rearrangements

## Reproducibility
1. Open https://www.ncbi.nlm.nih.gov/nuccore/MN443423.1 → download FASTA
2. Sign in to Galaxy → create history named Plastid_Ginkgo_Suan
3. Upload FASTA → run Fasta Statistics
4. Cross-check gene content against the GenBank annotation page
