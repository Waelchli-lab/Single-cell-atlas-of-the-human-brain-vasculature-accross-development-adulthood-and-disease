# **Single-cell-atlas-of-the-human-brain-vasculature-across-development-adulthood-and-disease**
**Publicaiton link:**
**DOI: 10.1038/s41586-024-07493-y**

## **Abstract**
A broad range of brain pathologies critically relies on the vasculature, and cerebrovascular disease is a leading cause of death worldwide. 
However, the cellular and molecular architecture of the human brain vasculature remains incompletely understood. 
Here, we performed single-cell RNA sequencing of 606,380 freshly isolated endothelial, perivascular and other tissue-derived cells from 117 samples, 
from 68 human fetuses and adult patients to construct a molecular atlas of the developing fetal, adult control and diseased human brain vasculature. 
We uncover extensive molecular heterogeneity of the vasculature of healthy fetal and adult human brains and across eight vascular-dependent Central Nervous System (CNS) pathologies 
including brain tumors and brain vascular malformations. We identify alteration of arteriovenous differentiation and reactivated fetal as well as conserved dysregulated genes and pathways 
in the diseased vasculature. Pathological endothelial cells display a loss of CNS-specific properties and reveal an upregulation of MHC class II molecules, indicating atypical features 
of CNS endothelial cells. Cell-cell interaction analyses predict numerous endothelial-to-perivascular cell ligand-receptor crosstalk including immune-related and angiogenic pathways,
thereby unraveling a central role for the endothelium within brain neurovascular unit signaling networks. Our single-cell brain atlas provides insight into the molecular architecture and
heterogeneity of the developing, adult/control and diseased human brain vasculature and serves as a powerful reference for future studies.

## **Methods**
**Isolation of FACS-sorted human fetal and adult endothelial cells and of unsorted human fetal and adult endothelial and perivascular cells for single cell RNA-seq**
Endothelial cells were isolated from human fetal and adult tissues using tissue digestion and subsequent CD31 + / CD45- FACS sorting whereas human endothelial and perivascular cells (all
cells) were isolated from the unsorted fraction. Briefly, both fetal and adult tissues were quickly minced in a petri dish on ice, using two surgical blades. For CD31+ / CD45- FACS sorting, a
cell suspension was obtained upon digesting the tissue in 2 mg/ml Dispase II (D4693, Sigma- Aldrich, Steinheim, Germany), 2 mg/ml Collagenase IV (#1710401, Thermo Fisher Scientific,
Zurich, Switzerland) and 2 mM CaCl2 PBS solution for 40 min at 37°C with occasional shaking. The suspension was filtered sequentially through 100/70/40 μm cell strainers
(#431751, Corning, New York, USA) to remove large cell debris. Cells were then centrifuged 500 RCF for 5 min at 4°C. In case of a visible myelin pellet 5 ml 25% Bovine Serum Albumin
(BSA) (ice cold) was overlayed with 5 ml of the sample, centrifuged at 2000 RCF for 20 min (4°C). The supernatant was removed (including the lipid phase) and the pellet was resuspended
in 9 ml PBS, followed by another round of centrifugation at 500 RCF for 5 min (4°C). Supernatant was subsequently discarded, while the cell pellets were resuspended in 3 ml of
ACK hemolytic buffer at room temperature for 3 minutes. To stop the reaction, 30 ml of ice- cold PBS was added to the mixture and centrifuged at 500 RCF for 5 min at 4⁰C. The cell pellets
were resuspended in FACS buffer (PBS + 1% Bovine Serum Albumin), a volume is taken for unsorted scRNA-seq analysis. For CD31+ / CD45 - FACS sorting, the cells were stained with
anti-CD31 PE conjugated antibody in a concentration of 1:20 (#566125, clone MBC78.2, BD Pharmingen) and anti-CD45 APC conjugated antibody in a concentration of 1:20 (#17-0459- 42, clone HI30, eBiosciences) for 30 min at 4⁰ C, protected from light. Thereafter the cells were
washed with 1ml of FACS buffer, centrifuged in a tabletop centrifuge at 500 RCF at 4⁰C for 5 min. Finally, the cell pellets were resuspended in appropriate volumes of FACS buffer (PBS +
1% Bovine Serum Albumin) and the suspension was passed through a 35 μm cell strainer of a FACS sorting tube (#352235, Corning). Immediately before sorting, SYTOXTM blue was added
in 1:1000 (Thermo Fisher Scientific, #S34857) to exclude dead cells from further analysis. Cell debris were excluded via a forward scatter-area/side scatter-area (FSC-A/SSC-A) gating, while
singlets were selected for using a forward scatter-area (FSC-A)/ FSC-height (FSC-H) gating strategy. Viable (SYTOXTM blue negative) endothelial cells were FACS-sorted by endothelial
marker CD31 positivity and negative selection for the brain microglia and macrophages marker CD45, whereas unsorted endothelial and perivascular cells were obtained from the SYTOXTM
blue- fraction. Cells were sorted by a FACS Aria III (BD Bioscience) sorter using the four-way purity sorting mode directly in EGM2 medium (#CC-3162, Lonza, Basel, Switzerland).

### GEO: 
All data (raw and processed) is accessible via the accession number GSE256493 (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE256493)

### Interactive websites for data visulaization and download are available at:
- https://waelchli-lab-human-brain-vasculature-atlas.ethz.ch
- https://brain-vasc.cells.ucsc.edu
- https://cellxgene.cziscience.com/collections/c95ca269-68a7-47c5-82db-da227f31b598

### Download links: 
- The generated Seurat objects of FACS-sorted (CD31+/CD45-) endothelial cells for the individual entities can be downloaded from: https://doi.org/10.5281/zenodo.10058183
- The generated Seurat objects of FACS-sorted (CD31+/CD45-) endothelial cells for the the overall merges of entities can be downloaded from: https://doi.org/10.5281/zenodo.10057779
- The generated Seurat objects of unsorted endothelial and perivascular cells for individual entities can be downloaded from: https ://doi.org/10.5281/zenodo.10058371
- The generated Seurat objects of unsorted endothelial and perivascular cells for the overall merges of entities can be downloaded from: https://doi.org/10.5281/zenodo.10058563
- The generated Monocle 3 CDS pseudotime objects of FACS-sorted (CD31+/CD45-) endothelial cells can be downloaded from: https://doi.org/10.5281/zenodo.10058766
- The generated diffusion map objects of FACS-sorted (CD31+/CD45-) endothelial cells can be downloaded from: https://doi.org/10.5281/zenodo.10060876
- The generated RNA velocity objects of FACS-sorted (CD31+/CD45-) endothelial cells of individual pathological entities can be downloaded from: https://doi.org/10.5281/zenodo.10065659
- The generated RNA velocity objects of FACS-sorted (CD31+/CD45-) endothelial cells of the fetal and adult/control brains from: https://doi.org/10.5281/zenodo.10066390
- The generated RNA velocity objects of FACS-sorted (CD31+/CD45-) endothelial cells of the overall merge of brain tumors from: https://doi.org/10.5281/zenodo.10066538
- The generated RNA velocity objects of FACS-sorted (CD31+/CD45-) endothelial cells of the overall merge of pathological entities from: https://doi.org/10.5281/zenodo.10066703






##### created by: Moheb Ghobrial


