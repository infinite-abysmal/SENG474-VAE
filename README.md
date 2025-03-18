The test file for our VAE project.
How to use:
1. download the credit card dataset from https://www.kaggle.com/datasets/priyamchoksi/credit-card-transactions-dataset
2. unzip the dataset to receive a folder named 'archive', leave this folder in the same directory as the test file
3. Open the test file
4. Scroll down to the main loop; this is indicated by a list named test_models
each model trained by the test file has an associated key. This key acts as both a representation of the model and as the model training parameters.
the test_models list is composed of a list of keys, where a key is constructed by key(<parameters dictionary>)
