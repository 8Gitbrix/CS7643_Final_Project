# CS7643_Final_Project
Using VAEs to train classifiers.

To run our code, colab is required. Upload the folder into google drive and then run the notebooks on colab. This is becuase we use colab specific functions like cd to move into this specific folder on drive. Make sure the folder name is the same.

The colab notebooks that utilize the quick draw dataset require our data of 10 selected sketch classes to be downloaded. Run the prepare_data.pynb colab file in drive once you upload the project to drive. Alternatively, those functions can be run to download the specific classes that we used which are: (tree, t-shirt, ice cream, fish, face, car, bowtie, apple, flamingo, sheep). We also included links to the three zip files (train, test, and validation data) here: https://drive.google.com/drive/folders/1mPzPcvFgIhEz4U2eEmz32ZHQOQoGkUcL?usp=sharing. 

## Important File Descriptions:
* `beta_vae.ipynb` - notebook for our beta-VAE trained on the MNIST dataset.
* `bvae_classifier_mnist_v4.ipynb` - Two layer fully connected classifier that trains on the encoded representations of the beta-vae (`bVAE.pt`) on the MNIST dataset.
* `bvae_classifier_mnist_v3.ipynb` - Five layer fully connected classifier that trains on the encoded representations of the beta-vae (`bVAE.pt`) on the MNIST dataset.
* `beta_vae_quickdraw.ipynb` - notebook for our beta-VAE trained on the Quick Draw dataset.
* `beta_vae_fashionMNIST.ipynb` - notebook for our beta-VAE trained on the fashion MNIST dataset.
* `bvae_classifier_fashionMNIST.ipynb` - Five layer fully connected classifier that trains on the encoded representations of the beta-vae (`bVAE.pt`) on the fashionMNIST dataset.
* `vae_classifier_mnist_v3.ipynb` - Five layer fully connected classifier fully connected classifier that trains on the encoded representations of a simple VAE (`vae_epoch_25.pt`) on the MNIST dataset.
* `hybridvae_classifier_mnist.ipynb` - VAE but with the decoder swapped with a classifier. Model did not train well, so stopped training
