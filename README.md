# South-america-vaccination-scientometrics
Reproducibility files for the systematic mapping and scientometric analysis of vaccination research in South America.

VOSviewer Reproducibility Files
=================================

Study title
-----------
Vaccination research at the intersection of health literacy, education, and
communication in South America: A systematic mapping and scientometric analysis
across a decade of crisis and recovery

Purpose
-------
This repository contains the files required to inspect and reproduce the
VOSviewer analyses reported in Figures 3–5 of the manuscript.

Folder structure
----------------
VOSviewer_reproducibility_files/
|
|-- README.txt
|-- Supplementary_Tables.xlsx
|
|-- input_files/
|   |-- pre_pandemic_input.txt
|   |-- pandemic_input.txt
|   `-- post_pandemic_input.txt
|
|-- term_cooccurrence/
|   |-- pre_pandemic_terms_map.txt
|   |-- pre_pandemic_terms_network.txt
|   |-- pandemic_terms_map.txt
|   |-- pandemic_terms_network.txt
|   |-- post_pandemic_terms_map.txt
|   `-- post_pandemic_terms_network.txt
|
`-- coauthorship/
    |-- pre_pandemic_coauthorship_map.txt
    |-- pre_pandemic_coauthorship_network.txt
    |-- pandemic_coauthorship_map.txt
    |-- pandemic_coauthorship_network.txt
    |-- post_pandemic_coauthorship_map.txt
    `-- post_pandemic_coauthorship_network.txt

Temporal classification
-----------------------
Publications were assigned to one of three periods according to their specific
publication dates:

1. Pre-pandemic: January 1, 2015 to March 10, 2020
2. Pandemic: March 11, 2020 to May 5, 2023
3. Post-pandemic: May 6, 2023 to November 30, 2025

Publications from the boundary years 2020 and 2023 were classified according to
their exact publication dates rather than by calendar year alone.

Input files
-----------
The files in the "input_files" folder contain the bibliographic records used to
construct the period-specific VOSviewer networks.

The supplementary spreadsheet contains the complete list of screened and
included studies and the corresponding study-selection information.

VOSviewer analyses
------------------
Software:
VOSviewer version 1.6.18

Term co-occurrence analysis:
- Text source: titles and abstracts
- Counting method: full counting
- Minimum occurrence threshold: 5
- Normalization method: association strength
- Clustering method: VOS clustering
- Resolution parameter: 1.00

The same analytical parameters were applied to all period-specific term
co-occurrence networks.

Co-authorship analysis:
The co-authorship map and network files are provided separately for the
pre-pandemic, pandemic, and post-pandemic periods.

Data cleaning
-------------
Before term extraction, structured abstract labels and copyright statements
were removed from the textual corpus.

No VOSviewer thesaurus file was used.

Figure correspondence
---------------------
Figures 3A and 3B:
Pre-pandemic term co-occurrence network and temporal overlay visualization.
Files:
- term_cooccurrence/pre_pandemic_terms_map.txt
- term_cooccurrence/pre_pandemic_terms_network.txt

Figures 3C and 3D:
Pre-pandemic co-authorship network and temporal overlay visualization.
Files:
- coauthorship/pre_pandemic_coauthorship_map.txt
- coauthorship/pre_pandemic_coauthorship_network.txt

Figures 4A and 4B:
Pandemic-period term co-occurrence network and temporal overlay visualization.
Files:
- term_cooccurrence/pandemic_terms_map.txt
- term_cooccurrence/pandemic_terms_network.txt

Figures 4C and 4D:
Pandemic-period co-authorship network and temporal overlay visualization.
Files:
- coauthorship/pandemic_coauthorship_map.txt
- coauthorship/pandemic_coauthorship_network.txt

Figures 5A and 5B:
Post-pandemic term co-occurrence network and temporal overlay visualization.
Files:
- term_cooccurrence/post_pandemic_terms_map.txt
- term_cooccurrence/post_pandemic_terms_network.txt

Figures 5C and 5D:
Post-pandemic co-authorship network and temporal overlay visualization.
Files:
- coauthorship/post_pandemic_coauthorship_map.txt
- coauthorship/post_pandemic_coauthorship_network.txt

How to open the files
---------------------
1. Open VOSviewer.
2. Select "Open".
3. Load the corresponding map file and network file.
4. Use "Network Visualization" to inspect clusters and links.
5. Use "Overlay Visualization" to inspect temporal patterns.

The map files contain item-level information, including labels, coordinates,
cluster assignments, occurrence weights, and link-related metrics. Therefore,
a separate term-list spreadsheet was not created.

Reproducibility note
--------------------
The period-specific networks were designed as exploratory scientometric maps.
Because the three temporal corpora differ in size, the absolute numbers of
retained terms and clusters should not be interpreted as normalized measures
of thematic complexity across periods.

Contact
-------
Patricia Paiva Corsetti (e-mail: patricia.corsetti@unifal-mg.edu.br).
Laboratory of Molecular Biology of Microorganisms
Federal University of Alfenas, Rua Gabriel Monteiro da Silva, 700, Alfenas, 37130-001, Minas Gerais, Brazil.
