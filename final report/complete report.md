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
 | Rationale | *Ginkgo biloba* is a "living fossil", the only surviving species in an ancient plant lineage, offering an interesting comparison to flowering plants. Its chloroplast genome is fully sequenced and publicly available on NCBI. |

 ![Figure 1: GenBank record of the Ginkgo biloba chloroplast complete genome (MN443423.1) in NCBI Nucleotide.](/figures/ncbi_genbank_record.jpg)

*Figure 1.* GenBank record of the Ginkgo biloba chloroplast complete genome (MN443423.1) in NCBI Nucleotide.

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
*Figure 2.* FASTA page for MN443423.1 in NCBI. I downloaded the sequence from this page and uploaded it to Galaxy.

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
*Figure 3.* Galaxy history and Fasta Statistics output for MN443423.1: length 156,990 bp, one sequence, GC 39.56%, no N bases.

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

## Questions for the Student Report

 ### 1. Organism and genome information

The organism is *Ginkgo biloba* (maidenhair tree), family Ginkgoaceae. I used the GenBank record MN443423.1 from the NCBI Nucleotide database. The complete plastid genome is 156,990 bp.

### 2. Evidence that this is a complete plastid genome

The record is titled "Ginkgo biloba chloroplast, complete genome" and is listed as circular. At 156,990 bp it falls in the normal plastome range (about 120 to 170 kb) and is far longer than a barcode such as *rbcL or matK.* It is annotated with typical plastid genes such as *psaA, psbA and rbcL*, which a nuclear sequence would not carry. In Galaxy, Fasta Statistics gave one sequence record (num_seq = 1) with no N bases, so the file is a single continuous sequence and not a set of fragments. The publication describes it as the complete chloroplast genome of Ginkgo biloba.

 ### 3. Genome organization

The genome has the usual LSC–IRa–SSC–IRb arrangement. According to Yang et al. (2021), the LSC is 99,259 bp, the SSC is 22,267 bp, and each IR is 17,732 bp. Together, 99,259 + 22,267 + 17,732 + 17,732 = 156,990 bp, which matches the genome length. The IRs are shorter than in most flowering plants, which fits the IR contraction described for *Ginkgo*. An earlier study linked this contraction to the loss of one *ycf2* copy from the IR.

  ### 4. Gene content and IR duplication

The record has 134 annotated genes: 85 protein-coding, 41 tRNA and 8 rRNA genes (IR copies counted), which matches the counts reported by Yang et al. (2021). The record does not flag any pseudogenes, although *rpl23* is truncated. Some genes appear twice because IRa and IRb are two copies of the same sequence, so a gene inside the IR is annotated once in each copy. This applies to the four rRNA genes, six tRNA genes, and the protein-coding genes *rps7, ndhB and rps12*.

  ### 5. Eight protein-coding genes from different functional groups

1. ***psaA*** (Photosystem I): codes for a core protein of Photosystem I, which holds the chlorophyll and electron carriers that capture light energy.

2. ***psbA*** (Photosystem II): codes for the D1 protein of the Photosystem II reaction center. It binds the cofactors used in the first charge separation and is replaced often because light damages it.

3. ***atpB*** (ATP synthase): codes for the beta subunit of ATP synthase, which is part of the catalytic site that makes ATP from the proton gradient.

4. ***petA*** (cytochrome b6/f): codes for cytochrome f, part of the complex that passes electrons between Photosystem II and Photosystem I.

5. ***rbcL*** (carbon fixation): codes for the large subunit of Rubisco, the enzyme that fixes CO2 in the Calvin cycle.

6. ***ndhF*** (NADH dehydrogenase-like complex): codes for a subunit of the complex involved in cyclic electron flow around Photosystem I.

7. ***rpoB*** (RNA polymerase): codes for the beta subunit of the plastid-encoded RNA polymerase, which transcribes plastid genes.

8. ***rps12*** (small ribosomal subunit): codes for ribosomal protein S12, needed for plastid translation. Its transcript is trans-spliced.

 ### 6. RNA genes and RNA-processing features
 The rRNA genes are *rrn16, rrn23, rrn4.5*, and *rrn5*, and they sit in the IR, so there are two copies of each. For tRNAs, *trnK-UUU* carries lysine and has an intron that contains matK. *trnL-UA*A carries leucine, and its intron is a group I intron. Also *trnA-UGC* carries alanine.Genes with introns include *clpP* and *ycf3*, which each have two introns, and *atpF* and *petB*, which have one. *rps12* is trans-spliced: its first exon is in the LSC and its other exons are in the IR.

 ### 7. Pseudogenes, gene losses, duplications and other unusual features
 The GenBank record does not flag any pseudogenes. However, *rpl23* is annotated as a CDS of only 81 bp (90448..90528) that codes for 26 amino acids, much shorter than a normal *rpl23*. An earlier study of the *Ginkgo* plastome described a truncated Ψ*rpl23*, so I think it is a degraded copy even though this record does not label it that way. The main duplications are the genes in the IR, listed in Question 4. The most unusual features are the short IRs (17,732 bp) with *ycf2* present only once, inside the LSC, and the trans-spliced *rps12*. Yang et al. (2021) also connect the shorter IRs to *ycf2*. The record itself does not describe any rearrangements.

 ### 8. GC content and other observations
 The GC content is 39.56%. From the Galaxy base counts (A = 46,855, T = 48,032, C = 31,611, G = 30,492), the genome is about 60.4% A+T. Two other observations:
 - The whole genome is one sequence record with no N bases, so there are no gaps or ambiguous positions.
 - The IRs are only about 17.7 kb, shorter than the roughly 25 kb of many flowering plants, and *ycf2* is present as a single copy in the LSC.

 ### 9. Plastid and mitochondrial genomes

**Five similarities**

1. Both come from bacteria that were taken in by endosymbiosis.
2. Both are small compared with the genomes of their free-living ancestors, because many genes moved to the nucleus.
3. Both code for part of their own translation machinery, such as rRNAs and ribosomal proteins.
4. Both code for subunits of membrane protein complexes that make energy.
5. Both are usually inherited from one parent and exist in many copies per cell.

**Five differences**

1. Plastids do photosynthesis and carbon fixation, and mitochondria do respiration and ATP synthesis.
2. Plastomes are similar in size across plants (about 120 to 170 kb), while plant mitochondrial genomes range from about 200 kb to several Mb.
3. Plastomes usually have one circular map with the LSC–IR–SSC–IR layout, while plant mitochondrial genomes are often a master circle with smaller circular and linear subgenomic forms.
4. Plastomes carry about 110 to 130 densely packed genes, while plant mitochondrial genomes carry about 50 to 60 genes spread over much larger non-coding regions.
5. Plastid sequences usually change faster at the nucleotide level than plant mitochondrial ones, but their structure changes much less. Plant mitochondria show the opposite pattern and also have more RNA editing.

Inheritance is not a clear difference in *Ginkgo*. A study using this same genome supports **maternal inheritance** of its plastids, unlike many other gymnosperms, and suggests the mitochondria may also be maternal.

### 10. Practical value of plastid genomes

**Advantages compared with the nuclear genome:**

- There are many copies per cell, so plastid DNA is easy to recover even from old or poor-quality samples such as herbarium specimens.
- The genome is small, so sequencing and assembly are cheaper.
- Gene content and order are conserved, so plastomes are easy to align between species.
- Plastomes mostly do not recombine and are usually inherited from one parent, so lineages are easier to follow.
- They are the same in male and female individuals. *Ginkgo* has separate male and female trees, and nuclear sex chromosomes usually recombine less and are present in different numbers in the two sexes, which complicates analysis.
- A small amount of plastid sequence carries a lot of phylogenetic information.

**Limitations:**

- A plastome shows only one parent's lineage.
- It has few genes, so it may not separate very close relatives.
- It says little about adaptation or traits controlled by nuclear genes.
- A plastome tree can disagree with the species tree if there has been hybridization or chloroplast capture.

**A question for plastid data:**
Where does *Ginkgo biloba* fall among the living seed plants? Plastid genes are conserved enough to align across very distant groups, so a plastome is a useful starting point. For example, Yang et al. (2021) used plastomes to place *Ginkgo* as sister to the cycads rather than to gnetophytes, cupressophytes or Pinaceae.

**A question for nuclear data:**
Do *Ginkgo* populations from warmer or wetter areas differ genetically from those in cooler or drier areas? Nuclear SNPs from many genes can show population structure and possible local adaptation. A plastome cannot, since it is inherited from one parent and acts as a single locus.

## Plastid vs Mitochondrial Genome Comparison

| Feature | Plastid genome | Mitochondrial genome |
|---|---|---|
| Cellular location | Chloroplasts (plastids) | Mitochondria |
| Main biological functions | Photosynthesis, plus plastid transcription and translation | Cellular respiration (oxidative phosphorylation) and ATP production |
| Typical genome organization | Circular map with LSC, SSC and two IR copies | Highly variable; often a master circle plus smaller subgenomic molecules |
| Relative genome size | About 120 to 170 kb; 156,990 bp in *Ginkgo* | About 200 kb to over 2 Mb in plants, generally much larger |
| Gene content | About 110 to 130 unique genes in most land plants; 134 annotated in *Ginkgo* MN443423.1 (IR copies counted) | About 50 to 60 genes, mostly respiratory subunits, with a reduced tRNA set |
| Copy number | Very high; many plastids per cell and many genome copies per plastid | Lower than plastid; varies by tissue |
| Inheritance | Maternal in *Ginkgo* [3] and in most flowering plants; conifers are often paternal | Mostly maternal in plants |
| Recombination / structural change | Low; gene order is usually conserved, with occasional IR expansion or contraction | High; frequent recombination between repeats and many rearrangements |
| Mutation / substitution pattern | Low nucleotide substitution rate, lower still in the IR | Even lower nucleotide change, but fast structural change and more RNA editing |
| Common research applications | Phylogenetics, DNA barcoding, species identification, conservation genetics, plastid transformation | Cytoplasmic male sterility, maternal lineage tracing; used less for plant phylogenetics because of rearrangements and slow sequence change |

 ## References

1. National Center for Biotechnology Information (NCBI). *Ginkgo biloba* chloroplast, complete genome. GenBank: MN443423.1.
   https://www.ncbi.nlm.nih.gov/nuccore/MN443423.1

2. The complete plastid genome provides insight into maternal plastid inheritance mode of the living fossil plant *Ginkgo biloba. Plant Diversity.*
   https://pmc.ncbi.nlm.nih.gov/articles/PMC10772217
  
3. Yang, X., Zhou, T., Wang, G., Su, X., Zhang, X., Guo, Q., & Cao, F. (2021). Structural characterization and comparative analysis of the chloroplast genome of *Ginkgo biloba* and other gymnosperms. *Journal of Forestry Research*, 32(2), 765–778.  
   https://doi.org/10.1007/s11676-019-01088-4

4. Galaxy History: https://usegalaxy.org/u/suan_jade/h/plastid-ginkgo-suan
   
5. Github Repository: https://github.com/Jayeydd/cmb-plastid-genome-Ginkgo-Suan
