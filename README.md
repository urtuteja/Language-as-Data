# Language-as-Data

For this assignment, I chose to work with the Hugging Face dataset, which is accessible at the following link: https://huggingface.co/datasets/werent4/lithuanian-translations/viewer/en-lt. This dataset contains sentences translated from Lithuanian to English.

The original dataset is provided in the file train-00000-of-00001.parquet.

The file train-00000-of-00001.csv contains the original data (lines 1-498) as well as data that was augmented using the LLaMA 3 model (lines 499-523).

The Jupyter Notebook Dataset_analysis.ipynb includes basic analyses of the dataset, investigating the following properties: average sentence length, vocabulary size and most frequent words, and POS tags.
