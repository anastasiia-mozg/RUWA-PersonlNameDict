# A Dictionary of Personal Names in News Discourse on the Russian-Ukrainian War

## Overview

This repository contains a dictionary of personal names extracted from news discourse on the Russian-Ukrainian war (2022). The dictionary was constructed to improve the accuracy of named entity recognition (NER) by consolidating name variants referring to the same individual.

## Data Source

The dictionary was obtained from the [RUWA dataset](https://github.com/ninakhairova/dataset_RUWA), which contains news articles covering the Russian-Ukrainian war.

## Dictionaries Included

Edit-Distance-Based Dictionary (names_edit_distance.json)

- Damerau-Levenshtein distance was used to group name variants

Cosine-Similarity-Based Dictionary (names_cosine_similarity.json)

- Cosine similarity was used to group name variants


Manually-Corrected Dictionary (names_corrected.json)

- Based on a manual review and correction of 500 groups of personal name variants.
- The final output contains 542 refined name groups to ensure higher accuracy.
