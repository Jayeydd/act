# Genome and Gene Summary Tables

## Ginkgo biloba — MN443423.1

---

## 3. Data Source and Genome Selection

| Item | Information |
|---|---|
| Accession | MN443423.1 |
| Organism | *Ginkgo biloba* (Maidenhair Tree) |
| Family | Ginkgoaceae |
| Genome length | 156,990 bp |
| Topology | Circular |
| Reference | Yang, X., Zhou, T., Wang, G., Zhang, X., Guo, Q., & Cao, F. (2021). Chloroplast genome characterization and comparative analysis of the chloroplast genome of *Ginkgo biloba* and other gymnosperms. *Journal of Forestry Research*, 32(2), 765–778. DOI: 10.1007/s11676-019-01088-4 |

---

## 5. Galaxy Workflow

| Step | Information |
|---|---|
| Sign in to own account | https://usegalaxy.org |
| History name | Plastid_Ginkgo_Suan |
| Upload FASTA | Uploaded MN443423.1 FASTA |
| Recognized as FASTA and renamed | Format is fasta.<br>Renamed to: `Ginkgo_biloba_MN443423.1.fasta` |
| Tool used | Fasta Statistics |
| Genome length | 156,990 bp |
| Number of sequence records | 1 |
| GC content | 39.56% |
| Complete plastome in one sequence record? | Yes |

---

## 6. Required Plastid Genome Characterization

| Item | Information |
|---|---|
| Genus and species | *Ginkgo biloba* |
| Family | Ginkgoaceae |
| NCBI accession | MN443423.1 |
| Complete genome size | 156,990 bp |
| GC content | 39.56% |
| Topology | Circular |
| LSC | 88,923 bp |
| SSC | 18,261 bp |
| IR | 24,903 bp each |
| Total annotated genes | 135 |
| Protein-coding genes | 86 |
| tRNA genes | 41 |
| rRNA genes | 8 |
| Introns | 15 genes contain introns; *rps12, clpP, ycf3* each have 2 introns |
| Pseudogenes | None confirmed |
| Gene duplications | Inverted Repeat regions duplicate: *rrn16, rrn23, rrn4.5, rrn5, rps7, ndhB, rps12* (partial), *trnA-UGC, trnI-GAU, trnL-CAA, trnN-GUU, trnR-ACG, trnV-GAC* → 14 genes duplicated → 2 copies each |
| Other notable features | • *rps12* is trans-spliced (exon 1 in LSC; exons 2–3 in IR)<br>• *ycf2* present as single copy only — IR shorter than in most angiosperms<br>• Genome structure: LSC = 99,259 bp; SSC = 22,267 bp; IR = 17,732 bp each<br>• GC pattern: IR > LSC > SSC<br>• No explicit `repeat_region` labels in MN443423.1; sizes from Yang et al. (2021) |

---

## 7. Identified Gene Groups

| Gene Group | Genes in *Ginkgo biloba* MN443423.1 |
|---|---|
| Photosystem I (*psa*) | *psaA, psaB, psaC, psaI, psaJ, ycf3, ycf4* (7) |
| Photosystem II (*psb*) | *psbA, psbB, psbC, psbD, psbE, psbF, psbH, psbI, psbJ, psbK, psbL, psbM, psbN, psbT, psbZ* (15) |
| ATP synthase (*atp*) | *atpA, atpB, atpE, atpF, atpH, atpI* (6) |
| Cytochrome b₆/f complex (*pet*) | *petA, petB, petD, petG, petL, petN* (6) |
| Rubisco large subunit | *rbcL* (present) |
| RNA polymerase (*rpo*) | *rpoA, rpoB, rpoC1, rpoC2* (4) |
| Ribosomal proteins — large subunit (*rpl*) | *rpl2, rpl14, rpl16, rpl20, rpl22, rpl32, rpl33, rpl36* (8) |
| Ribosomal proteins — small subunit (*rps*) | *rps2, rps3, rps4, rps7, rps8, rps11, rps12, rps14, rps15, rps16, rps18, rps19* (12) |
| rRNA (*rrn*) | *rrn16, rrn23, rrn4.5, rrn5* (each in 2 IR copies = 8 total) |
| tRNA (*trn*) | 41 total; includes *trnK-UUU, trnL-UAA, trnV-UAC* with introns; 6 duplicated in IR |
| Other conserved genes | *matK, clpP, accD, cemA, ycf1, ycf2* |

---

## 9. Plastid vs Mitochondrial Genome Comparison

| Feature | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| Cellular location | Plastids | Mitochondria |
| Main biological functions | Photosynthesis genes, plastid transcription and translation | Respiration (oxidative phosphorylation), mitochondrial translation |
| Typical genome organization | Circular map with LSC, SSC and two IR copies (156,990 bp in *G. biloba*) | Highly variable; often a master circle plus smaller subgenomic molecules |
| Relative genome size | Small: ~120–170 kb (156,990 bp here) | Larger and highly variable in plants: ~200 kb to several Mb |
| Gene content | 137 gene entries (116 unique here); ~110–130 typical | ~50–60 genes in angiosperms |
| Copy number | Very high per cell (many plastids, many copies each) | Lower than plastid; varies by tissue |
| Inheritance | Mostly maternal in angiosperms; paternal in gymnosperms including *Ginkgo* | Mostly maternal; varies among lineages |
| Recombination / structural change | Low; gene order conserved; occasional IR expansion/contraction | High; frequent recombination between repeats and many rearrangements |
| Mutation / substitution pattern | Slow substitution rate; slower in IR | Very slow substitution rate overall, but fast structural change |
| Common research application | Phylogenetics, barcoding, conservation, transformation | Population studies, cytoplasmic male sterility, lineage tracing |
