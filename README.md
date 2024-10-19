# sentiment-analysis-shopee-computer-product-reviews
Dataset Reference: https://huggingface.co/datasets/magixxixx/shopee-product-reviews-on-computer-category

Code Snippet to load data from source:

import pandas as pd

df = pd.read_csv("hf://datasets/magixxixx/shopee-product-reviews-on-computer-category/combined-dataset-shuffled-cased-40K.csv")
