# Language-as-Data

For this assignment, I chose to work with the Hugging Face dataset, which is accessible at the following link: https://huggingface.co/datasets/werent4/lithuanian-translations/viewer/en-lt. This dataset contains sentences translated from Lithuanian to English.

Original Dataset: The dataset is provided in the file train-00000-of-00001.parquet.

Prompts for Data Augmentation: The Jupyter Notebook Llama3_for_Data_Augmentation.ipynb contains the prompts used for data augmentation.

Augmented Dataset: The file train-00000-of-00001.csv includes both the original data (lines 1–498) and the data augmented using the LLaMA 3 model (lines 499–523).

Dataset Analysis: The Jupyter Notebook Dataset_Analysis.ipynb provides a basic analysis of the dataset, examining properties such as average sentence length, vocabulary size, most frequent words, and POS tags.

Machine Translation Experiments: The folder MT Experiments contains the code and all the generated files used during the machine translation experiments.
