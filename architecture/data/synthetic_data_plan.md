Synthetic Data Plan

Synthetic, non-identifiable datasets will be used for early prototyping to ensure full privacy and to allow open sharing of the project.

1. Why Synthetic Data

No patient-identifiable data required.

Safe for open-source use.

Allows early model testing before access to real datasets.

Aligns with NHS and global digital health governance standards.

2. Planned Synthetic Datasets
A. Search Trends

Fields:
date, keyword, search_volume

B. ED Respiratory Visits

Fields:
date, age_group, resp_visit_count

C. Prescription Patterns

Fields:
date, antiviral_count, antibiotic_count, steroid_count

D. Wearable Device Signals

Fields:
user_id (fake), date, resting_hr, skin_temp, sleep_disruption_index

E. Wastewater Genomics

Fields:
site_id, date, viral_rna_level, variant_signal_strength

3. Synthetic Data Tools

Python Faker

NumPy random generators

Pandas time-series creation

Optional: SDV (Synthetic Data Vault)

4. Folder Structure

Synthetic datasets will be placed in:/data/raw/synthetic/
