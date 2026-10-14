# Supplementary Proof Catalogue: Normalized Systems Theory and Data Vault 2.0

This repository contains the supplementary proof catalogue accompanying the research paper *Applying Normalized Systems Theory to Data Vault 2.0: A Constructive Approach to Evolvability*.

The research investigates how architectural restrictions derived from Normalized Systems Theory (NST) can be applied to Data Vault 2.0 (DV2.0) data warehouses to limit the propagation of architectural changes as a warehouse grows.

## Supplementary Material

**[ENASE2027_NST_DV20_Alignment_Proofs.pdf](ENASE2027_NST_DV20_Alignment_Proofs.pdf)**

The document extends the nine constructive proofs presented in the main paper with additional change scenarios, detailed artifact counts, preservation arguments, and boundary results.

The catalogue covers source integration and retirement, attribute and type evolution, source renaming, business-rule changes, task activation and recovery, delivery interfaces, and entity splitting and merging.

## Scope and Limitations

The proofs consider a restricted reference architecture satisfying seven architectural restrictions (R1–R7). They establish conditional upper bounds on the number of architectural artifacts that must be added, modified, or retired for specified changes.

These bounds are independent of the accumulated warehouse size only when the stated preconditions, contract-preservation requirements, and change-scope assumptions hold.

The analysis concerns architectural modifications, not development effort, runtime performance, data-processing costs, or arbitrary semantic changes. The catalogue provides analytical arguments rather than an implemented or experimentally validated warehouse.

## Relationship to the Main Paper

The main paper presents the architectural approach, restrictions, formal change-impact model, and principal proofs. This repository provides additional derivations and examples to support examination and reproducibility of the analytical reasoning.

The supplementary catalogue is intended to be read alongside the paper.
