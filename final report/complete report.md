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
  1. The organism is *Ginkgo biloba* (maidenhair tree), family Ginkgoaceae. I used the GenBank record MN443423.1 from the NCBI Nucleotide database. The complete plastid genome is 156,990 bp. 

  2. The record is titled "chloroplast, complete genome," and it is 156,990 bp, which is in the normal size range for plastomes rather than a short single-gene barcode fragment like rbcL or matK. It is listed as circular and is annotated with typical plastid genes such as psaA, psbA, and rbcL. The Galaxy's Fasta Statistics showed exactly 1 sequence record (scaffold_num_seq = 1) instead of multiple fragmented contigs. 

  3. It has the usual LSC–IRa–SSC–IRb layout. According to Yang et al. (2021), the LSC is 99,259 bp, the SSC is 22,267 bp, and each IR is 17,732 bp. Together that is 99,259 + 22,267 + 17,732 + 17,732 = 156,990 bp. The IRs are shorter than in most flowering plants, which I read as an IR contraction. Earlier work on the Ginkgo plastome links this to the loss of one ycf2 copy.

  4. The record has 134 annotated genes: 85 protein-coding, 41 tRNA, and 8 rRNA. No confirmed pseudogenes were identified in the *Ginkgo biloba* plastid genome accession MN443423.1. Some genes show up twice because the two IR regions are copies of the same sequence. Any gene inside the IR is therefore counted once in IRa and once in IRb. The IR copies should be identical or nearly so.

  5. Eight protein-coding genes from different functional groups:
     
   - 1. psaA (Photosystem I): psaA codes for a core protein of Photosystem I, which holds the chlorophyll and electron carriers that capture light energy.
        
   - 2. psbA (Photosystem II): Encodes the D1 reaction center protein responsible for primary charge separation and water splitting in PSII.
 
   - 3. atpB (ATP Synthase): atpB codes for the beta subunit of ATP synthase, which is part of the catalytic site that makes ATP using a proton gradient.

   - 4. ​petA (Cytochrome b6/f complex): petA codes for cytochrome f, part of the cytochrome b6/f complex, which transfers electrons between PSII and PSI.
        
   - 5. ​rbcL (Carbon Fixation): rbcL codes for the large subunit of Rubisco, the enzyme that fixes CO2 in the Calvin cycle.
        
   - 6. ​ndhF (NADH Dehydrogenase): ndhF codes for a subunit of the NADH dehydrogenase-like complex, which takes part in cyclic electron flow around Photosystem I.
        
   - 7. rpoB (RNA Polymerase): Encodes the beta subunit of plastid-encoded RNA polymerase (PEP) for gene transcription.
        
   - 8. rps12 (Ribosomal Small Subunit): Encodes ribosomal protein S12 required for plastid protein translation. It also trans-spliced

  7. The rRNA genes are rrn16, rrn23, rrn4.5, and rrn5, and they sit in the IR, so there are two copies of each. For tRNAs, trnK-UUU carries lysine and has an intron that contains matK. trnL-UAA carries leucine, and its intron is a group I intron. Two genes with introns are clpP and ycf3, which have two introns each. rps12 is trans-spliced, with its first exon in the LSC and the other exons in the IR.

 8. In accession **MN443423.1**, no pseudogenes were confirmed, but the *Ginkgo biloba* plastome exhibits a gymnosperm-specific inverted repeat (IR) contraction (~24.9 kb) resulting from the partial loss and shifting of *ycf2*, which leaves *ycf2* as a single-copy gene in the large single-copy (LSC) region rather than duplicated as in most angiosperms.

 9. The GC content is 39.56%. The base counts from Galaxy are A = 46,855, T = 48,032, C = 31,611, and G = 30,492, so the genome is about 60.4% AT. Two other things I noticed:
   - The whole genome came out as a single sequence record with no N bases.
   - The IRs are a lot shorter than in most angiosperms, which cuts the total genome size.

 9. The five similarities:
    - Both come from bacteria that were taken in by endosymbiosis.
    - Both keep a small genome compared with their free-living ancestors, because many genes moved to the nucleus.
    - Both code for part of their own translation machinery, such as rRNAs and ribosomal proteins.
    - Both code for subunits of membrane protein complexes that make energy.
    - Both are usually inherited from one parent and exist in many copies per cell.

 Differences:

  The five differences:
    - Plastids do photosynthesis/Carbon fixation, and mitochondria do respiration/ATP synthesis.
    - Plastomes are small and similar in size across plants (about 120–170 kb), while plant mitochondrial genomes range from about 200 kb to several Mb.
    - Plastomes have a single circular map with quadripartite LSC–IR–SSC–IR layout, while mitochondrial genomes are often a dynamic master circle with subgenomic linear/circular forms.
    - Plastomes have high gene density about 110–130 genes, and plant mitochondrial genomes have low gene density about 50–60 genes spread over larger non-coding regions.
    - Plastid sequences evolve faster at the nucleotide level than plant mitochondrial ones, but their structure changes much less. Plant mitochondria show the opposite pattern, and they also have much more RNA editing.

For Ginkgo specifically, plastids look maternally inherited. A recent study using this same genome says so, and it also says mitochondria may be maternal too. So inheritance is not a difference I would list here.

  10. Plastid genomes are useful because:
      - They have many copies per cell, so they are easy to recover even from old or poor-quality DNA.
      - They are small, so sequencing and assembly are cheaper.
      - Their gene content and order are conserved, so they are easy to align between species.
      - They mostly don't recombine and are inherited from one parent, which makes lineages easier to follow.
      - They are the same in males and females. In a dioecious species like Ginkgo, nuclear sex chromosomes have lower recombination and different copy numbers in the two sexes, which complicates analysis.
      - They give a lot of phylogenetic signal for a small amount of sequence.

The limitations are that:
  - They show only one parent's lineage.
  - They have few genes, so they may not separate very close relatives.
  - They tell you little about adaptation or traits controlled by nuclear genes.
  - A plastome tree can disagree with the species tree if there has been hybridization or chloroplast capture.

Research Question Examples
 Plastid data: Where does Ginkgo biloba fall among the living seed plants? Plastid genes are conserved enough to align across very distant groups, so a plastome is a useful starting point for this kind of question.
 Nuclear data: Do Ginkgo populations from warmer or wetter areas differ genetically from those in cooler or drier areas? Nuclear SNPs from many genes can show population structure and possible local adaptation. The plastome can't, since it is inherited from one parent and acts as a single locus.

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
   

4. Github Link: https://github.com/Jayeydd/cmb-plastid-genome-Ginkgo-Suan
