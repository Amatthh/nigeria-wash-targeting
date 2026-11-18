# Household WASH deprivation and the limits of model-based targeting in Nigeria

This repository contains analysis notebooks for a study using the
2013, 2018 and 2024 Nigeria Demographic and Health Surveys (NDHS),
linked to CHIRPS rainfall and ERA5-Land temperature data.

The study examines WASH inequalities, spatial clustering, household
prediction and the reliability of state-level priority decisions.
It evaluates how missing outcomes and priority thresholds affect
the interpretation of those decisions.

## Repository contents

- [Notebook order and execution guide](notebooks/README.md)
- [Data sources and climate periods](docs/DATA_SOURCES.md)

## Data access

Researchers must obtain authorised access to the Nigeria DHS
household and geographic datasets through
[The DHS Program](https://dhsprogram.com/data/).

The data sources guide identifies the climate datasets and months
required for each survey round.

## Running the analysis

1. Run the DHS harmonisation notebook.
2. Complete the climate linkage for each survey round.
3. Combine the climate-linked survey rounds.
4. Follow the notebook guide for descriptive analysis, mapping,
   spatial modelling, household prediction and priority assessment.

The December 2023 climate pilot documents development of the
linkage procedure.

Each notebook explains its required inputs, processing steps,
quality checks and outputs. Follow its instructions for the
software environment and input filenames.

## Analytical scope

All three survey rounds contribute to domain-specific descriptions.
The primary multidimensional deprivation models use 2018 and 2024.
The 2013 composite outcome is used in sensitivity analyses.

The main state-priority cutoff is study-defined at 50%, with
sensitivity analyses at 40% and 60%.

## Reproducibility

Use the notebook versions and input data releases corresponding to
the analysis being reproduced. Record package versions and the
repository commit used for the completed run.

## Manuscript

Household WASH deprivation and the limits of model-based targeting
in Nigeria.

The publication citation and DOI will be added when available.
