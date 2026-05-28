# Quota-Based Slack Analysis in Global Trade Networks

This repository contains the replication materials for the contribution:

**Slack in the Chain: Measuring Structural Pivotality in Global Trade Networks**  
Brian Daniel Bernhardt and Mario Rosario Guarracino

## Overview

The project introduces a quota-based slack metric to identify structurally pivotal supplier-product links in weighted bipartite trade networks. The empirical application uses the BACI international trade database compiled by CEPII and focuses on the 2023 HS17 cross-section aggregated to the HS4 product level.

## Repository Structure

notebooks/ ->                 Main Google Colab notebook

BACI_HS17_V202601_/ ->       Product and country codes 

## Raw Data

The raw trade data are not included in this repository because the BACI files are large.

To reproduce the analysis, download the official BACI dataset from CEPII:

https://www.cepii.fr/CEPII/en/bdd_modele/bdd_modele_item.asp?id=37

This project uses:

- BACI HS17
- Version: V202601
- Reference year: 2023
- Product level in raw data: HS6
- Product level used in the analysis: HS4, obtained by truncating HS6 codes to the first four digits
