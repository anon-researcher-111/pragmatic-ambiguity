# "Detecting and Resolving Pragmatic Ambiguities in Natural Language Requirements with Contextual Discrepancy Detection

## Overview

This repository contains the validation package supporting our submission "Detecting and Resolving Pragmatic Ambiguities in
Natural Language Requirements with Contextual Discrepancy Detection". It includes the code used in the experiments for both pragmatic ambiguity detection and pragmatic ambiguity resolution, along with the ground truth datasets for validation.

## Contents

- `Pragmatic_Ambiguity_Detection_and_Resolution.ipynb`: Jupyter Notebook implementing pragmatic ambiguity detection and resolution.
- `Clarus_ground_truth.xlsx`: Ground truth dataset for the Clarus Weather System Design document.
- `MDOT_VII_DUAP_ground_truth.xlsx`: Ground truth dataset for the MDOT VII Data Use Analysis and Processing Document.
- `words_alpha.txt`: A list of alphabetical words in the english language (words that only have letters, no numbers or symbols), used to filter out project-specific terms during minimum coverage index calculation. [Source](https://github.com/dwyl/english-words/blob/master/words_alpha.txt)

## Requirements

- Python 3.8+
- Jupyter Notebook
   
## Usage

1. Open the Jupyter Notebook `Pragmatic_Ambiguity_Detection_and_Resolution.ipynb`.
2. Follow the instructions in the notebook to run the ambiguity detection and resolution pipeline.



