# CS7643_Final_Project
Using VAEs to train classifiers.

To run our code, colab is required. Upload the folder into google drive and then run the notebooks on colab. This is becuase we use colab specific functions like cd to move into this specific folder on drive. Make sure the folder name is the same.

## Important File Descriptions:
* `beta_vae.ipynb` - notebook for our beta-VAE trained on the MNIST dataset.
* `bvae_classifier_mnist_v4.ipynb` - Two layer fully connected classifier that trains on the encoded representations of the beta-vae (`bVAE.pt`) on the MNIST dataset.
* `bvae_classifier_mnist_v3.ipynb` - Five layer fully connected classifier that trains on the encoded representations of the beta-vae (`bVAE.pt`) on the MNIST dataset.
* `beta_vae_quickdraw.ipynb` - notebook for our beta-VAE trained on the Quick Draw dataset.
* `vae_classifier_mnist_v3.ipynb` - Five layer fully connected classifier fully connected classifier that trains on the encoded representations of a simple VAE (`vae_epoch_25.pt`) on the MNIST dataset.
