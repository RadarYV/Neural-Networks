# Text Classification with BERT

You need to train the model to classify comments into positive and negative. 
A quality of model (**F1**) should be at least 0.75. 

## Data
The data is in the file `toxic_comments.csv`. The *text* column in it contains the comment text, and *toxic* is the target attribute.

- 'bert\\vocab.txt' - vocabulary
- 'bert\\config.json' - configuuration
- 'bert\\pytorch_model.bin' - bert model

## Brief
 - Convert the text to token numbers from the dictionary
 - Create attention mask
 - Create batches of embeddings
 - Geerate features embeddings
 - train-test split
 - use logistic regression and LightGBM
 - Conclusions and recommendations

## Libraries used

- torch
- transformers
- sklearn