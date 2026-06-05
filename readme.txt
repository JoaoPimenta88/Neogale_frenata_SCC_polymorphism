This repository contains the genomic analysis pipeline used to investigate the genetic basis of winter coat color polymorphism in the long-tailed weasel (Neogale frenata). Using whole-genome sequencing data generated from historical museum specimens sampled across two independent winter color transition zones in North America, the pipeline identifies genomic regions associated with adaptive variation, characterizes population structure, estimates population genetic parameters, and detects signatures of natural selection.

The analyses revealed independent mutations in the pigmentation gene MC1R associated with the winter-brown phenotype in eastern and western populations, providing evidence for recurrent evolution of seasonal camouflage adaptation.

Pipeline Structure

The workflow is organized into the following modules:

Step	Description
0. RawData_Filtering	Quality control and filtering of raw sequencing data.
1. DNA_Damage_filter	Identification and filtering of DNA damage patterns associated with historical museum specimens.
2. PopulationStructure	Population structure analyses, including genetic clustering and ancestry inference.
3. Association_Scans	Genome-wide association analyses to identify genomic regions linked to winter coat color variation.
4. Population_summary_stats	Estimation of population summary stats.
5. SelectionScan	Detection of genomic signatures of natural selection and adaptive evolution.

This pipeline is designed for whole-genome sequencing datasets and is particularly suitable for studies of adaptation, evolutionary genomics, and museum genomics.
