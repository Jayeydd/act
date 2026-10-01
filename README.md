# Plastid Genome Characterization: *Ginkgo biloba*

**Student:** Jade Angela Suan

**Course/Section:** Cell & Molecular Biology - Section B

**Date:** 2026-09-30

**This repository documents my lab activity on the complete plastid (chloroplast) genome of *Ginkgo biloba*: where the genome came from, what I did in Galaxy, what I found, and how I interpreted it**.

## Genome Source
- **Genus:** *Ginkgo*
- **Species:** *Ginkgo biloba*
- **Family:** Ginkgoaceae
- **NCBI Accession:** MN443423.1
- **Source:** https://www.ncbi.nlm.nih.gov/nuccore/MN443423.1
- **Retrieved:** 2026-09-30
- **Reference:** Yang, X., Zhou, T., Wang, G., Zhang, X., Guo, Q., & Cao, F. (2021). Structural characterization and comparative analysis of the chloroplast genome of Ginkgo biloba and other gymnosperms. Journal of Forestry Research, 32(2), 765–778. DOI: 10.1007/s11676-019-01088-4 

## Plastid Genome Summary

| Feature | Information |
|---|---|
| **Species** | *Ginkgo biloba* |
| **Family** | Ginkgoaceae |
| **NCBI Accession** | MN443423.1 |
| **Total Plastome Size** | 156,990 bp |
| **Topology** | Circular, quadripartite structure |
| **LSC — Large Single Copy** | 99, 259 bp |
| **SSC — Small Single Copy** | 22, 267 bp |
| **IR — Inverted Repeat (each)** | 17,732 bp |
| **GC Content** | 39.56% |
| **Total Annotated Genes** | 134 |
| Protein‑coding genes | 85 |
| tRNA genes | 41 |
| rRNA genes | 8 |
| **Genes with Introns** | 16 distinct genes |
|  — with 2 introns | 3 genes: *rps12, clpP, ycf3* |
|  — with 1 intron | 13 genes: *atpF, rpoC1, petB, petD, ndhB, ndhA, trnK‑UUU, trnL‑UAA, trnV‑UAC, trnG‑UCC, trnI‑GAU, trnA‑UGC* |
| **Pseudogenes** | 	None flagged in the record; *rpl23* is truncated |
| **Duplicated Genes (in IR)** | the IR	13 (4 rRNA, 6 tRNA, and the protein-coding genes *rps7, ndhB and rps12*) |

### Notable Features
- The genome has the usual LSC–IRa–SSC–IRb layout.
- *rps12* is trans-spliced. Its first exon is in the LSC and exons 2 and 3 are in the IR.
- The IRs are about 17.7 kb each, shorter than the roughly 25 kb seen in many flowering plants. *ycf2* occurs once (92549..99088), inside the LSC.
- *rpl23* is annotated as a CDS of only 81 bp (90448..90528), which is far shorter than a normal *rpl23.*
- The record has no pseudo or repeat_region features.

 ---

## Galaxy Workflow

**Account:** https://usegalaxy.org/u/suan_jade/h/plastid-ginkgo-suan

**History Name:** Plastid_Ginkgo_Suan

**Tool Used:** Fasta Statistics

**Date:** 2026-09-30

---

### Step 1 — Download Sequence from NCBI
1. Go to: https://www.ncbi.nlm.nih.gov/nuccore/MN443423.1
2. Click **FASTA** tab → Download → Save as:
   `Ginkgo_biloba_MN443423.1.fasta`

### Step 2 — Log In & Create History
1. Sign in to https://usegalaxy.org
2. Click **+ New History** → Name it:
   `Plastid_Ginkgo_Suan`

### Step 3 — Upload FASTA File
1. Click **Upload Data** 
2. Click **Choose Local File**
3. Click **Start** → wait until dataset turns **green** 
4. Rename dataset :
   `Ginkgo_biloba_MN443423.1`

### Step 4 — Run Fasta Statistics
1. In left tool panel search box, type: `Fasta Statistics`
2. Select **Fasta Statistics display summary statistics**
3. Input FASTA file: → select your uploaded dataset
4. Click **Run Tool** 
5. New dataset appears: `Fasta Statistics on dataset 1: summary stats`

### Step 5 — View & Record Results
From the **Preview** panel:
| Metric | Value |
|---|---|
| Total length | 156,990 bp |
| Number of sequences | 1 |
| GC content | 39.56% |
| Scaffold num_A | 46,855 |
| Scaffold num_T | 48,032 |
| Scaffold num_C | 31,611 |
| Scaffold num_G | 30,492 |
| Scaffold num_N | 0 |

### Step 6 — Save Screenshot
- Capture full screen showing:
  - History name: `Plastid_Ginkgo_Suan`
  - Renamed FASTA file 
  - Fasta Statistics results table 
- Save as: `galaxy_fasta_ statistics.jpg` → place in `figures/` folder

### Step 7 — Verify
-  Length matches NCBI: 156,990 bp
-  Single record = complete genome (not fragmented)
-  N = 0 = high-quality sequence
-  GC = 39.56% consistent with land-plant plastomes

---

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
| **Ribosomal Proteins (Large Subunit — rpl)** | *rpl2, rpl14, rpl16, rpl20, rpl22, rpl23 (truncated), rpl32, rpl33, rpl36* | 9 |
| **Ribosomal Proteins (Small Subunit — rps)** | *rps2, rps3, rps4, rps7, rps8, rps11, rps12, rps14, rps15, rps16, rps18, rps19* | 12 |
| **Ribosomal RNA** | *rrn16, rrn23, rrn4.5, rrn5* — 2 copies each in IR | 8 total |
| **Transfer RNA** | *trnA-UGC, trnC-GCA, trnD-GUC, trnE-UUC, trnF-GAA, trnG-GCC, trnG-UCC, trnH-GUG, trnI-CAU, trnI-GAU, trnK-UUU, trnL-CAA, trnL-UAA, trnL-UAG, trnM-CAU, trnN-GUU, trnP-UGG, trnQ-UUG, trnR-ACG, trnR-UCU, trnS-GCU, trnS-GGA, trnS-UGA, trnT-GGU, trnT-UGU, trnV-GAC, trnV-UAC, trnW-CCA, trnY-GUA* (six of them are also copied in the IR) | 41 total |
| **Other Conserved Genes** | *matK, clpP, accD, cemA, ycf1, ycf2* | 6 |

## Key Observations
 - The inverted repeat (IR) regions are short at ~17.7 kb each — shorter than in most flowering plants — and *ycf2* occurs only once, inside the LSC.
 - Thirteen genes sit in the IR and appear duplicated: 4 rRNA, 6 tRNA, plus *rps7*, *ndhB*, and *rps12*.
 - *rps12* is trans‑spliced: its first exon lies in the LSC, while exons 2 and 3 are in both IRs.
 - Several genes contain introns: *clpP* and *ycf3* each have two, and *atpF*, *petB*, *rpl2*, *trnK‑UUU*, *trnL‑UAA*, and *trnV‑UAC* each have one.
 - *rpl23* is notably truncated — annotated at only 81 bp — suggesting it may be a pseudogene.
 - The genome is complete and AT‑rich: GC = 39.56%, and Galaxy returned one continuous sequence with **no ambiguous N bases**.

## Data Sources & References

1. National Center for Biotechnology Information (NCBI). *Ginkgo biloba* chloroplast, complete genome. GenBank: MN443423.1.
   https://www.ncbi.nlm.nih.gov/nuccore/MN443423.1

2. The complete plastid genome provides insight into maternal plastid inheritance mode of the living fossil plant *Ginkgo biloba. Plant Diversity.*
   https://pmc.ncbi.nlm.nih.gov/articles/PMC10772217
  
3. Yang, X., Zhou, T., Wang, G., Su, X., Zhang, X., Guo, Q., & Cao, F. (2021). Structural characterization and comparative analysis of the chloroplast genome of *Ginkgo biloba* and other gymnosperms. *Journal of Forestry Research*, 32(2), 765–778.  
   https://doi.org/10.1007/s11676-019-01088-4

4. Galaxy History: https://usegalaxy.org/u/suan_jade/h/plastid-ginkgo-suan
   
5. Github Repository: https://github.com/Jayeydd/cmb-plastid-genome-Ginkgo-Suan

----

## Reproducibility — How to Repeat This Analysis

Another student can reproduce this work exactly by following these steps:

1. Go to NCBI Nucleotide → search for **"Ginkgo biloba chloroplast complete genome"** or directly use accession **MN443423.1** → download the FASTA file
2. Sign in to https://usegalaxy.org/ → create a new history named: **Plastid_Ginkgo_Suan**
3. Upload the FASTA file → rename it to: `Ginkgo_biloba_MN443423.1.fasta`
4. Run **Fasta Statistics** → record genome length, GC%, and number of sequences
   - Expected: Length = 156,990 bp; GC = 39.56%; Sequences = 1; Ambiguous bases = 0
5. Open the NCBI GenBank "Features" table → extract gene counts, intron positions, and coordinates
6. Use published boundary values: LSC = 88, 923 bp; SSC = 18, 261 bp; IR = 24, 903 bp each
7. Compile tables following the lab report template
8. Create GitHub repository with the folder structure below and document your workflow


