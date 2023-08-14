# De-Noise
This project is based on Speech Enhancement using deep learning techniques.
Speech enhancement is task of taking a noisy speech input and producing an enhanced speech output.

# Main implementation
The main implementation of the project is done in Final.ipynb

## Content covered

- Python, git basics
- ML Crash Course by Google (up to embeddings)
- Udacity course on TensorFlow (modules 2,3,4,5,6)
- ResNet architecture
- YouTube series on GANs
- GAN implementation on MNIST

  - Can be found in GAN_digits.ipynb
  - It includes the use of GANs to generate images of digits similar to MNIST images

- RNN part from Sequence Models course of Deep Learning Specialization on Coursera
- Autoencoder model implementation

  - Can be found in Autoencoder.ipynb
  - It includes the use of encoder and decoder in ResNet architecture form to perform noise suppression.
  - The dataset used here can be downloaded from https://datashare.ed.ac.uk/bitstream/handle/10283/1942/clean_trainset_wav.zip?sequence=1&isAllowed=y and https://datashare.ed.ac.uk/bitstream/handle/10283/1942/noisy_trainset_wav.zip?sequence=2&isAllowed=y

- SEGAN paper & its implementation
- 
  - The paper is available at https://arxiv.org/abs/1703.09452
  - Can be found in Final.ipynb
  - It includes the use of GAN as per the paper to generate clean signal from noisy input
