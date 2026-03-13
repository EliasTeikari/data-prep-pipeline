# Feedback Dataset Cleaner and Analyzer

This project is for collecting human feedback on model outputs.

The pipeline does this:

- loads a dataset from HuggingFace datasets
- inspects the schema
- cleans bad rows
- adds useful derived columns
- split into train/validation
- converts a sample to pandas for analysis
- exports the cleaned dataset

## Usage

I will make a jupyter notebook to lead the dataset

1. print column names and a few examples
2. remove empty or very short texts
3. add columns like text length, word count
4. split into train/text or train/validation
5. convert a sample to pandas for analysis
6. compute simple summaries
