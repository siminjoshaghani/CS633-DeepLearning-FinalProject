# CS633-DeepLearning-FinalProject


Here you can find the experiments for the final project of cs633.

Each notebook contains a GAN model with a different loss function; the experiment aims to explore the use of GANS on tabular data. The main interest is comparing Wasserstein loss with other loss functions to generate tabular data that the label does not exist in the dataset.

Pieces of the code are taken from the following sources:
- Cross entropy code is from the following source and I feed it my data: https://medium.com/analytics-vidhya/a-step-by-step-guide-to-generate-tabular-synthetic-dataset-with-gans-d55fc373c8db
- KLGAN is same code as above but with KL_divergence as the loss function
- WGAN code combines the above code with the following : https://machinelearningmastery.com/how-to-code-a-wasserstein-generative-adversarial-network-wgan-from-scratch/
- an other source for WGAN:https://towardsdatascience.com/how-to-generate-synthetic-tabular-data-bcde7c28038a
- RandomForest regression adapted from here: https://www.kaggle.com/code/rogerbellavista/randomforestregressor-mae-0-0922-rmse-0-2314/notebook

More images and discussions of the result will be added soon.
