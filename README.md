# entity-recognition-recipes
An NLP project using CRF to extract entities from culinary data
# Identifying Key Entities in Recipe Data

## Overview
This project focuses on extracting structured information from unstructured recipe text using Natural Language Processing (NLP). The goal is to identify and classify entities like Ingredients, Quantities, and Units.

## Methodology
- **Model:** Conditional Random Fields (CRF) for sequence labeling.
- **Libraries:** Python, `sklearn-crfsuite`, `pandas`, and `spacy`.
- **Key Features:** Custom feature engineering using contextual word neighbors and regex-based quantity patterns.

## Performance
- Addressed class imbalance using inverse frequency weights.
- Achieved significant improvement in identifying minority classes (Units and Quantities).

## Future Improvements
- Integration of pre-trained word embeddings (Word2Vec/GloVe).
- Enhanced regex patterns for complex fraction formats.
