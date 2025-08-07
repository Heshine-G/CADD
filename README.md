# CADD

This repo demonstrates a ligand-based workflow to identify potential EGFR inhibitors. Key steps include:

- Descriptor Calculation & Filtering

  - Lipinski’s Rule of Five

  - Substructure comparison against known inhibitors

- Machine Learning Modeling

  - Training classifiers on active/inactive labels

  - Scoring molecules by predicted activity probability

- Prioritization

  - Ranking candidates by high predicted activity and favorable properties

All analyses are implemented in Python using RDKit, pandas, scikit-learn, and Cheminfo tools.
