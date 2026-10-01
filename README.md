# Plastid Genome Characterization: *Ginkgo biloba*

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
 | Total annotated genes | 135 |
 | Protein-coding genes | 86 |
 | tRNA genes | 41 |
 | rRNA genes | 8 |
 | Genes with introns | 15 | GenBank feature analysis |
 | Pseudogenes | None confirmed |
 | Duplicated genes | 14 (in IR regions) | 
### Notable Features
 - Typical quadripartite circular structure: LSC–IRa–SSC–IRb
 - *Ginkgo biloba* is a gymnosperm "living fossil," sister to cycads
 - IR regions are shorter (~17,732 bp each) than in most flowering plants —
   caused by partial *ycf2* loss; *ycf2* exists as a single copy only
 - ***rps12* is trans-spliced**: 5' exon in LSC, 3' exons in IR
 - 3 genes have **2 introns**: *rps12, clpP, ycf3*
 - Genes with single introns: *atpF, rpoC1, petB, petD, ndhB, trnK-UUU, trnL-UAA, trnV-UAC*
 - **14 genes duplicated** in IR:
   - rRNA: *rrn16, rrn23, rrn4.5, rrn5*
   - Protein-coding: *rps7, ndhB, rps12* (partial)
   - tRNA: *trnA-UGC, trnI-GAU, trnL-CAA, trnN-GUU, trnR-ACG, trnV-GAC*
 - No confirmed pseudogenes in MN443423.1
 - GC pattern: IR > LSC > SSC
 ---

## Galaxy Workflow

**Account:** https://usegalaxy.org/u/suan_jade/h/plastid-ginkgo-suan

**History Name:** Plastid_Ginkgo_Suan

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
- Save as: `galaxy_stats_MN443423.1.jpg` → place in `figures/` folder

### Step 7 — Verify
-  Length matches NCBI: 156,990 bp
-  Single record = complete genome (not fragmented)
-  N = 0 = high-quality sequence
-  GC = 39.56% consistent with land-plant plastomes

---

## Gene Content Overview

| Functional Group | Genes Present |
|---|---|
| Photosystem I (psa) | psaA, psaB, psaC, psaI, psaJ, ycf3, ycf4 (7) |
| Photosystem II (psb) | psbA, psbB, psbC, psbD, psbE, psbF, psbH, psbI, psbJ, psbK, psbL, psbM, psbN, psbT, psbZ (15) |
| ATP synthase (atp) | atpA, atpB, atpE, atpF, atpH, atpI (6) |
| Cytochrome b₆/f complex (pet) | petA, petB, petD, petG, petL, petN (6) |
| Carbon fixation | rbcL (present) |
| NADH dehydrogenase (ndh) | ndhA, ndhB, ndhC, ndhD, ndhE, ndhF, ndhG, ndhH, ndhI, ndhJ, ndhK (11) |
| RNA polymerase (rpo) | rpoA, rpoB, rpoC1, rpoC2 (4) |
| Ribosomal proteins (rpl) | rpl2, rpl14, rpl16, rpl20, rpl22, rpl32, rpl33, rpl36 (8) |
| Ribosomal proteins (rps) | rps2, rps3, rps4, rps7, rps8, rps11, rps12, rps14, rps15, rps16, rps18, rps19 (12) |
| rRNA (rrn) | rrn16, rrn23, rrn4.5S, rrn5S — 2 copies each in IR = 8 total |
| tRNA (trn) | 41 total; trnK-UUU, trnL-UAA, trnV-UAC contain introns; 6 duplicated in IR |
| Other genes | matK, clpP, accD, cemA, ycf1, ycf2 (single copy only) |

- rps12 is trans-spliced (exon 1 in LSC; exons 2–3 in IR)
- clpP and ycf3 each have 2 introns
- No confirmed pseudogenes in MN443423.1
- ycf2 present as single copy — IR shorter than in most angiosperms

## Data Sources & References

1. Yang, X., Zhou, T., Wang, G., Zhang, X., Guo, Q., & Cao, F. (2021). Chloroplast genome characterization and comparative analysis of the chloroplast genome of Ginkgo biloba and other gymnosperms. *Journal of Forestry Research*, 32(2), 765–778. https://doi.org/10.1007/s11676-019-01088-4

2. National Center for Biotechnology Information. (2020). *Ginkgo biloba* chloroplast, complete genome (MN443423.1) [Nucleotide sequence]. Retrieved September 30, 2026, from https://www.ncbi.nlm.nih.gov/nuccore/MN443423.1

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


