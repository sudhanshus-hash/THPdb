# THPdb: Database of FDA-approved Peptide and Protein Therapeutics

Welcome to the official repository and documentation overview for **THPdb**, a manually curated repository of Food and Drug Administration (FDA) approved therapeutic peptides and proteins. This resource provides a comprehensive platform for researchers to explore clinical therapeutics, their drug variants, and their pharmacological profiles to assist in drug discovery.

**Web Server:** [http://crdd.osdd.net/raghava/thpdb/](http://crdd.osdd.net/raghava/thpdb/)

## Citation

Usmani, S. S., Bedi, G., Samuel, J. S., Singh, S., Kalra, S., Kumar, P., ... & Raghava, G. P. S. (2017). 
**THPdb: Database of FDA-approved peptide and protein therapeutics.** *PLOS ONE*, 12(7): e0181748. 
[https://doi.org/10.1371/journal.pone.0181748](https://doi.org/10.1371/journal.pone.0181748)

This dataset can also be found on Zenodo at https://doi.org/10.5281/zenodo.20072945


## About the Database

THPdb was developed to provide the first single, freely available platform dedicated entirely to US-FDA approved protein and peptide therapeutics. It addresses the need for integrated data that was previously scattered across literature and disparate repositories.

The database integrates data from:
* **Primary Literature:** Information compiled from 985 research publications and 70 patents.
* **External Repositories:** Data integrated from resources like DrugBank and the Protein Data Bank (PDB).

## Key Features

### Comprehensive Dataset
* **239 unique therapeutics** consisting of US-FDA approved peptides and proteins.
* **380 drug variants** including modified drug molecules (e.g., PEGylated) and different brand names.
* **852 total entries** systematically compiled with detailed pharmacological profiles.

### Rich Annotations
Each record includes:
* **Pharmacological Data:** Information on half-life, molecular weight, and mechanism of action.
* **Chemical Modifications:** Details on modifications used to improve therapeutic competency, such as glycosylation.
* **Structural Data:** 3D structures provided via PDB entries or predicted using I-TASSER and PEPstrMOD.
* **Physicochemical Properties:** Calculated amino acid composition, hydrophobicity, and isoelectric points.

### Built-in Tools
* **Sequence Alignment:** Integrated BLAST and Smith-Waterman algorithms for similarity searches against database sequences.
* **Search & Browse:** Query by therapeutic name, property, or disease, with support for advanced Boolean expressions.


## Overview

THPdb is organized into primary and secondary data categories to ensure a comprehensive therapeutic profile:
1.  **Primary Information:** Core data including sequence, toxicity, and clinical status.
2.  **Drug Variant Data:** Information on brand names, manufacturers, and specific modifications.
3.  **Functional Classification:** Categorized into four groups: Enzymatic/Regulatory (Group I), Special Targeting (Group II), Vaccines (Group III), and Diagnostic Agents (Group IV).



## Applications

* **Drug Discovery:** Identifying strategies used to improve half-life and rate of clearance in therapeutics.
* **Molecular Modeling:** Utilizing provided 3D structural information for docking and molecular dynamics studies.
* **Academic Enhancement:** Accessing downloadable, self-explanatory power-point presentations for research and teaching.
  
## Contact & Authors

**Prof. G.P.S. Raghava**
raghava@imtech.res.in | raghava@iiitd.ac.in
Bioinformatics Centre, CSIR-Institute of Microbial Technology, Chandigarh, India.

## License

This database is distributed under the **Creative Commons Attribution License (CC BY 4.0)**.
