# Plastid Genome Characterization: *Ginkgo biloba*

 **Student:** Jade Angela Suan

 **Course/Section:** Cell & Molecular Biology

 **Date:** 2026-09-30

 ---
## Choosing and Recording a Plant Genus
 | Item | Details |
 |---|---|
 | Selected Genus | *Ginkgo* |
 | Species | *Ginkgo biloba* |
 | Common Name | Maidenhair Tree |
 | Family | Ginkgoaceae |
 | Growth Form | Woody tree; long-lived gymnosperm |
 | Accession | MN443423.1 |
 | URL | https://www.ncbi.nlm.nih.gov/nuccore/MN443423.1 |
 | Rationale | *Ginkgo biloba* is a "living fossil" — the only surviving species in an ancient plant lineage, offering an interesting comparison to flowering plants. Its chloroplast genome is fully sequenced and publicly available on NCBI. |

 ![Figure 1: Retrieval of Ginkgo biloba in NCBI (MN443423.1)](/figures/ncbi_genbank_record.jpg)

*Figure 1.* Retrieval of *Ginkgo biloba* chloroplast complete genome in NCBI (Accession MN443423.1).

## Data Source and Genome Selection

| Item | Information |
|---|---|
| Accession | MN443423.1 |
| Organism | *Ginkgo biloba* |
| Family | Ginkgoaceae |
| Genome Length | 156,990 bp |
| Topology | Circular |
| GC Content | 39.56% |
| Database Source | NCBI Nucleotide (GenBank) |
| Direct Link | https://www.ncbi.nlm.nih.gov/nuccore/MN443423.1 |
| FASTA File | `Ginkgo_biloba_MN443423.1.fasta` |
| GenBank File | `Ginkgo_biloba_MN443423.1.gb` |
| Reference Publication | Yang, X., Zhou, T., Wang, G., et al. (2021). Structural characterization and comparative analysis of the chloroplast genome of *Ginkgo biloba* and other gymnosperms. *Journal of Forestry Research*, 32(2), 765–778. DOI: 10.1007/s11676-019-01088-4 |

![Figure 2 — NCBI FASTA Sequence Page](/figures/ncbi_fasta_sequence.jpg)
*Figure 2.* FASTA sequence download page for *Ginkgo biloba* chloroplast genome (MN443423.1). The FASTA-formatted sequence was downloaded from this page and uploaded to Galaxy for analysis.

## Galaxy Workflow

| Step | Information |
|---|---|
| Platform | Galaxy Project — https://usegalaxy.org |
| User Account | suan_jade |
| History Name | Plastid_Ginkgo_Suan |
| Uploaded File | `Ginkgo_biloba_MN443423.1.` |
| File Format | FASTA — verified |
| Tool Used | Fasta Statistics |
| Total Genome Length | 156,990 bp |
| Number of Sequence Records | 1 |
| GC Content Overall | 39.56% |
| Complete Plastome in Single Record | Yes |
| Gaps Detected | 0 |
| Base Counts | A = 46,855 &nbsp; T = 48,032 &nbsp; C = 31,611 &nbsp; G = 30,492 |

![Figure 3 — Galaxy Fasta Statistics Results](/figures/galaxy_fasta_statistics.jpg)
*Figure 3.* Galaxy Fasta Statistics output for *Ginkgo biloba* chloroplast genome. Confirms genome length = 156,990 bp, GC content = 39.56%, and one continuous sequence record with no gaps.

## Requiired Plastid Genome Characterization

| Feature | Information |
|---|---|
| **Species** | *Ginkgo biloba* |
| **Family** | Ginkgoaceae |
| **NCBI Accession** | MN443423.1 |
| **Total Plastome Size** | 156,990 bp |
| **Topology** | Circular — quadripartite structure |
| **LSC — Large Single Copy** | 88,923 bp |
| **SSC — Small Single Copy** | 18,261 bp |
| **IR — Inverted Repeat (each)** | 24,903 bp |
| **GC Content** | 39.56% |
| **Total Annotated Genes** | 135 |
| Protein‑coding genes | 86 |
| tRNA genes | 41 |
| rRNA genes | 8 |
| **Genes with Introns** | 15 distinct genes |
|  — with 2 introns | 3 genes: *rps12, clpP, ycf3* |
|  — with 1 intron | 12 genes: *atpF, rpoC1, petB, petD, ndhB, ndhA, trnK‑UUU, trnL‑UAA, trnV‑UAC, trnG‑UCC, trnI‑GAU, trnA‑UGC* |
| **Pseudogenes** | None confirmed |
| **Duplicated Genes (in IR)** | 14 genes |

### Notable Features
- Quadripartite architecture: **LSC – IRa – SSC – IRb**
- ***rps12* is trans‑spliced**: 5' exon located in LSC; exons 2–3 in both IR regions
- IR regions are shorter (~24,903 bp each) compared to most flowering plants → *ycf2* occurs as a **single copy**
- *Ginkgo biloba* is a gymnosperm "living fossil" — phylogenetically distinct from angiosperms
- No confirmed pseudogenes
- Gene order is conserved and typical of gymnosperm plastomes

## Gene Content Overview

| Functional Group | Gene Names | Number |
|---|---|---|
| **Photosystem I** | *psaA, psaB, psaC, psaI, psaJ, ycf3, ycf4* | 7 |
| **Photosystem II** | *psbA, psbB, psbC, psbD, psbE, psbF, psbH, psbI, psbJ, psbK, psbL, psbM, psbN, psbT, psbZ* | 15 |
| **ATP Synthase** | *atpA, atpB, atpE, atpF, atpH, atpI* | 6 |
| **Cytochrome b₆/f Complex** | *petA, petB, petD, petG, petL, petN* | 6 |
| **Carbon Fixation** | *rbcL* | 1 |
| **NADH Dehydrogenase** | *ndhA, ndhB, ndhC, ndhD, ndhE, ndhF, ndhG, ndhH, ndhI, ndhJ, ndhK* | 11 |
| **RNA Polymerase** | *rpoA, rpoB, rpoC1, rpoC2* | 4 |
| **Ribosomal Proteins (Large Subunit — rpl)** | *rpl2, rpl14, rpl16, rpl20, rpl22, rpl32, rpl33, rpl36* | 8 |
| **Ribosomal Proteins (Small Subunit — rps)** | *rps2, rps3, rps4, rps7, rps8, rps11, rps12, rps14, rps15, rps16, rps18, rps19* | 12 |
| **Ribosomal RNA** | *rrn16, rrn23, rrn4.5, rrn5* — 2 copies each in IR | 8 total |
| **Transfer RNA** | *trnA‑UGC, trnC‑GCA, trnD‑GUC, trnE‑UUC, trnF‑GAA, trnG‑GCC, trnG‑UCC, trnH‑GUG, trnI‑CAU, trnI‑GAU, trnK‑UUU, trnL‑CAA, trnL‑UAA, trnL‑UAG, trnM‑CAU, trnN‑GUU, trnP‑UGG, trnQ‑UUG, trnR‑ACG, trnR‑UCU, trnS‑GCU, trnS‑GGA, trnS‑UGA, trnT‑GGU, trnT‑UGU, trnV‑GAC, trnV‑UAC, trnW‑CCA, trnY‑GUA* (+ duplicates in IR) | 41 total |
| **Other Conserved Genes** | *matK, clpP, accD, cemA, ycf1, ycf2* | 6 |

### Summary Counts

| Category | Unique Genes | Total Copies (incl. IR duplicates) |
|---|---|---|
| Protein‑coding | 86 | 100 |
| tRNA | 35 | 41 |
| rRNA | 4 | 8 |
| **Total** | **125 unique** | **135 annotated** |

### Notes
- **14 genes appear twice** due to location within Inverted Repeat regions
- ***rps12* is trans‑spliced**: exon 1 in LSC; exons 2–3 in both IR regions
- Genes with introns are marked in the Plastome Summary section
- No *ycf2* duplication — IR length shorter than in most flowering plants

## Questions for the Student Report
 ### 1. Full Organism & Genome Information
 | Item | Details |
 |---|---|
 | Full Scientific Name | *Ginkgo biloba* |
 | Family | Ginkgoaceae |
 | NCBI Accession / Version | MN443423.1 |
 | Database Source | NCBI GenBank (Nucleotide database) |
 | Complete Plastid Genome Size | 156,990 bp |
 | Direct Link | https://www.ncbi.nlm.nih.gov/nuccore/MN443423.1 |
 ---

### 2. Evidence for Complete Plastid Genome
 Three key confirmations:
 - **Length matches known range**: 156,990 bp falls within typical plant plastome range (~120–170 kb), far larger than DNA barcode markers (~600 bp) or gene fragments.
 - **Quadripartite structure present**: LSC (88,923 bp) + IRa (24,903 bp) + SSC (18,261 bp) + IRb (24,903 bp) — the hallmark architecture of a complete chloroplast genome.
 - **Full gene complement annotated**: 135 total genes including photosystem, ATP synthase, ribosomal, rRNA, and tRNA genes — not a partial or nuclear sequence.
 - **Galaxy verification**: Single continuous record with 0 gaps confirms no fragmentation.
 ---
 ### 3. Genome Organization & Region Sizes
 - **Overall organization**: Circular, double‑stranded DNA with **quadripartite** architecture — Large Single Copy → Inverted Repeat a → Small Single Copy → Inverted Repeat b.
 - **LSC–IR–SSC–IR arrangement**: Present — the standard land plant plastome structure.
 - **Region sizes**:
   | Region | Size |
   |---|---|
   | LSC — Large Single Copy | 88,923 bp |
   | IR — Inverted Repeat (each copy) | 24,903 bp |
   | SSC — Small Single Copy | 18,261 bp |
   | Total | 156,990 bp |
 ---
 ### 4. Annotated Gene Content & IR Duplication
 | Category | Count |
 |---|---|
 | **Total annotated genes** | 135 |
 | Protein‑coding genes | 86 |
 | tRNA genes | 41 |
 | rRNA genes | 8 |
 | Pseudogenes | None confirmed |

 **Why IR genes appear in two copies**: The Inverted Repeat regions (IRa and IRb) have **identical DNA sequences** oriented in opposite directions. Any gene located within these regions is automatically present **twice** — once in IRa and once in IRb — giving two identical functional copies in the full genome sequence.

 ---
 ### 5. Eight Protein‑Coding Genes — Different Functional Groups
 | Gene | Functional Group | Biological Function |
 |---|---|---|
 | *psaA* | Photosystem I | Core reaction center protein; binds chlorophyll → light energy capture |
 | *psbA* | Photosystem II | D1 protein; binds cofactors → primary target of herbicides |
 | *atpB* | ATP Synthase | Beta subunit; forms catalytic site → ATP production |
 | *petA* | Cytochrome b₆/f | Cytochrome f → electron transport chain |
 | *rbcL* | Carbon Fixation | Large subunit of Rubisco → CO₂ fixation in Calvin cycle |
 | *ndhF* | NADH Dehydrogenase | Subunit F → cyclic electron flow & stress response |
 | *rpoB* | RNA Polymerase | Beta subunit → transcribes plastid genes |
 | *rps12* | Ribosomal Protein (small subunit) | Component of 30S ribosome → protein synthesis; *trans‑spliced* |
 ---
 ### 6. RNA Features & Intron‑Containing Genes
 **rRNA Genes**: *rrn16, rrn23, rrn4.5, rrn5* — each present in 2 copies in IR → 8 total; form ribosome structural core.
 **tRNA Examples**:
 - *trnK‑UUU* — carries lysine; **contains intron** → matK gene nested within its intron
 - *trnL‑UAA* — carries leucine; classic group I intron
 - *trnA‑UGC* — carries alanine; duplicated in IR
 **Genes with Introns**:
 - **Two introns**: *rps12, clpP, ycf3*
 - **One intron**: *atpF, rpoC1, petB, petD, ndhB, ndhA, trnK‑UUU, trnL‑UAA, trnV‑UAC, trnG‑UCC, trnI‑GAU, trnA‑UGC*
 - *rps12* is special: **trans‑spliced** — exon 1 in LSC; exons 2–3 in both IR regions
 ---
 ### 7. Pseudogenes, Losses, Duplications & Unusual Features
 | Feature | Observation |
 |---|---|
 | **Pseudogenes** | None reported / confirmed |
 | **Gene losses** | No gene losses detected — full typical complement present |
 | **Duplications** | 14 genes duplicated in IR regions → appear twice |
 | **Rearrangements** | None reported — gene order conserved, typical of gymnosperms |
 | **Unusual features** | 1. *rps12* trans‑splicing<br>2. Shorter IR (~24,903 bp) → *ycf2* present as **single copy** (duplicated in most angiosperms)<br>3. *Ginkgo* is gymnosperm → plastid inheritance is **paternal** (maternal in most flowering plants) |
 ---
 ### 8. GC Content & Notable Observations
 - **GC Content**: 39.56% (from Galaxy Fasta Statistics)
 - **Two other notable observations**:
   1. **Base composition bias**: A+T rich (60.44%) — common in plastid genomes; IR regions have slightly higher GC (~42%) than single‑copy regions → IR more structurally stable.
   2. **Sequence continuity**: Galaxy shows **1 single record, 0 gaps** → fully assembled; no Ns or ambiguous bases confirm high‑quality sequence.
 ---

### 9. Compare Plastid and Mitochondrial Genomes

#### A. Five Differences

| Category | Plastid Genome | Mitochondrial Genome |
|---|---|---|
| **Location** | Chloroplast organelles | Mitochondrial organelles |
| **Biological role** | Photosynthesis; synthesis of chloroplast proteins & RNAs | Cellular respiration; ATP production via oxidative phosphorylation |
| **Genome organization** | Circular; conserved quadripartite structure (LSC–IR–SSC–IR) | Highly variable; master circle + subgenomic molecules; frequent rearrangements |
| **Gene content** | ~110–130 unique genes (135 total in *Ginkgo*); includes photosystem, rbcL, rpo, full tRNA/rRNA sets | ~50–60 unique genes; mostly respiratory chain subunits; reduced tRNA set |
| **Copy number** | Very high — hundreds of copies per cell | Lower — varies by tissue, generally fewer than plastids |
| **Inheritance** | Paternal in *Ginkgo* and most gymnosperms | Mostly maternal in plants |
| **Evolutionary behavior** | Slow sequence evolution; gene order highly conserved | Slow sequence evolution but rapid structural changes; frequent gene loss/gain |

#### B. Five Similarities

| # | Similarity |
|---|---|
| 1 | Both are **double‑stranded circular DNA** molecules — not linear like nuclear chromosomes |
| 2 | Both originated through **endosymbiosis** from ancient bacteria; retain their own independent genomes |
| 3 | Both possess **complete transcription and translation machinery** — rRNA, tRNA, ribosomal protein genes |
| 4 | Both are **cytoplasmically inherited** — not through nuclear chromosomes; uniparental in most plants |
| 5 | Both have **higher copy number than nuclear DNA** — easier to isolate, amplify, and sequence from small/old samples |
| 6 | Both encode **hydrophobic membrane proteins** — core energy‑processing complexes (photosynthesis / respiration) |

 ---
 
 ### 10. Practical Value of Plastid Genomes in Research — Advantages vs Nuclear Genome
 #### Advantages of Plastid Genomes
 | Advantage | Explanation |
 |---|---|
 | **High copy number** | Hundreds of copies per cell → easy to isolate, amplify, and sequence even from small, degraded, or ancient samples; works well with herbarium specimens or fossil material |
 | **Conserved structure & sequence** | Slow evolution → easy to align across distant species; excellent for resolving deep evolutionary relationships |
 | **Haploid & non‑recombining** | No sexual recombination → simpler lineage tracing; clearer phylogeographic patterns |
 | **No sex chromosomes** | Same data from all individuals → no bias between males/females; consistent results across samples |
 | **Small genome size** | Cheaper & faster to sequence than nuclear genomes; manageable data volume for analysis |
 | **Maternally or paternally inherited** | Tracks single parent lineage → useful for gene flow, dispersal, and biogeography studies |
 #### Limitations
 - Represents only **one parental lineage** — cannot capture full biparental genetic history
 - Few genes → limited resolution for **very closely related** species or populations
 - Cannot study **nuclear genes, adaptive traits, sex‑linked characteristics, or most recent evolutionary changes**
 - Limited functional information compared to the nuclear genome
 #### Research Question Examples
 | Data Type | Research Question |
 |---|---|
 | **Plastid data** | *What is the evolutionary position of Ginkgo biloba among all seed plants?* → conserved plastid genes resolve deep phylogenetic branches |
 | **Nuclear data** | *Do Ginkgo populations show adaptive genetic differences across temperature and rainfall zones?* → nuclear SNPs reveal recent adaptation, population structure, and local selection |

 ### 10. Plastid vs Mitochondrial Genome Comparison
 | Feature | Plastid Genome | Mitochondrial Genome |
 |---|---|---|
 | **Cellular location** | Chloroplasts | Mitochondria |
 | **Main biological functions** | Photosynthesis; plastid transcription & translation; synthesis of photosynthetic proteins | Cellular respiration (oxidative phosphorylation); ATP production; energy metabolism |
 | **Typical genome organization** | Circular; conserved quadripartite structure — LSC–IRa–SSC–IRb | Highly variable; master circle + subgenomic molecules; frequent structural rearrangements |
 | **Relative genome size** | ~120–170 kb; *Ginkgo* = **156,990 bp** | ~200 kb to >2 Mb in plants — generally much larger |
 | **Gene content** | ~110–130 unique genes; 135 total annotated in *Ginkgo* — photosystem, ATP synthase, rRNA, tRNA, ribosomal proteins | ~50–60 unique genes — respiratory subunits; reduced tRNA set; many genes lost or transferred to nucleus |
 | **Copy number** | Very high — hundreds per cell; easy to extract & amplify | Lower — varies by tissue; generally fewer copies |
 | **Inheritance** | Paternal in *Ginkgo* and most gymnosperms | Mostly maternal in plants |
 | **Recombination / structural change** | Low; IR regions stabilize genome; gene order highly conserved | High; frequent recombination between repeats; rapid structural rearrangements |
 | **Mutation / substitution pattern** | Slow sequence evolution; IR regions evolve even slower | Slow sequence evolution but fast structural change; different substitution rates per lineage |
 | **Common research applications** | DNA barcoding, phylogenetics, species identification, deep evolutionary relationships, conservation genetics, transgenic engineering | Population genetics, cytoplasmic male sterility, maternal lineage tracing, phylogenetic studies at family/genus level |

 ## References

1. Yang, X., Zhou, T., Wang, G., Su, X., Zhang, X., Guo, Q., & Cao, F. (2021). Structural characterization and comparative analysis of the chloroplast genome of *Ginkgo biloba* and other gymnosperms. *Journal of Forestry Research*, 32(2), 765–778.  
   https://doi.org/10.1007/s11676-019-01088-4

2. National Center for Biotechnology Information (NCBI). *Ginkgo biloba* chloroplast, complete genome. GenBank: MN443423.1.  
   https://www.ncbi.nlm.nih.gov/nuccore/MN443423.1

3. Galaxy Link: https://usegalaxy.org/u/suan_jade/h/plastid-ginkgo-suan
   

4. Github Link: 
