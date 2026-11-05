---
layout: default
title: Data & Tools
permalink: /data/
---

# Data & Tools

This page collects the data products and technical outputs of the consortium, grouped by type. The sequence data reported in our publications are deposited at NCBI, under the consortium's [BioProject entry (PRJNA707598)](https://www.ncbi.nlm.nih.gov/bioproject/PRJNA707598). Detailed datasets and protocols have their own pages on this site (see "Topics" in the menu on the left).

## Protocols and standards

- [iconHi-C](repos/iconhi-c.md) — our inexpensive and controllable Hi-C protocol and the record of Hi-C data production
- [Shark cell culture](repos/karyotype.md) — our cell culture protocol for elasmobranch karyotyping ([Uno et al., 2020. Commun. Biol. 3: 652](https://www.nature.com/articles/s42003-020-01373-7))
- [sQuantGenome](repos/c-value.md) — our qPCR-based protocol for estimating genome size, which requires no living cells
- [SNEG](repos/sneg.md) — phylome construction and the standardized nomenclature of elasmobranch genes (SNEG Project)
- [UTR modeling](repos/utr-modeling.md) — our workflow for extending 3' UTR annotations of gene models, using peaks2utr
- [A technical note for Hi-C scaffolding using YaHS](https://github.com/TkNiw/Note-for-YaHS), based on our internal benchmarking

<div class="accent-bar" aria-hidden="true"></div>

## Data by species

- [Species](species.md) — sequencing status for the dozens of species we work on, with latest publications
- [Selected species](repos/selected-species.md) — our flagship species, for which we hold data well beyond genome assemblies
- [Genome sizes](repos/c-value.md) — original genome size (C-value) data measured by the consortium
- [Karyotypes](repos/karyotype.md) — original karyotype data, the reference for validating genome assemblies
- [Squalomix Extra](repos/extra.md) — our products on non-chondrichthyan species

<div class="accent-bar" aria-hidden="true"></div>

## Data use policy

Our data use policy — covering release timing, first-publication rights and the assemblies marked 'in prep.' — is stated on the [Data Use Policy](repos/data-use-policy.md) page.

<div class="accent-bar" aria-hidden="true"></div>

## Our technical basis

The capability behind these products was built over years of operating a DNA sequencing facility. From 2012, Shigehiro Kuraku, the Leader of Squalomix, supervised the genome analysis facility at the RIKEN Kobe Campus — first as the Genome Resource and Analysis Unit of RIKEN CDB and later as the Laboratory for Phyloinformatics of RIKEN BDR, which harbours a DNA Analysis Facility — serving genome projects of many research groups, on a wide range of organisms and sample conditions. Working through demanding material, project after project — samples that were minute, degraded, or from species with no genomic precedent — refined our DNA extraction, library preparation, and data analysis. That accumulated craft is what allowed us to take on the large, repeat-rich genomes of sharks and rays.

For our previous publication in 2018, we produced all short read sequence data in-house at the DNA Analysis Facility operated inside the [Laboratory for Phyloinformatics, RIKEN BDR](https://www.bdr.riken.jp/en/research/labs/kuraku-s/).

We have released the ['iconHi-C' (inexpensive and controllable Hi-C) protocol](repos/iconhi-c.md) for versatile Hi-C data acquisition and performed Hi-C scaffolding to obtain chromosome-scale genome sequences for diverse species. The obtained sequences are validated with original high-fidelity karyotype data provided by our cell culture protocol for elasmobranchs ([Uno et al., 2020. Commun. Biol. 3: 652](https://www.nature.com/articles/s42003-020-01373-7)).

<div class="accent-bar" aria-hidden="true"></div>

## Past efforts

- [Repeats](repos/repeats.md) — repetitive element resources
- [iMate](https://www.slideshare.net/xsighex/imate-protocol-guide-version-20) — our protocol guide for Nextera mate-pair library preparation, used for our 2018 assemblies
