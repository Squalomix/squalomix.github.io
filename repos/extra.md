---
layout: default
title: Squalomix Extra
permalink: /repos/extra/
---

# Squalomix Extra

Our [Data Use Policy](data-use-policy.md) applies to all of the assemblies below, and applies strictly to those marked as 'in prep.'.

## Non-chondrichthyan species chosen for whole genome sequencing by Squalomix

Some comments about the status and details of the individual assemblies are included below the table.

| Species |Common name|Technology|Publication or release detail|
|----|----|----|----|
| *Geotria australis* | pouched lamprey | illumina short read + mate-pair + Hi-C | in prep. |
| *Mordacia mordax* | southern lamprey | illumina short read + mate-pair + Hi-C | in prep. |
| *Cololabis saira* | Pacific saury | PacBio HiFi + Hi-C | [Sato et al., 2024](https://academic.oup.com/dnaresearch/article/31/2/dsae004/7623430) |
| *Halichoeres trimaculatus*| Threespot wrasse| PacBio HiFi + Hi-C | [Nozu et al., 2024](https://onlinelibrary.wiley.com/doi/10.1111/gtc.13166)|
| *Paroedura picta* | Madagascar ground gecko | PacBio HiFi + Hi-C | [GCF_049243985.1](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_049243985.1/)|
| *Coturnix japonica* | Japanese quail | PacBio HiFi + Hi-C |[GCF_054131305.1](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_054131305.1/)|
| *Nothobranchius furzeri* | African turquoise killifish | PacBio HiFi + Hi-C |[GCF_043380555.1](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_043380555.1/)|

<div class="accent-bar" aria-hidden="true"></div>

### *Coturnix japonica* (Japanese quail)

An improved chromosome-scale genome assembly has been produced by collaborating with Prof. Nishijima at Avian Bioscience Research Center of Nagoya University who conducts [National BioResource Project (NBRP) for chicken and quail under MEXT, Japan](https://www.agr.nagoya-u.ac.jp/~nbrp/en/organiztion/index.html). It has been released at NCBI as [GCF_054131305.1](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_054131305.1/).

### *Nothobranchius furzeri* (African turquoise killifish)

*Nothobranchius furzeri* is known as African turquoise killifish and is an excellent model organism for aging study, having the shortest captive lifespan among vertebrates and showing highly similar aging phenotypes to humans. In collaboration with Prof. Tohru Ishitani at RIMD, Osaka University, we are working on genome assembly improvement for this species, and the first product from this collaboration is available at NCBI ([GCF_043380555.1](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_043380555.1/)). See also our preprint on this genome ([Ogawa et al., bioRxiv 2026](https://www.biorxiv.org/content/10.64898/2026.10.12.757905v1)).

### *Cololabis saira* (Pacific saury)

After our fundamental analysis on a non-phased assembly ([DNA Research](https://academic.oup.com/dnaresearch/article/31/2/dsae004/7623430)), we have made haplotype-phased assemblies ('hap1' and 'hap2') with hifiasm and YaHS, which are available have been registered under the [BioProject PRJNA1104577](https://www.ncbi.nlm.nih.gov/bioproject/1104577) and available in NCBI (as of September 11, 2024). Those assemblies underwent some manual interventions after computation with YaHS, and we recognize some discrepancies in chromosomal organization between the 'hap1' and 'hap2', which will be amended by our future effort.

### *Geotria australis* (pouched lamprey) and *Mordacia mordax* (southern lamprey)

We are preparing to publish our molecular evolutionary analyses using these assemblies, and the [Data Use Policy](data-use-policy.md) strictly applies to these assemblies.

### *Paroedura picta* (Madagascar ground gecko)

Our initial effort with short-read sequencing resulted in its the first release of this species' genome assembly which however did not reach chromosome levels ([Hara et al., BMC Biol 2018](https://bmcbiol.biomedcentral.com/articles/10.1186/s12915-018-0509-4); v1; GCA_003118565.1). Later we applied Hi-C scaffolding on the contigs obtained with the 10X Linked Reads technology, to achieve the chromosome scale ([Yamaguchi et al., Mol Ecol, 2021](https://onlinelibrary.wiley.com/doi/10.1111/mec.16146); v2; GCA_003118565.2). Most recently, we reused the Hi-C data to scaffold the contigs obtained with high-fidelity (HiFi) long-read sequencing ([GCF_049243985.1](https://www.ncbi.nlm.nih.gov/datasets/genome/GCF_049243985.1/)). Gene model construction with NCBI EGAP has been completed and [its output](https://www.ncbi.nlm.nih.gov/refseq/annotation_euk/Paroedura_picta/GCF_049243985.1-RS_2025_09/) is accessible.  

At the moment, [CRISPRdirect](https://crispr.dbcls.jp/) provides CRISPR/Cas guide RNA designing only on v1 and v2 genome assemblies.
