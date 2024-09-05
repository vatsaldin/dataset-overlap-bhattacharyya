# NER Dataset Comparison

This repository contains a Jupyter notebook for comparing different Named Entity Recognition (NER) datasets using the Bhattacharyya coefficient.

## Overview

The notebook analyzes and compares the following NER datasets:

- OntoNotes5
- BC5CDR
- CoNLL-2003

It calculates similarity between the datasets based on:

- NER tag distributions
- Word distributions

The analysis uses the Bhattacharyya coefficient as a measure of similarity between probability distributions.

## Key Features

- Loading and preprocessing of NER datasets
- Calculation of tag and word distributions
- Computation of Bhattacharyya coefficients between datasets
- Visualization of results using:
  - Bar plots of tag distributions
  - Heatmaps of similarity coefficients

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, datasets (Hugging Face)

## Usage

1. Clone the repository
2. Install required dependencies
3. Open and run the Jupyter notebook

## Results

The notebook generates visualizations including:

- Tag distribution plots for each dataset
- Heatmaps showing similarity between datasets

These visualizations help in understanding the differences and similarities between the analyzed NER datasets.

## License

Apache 2.0

## Contributing

Contributions to improve the analysis or extend it to other datasets are welcome. Please open an issue or submit a pull request.