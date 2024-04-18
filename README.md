Generating Cartoon faces with GANs
What is GANs

A Generative Adversarial Network (GAN) is a type of machine learning framework consisting of two neural networks that use deep learning techniques to improve their accuracy by competing against each other.

For our second project, we're going to work with two neural networks: a Generator and a Discriminator. The Generator's job is to create a "fake" sample from a random vector or matrix, while the Discriminator's task is to figure out if a sample is "real" (selected from the training dataset) or "fake" (created by the Generator). The training process involves alternating between training the Discriminator for several epochs and then the Generator for a similar number of epochs. By doing this, both networks gradually improve at their respective tasks.

We're going to work with Google's Cartoon Dataset, available on Kaggle. This dataset consists of a random assortment of 2D cartoon avatar images. These cartoons differ across 10 artwork categories, 4 color categories, and 4 proportion categories, offering around 1013 different possible combinations in total.(https://www.kaggle.com/datasets/brendanartley/cartoon-faces-googles-cartoon-set/code),
