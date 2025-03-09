Face Image Generation with GANs
This project is a PyTorch implementation of a Generative Adversarial Network (GAN) designed to generate realistic face images. The GAN is trained on the CelebA dataset, a large collection of aligned celebrity face images, to produce 64x64 pixel outputs. The generator creates images from random noise, while the discriminator evaluates their realism, leading to a competitive training process that refines the generated faces over time.
The implementation includes a custom dataset loader to handle CelebA images, a deeper architecture inspired by DCGAN for better feature learning, and training enhancements like weight initialization and label smoothing to stabilize the process. The goal is to create face-like images that improve in quality with training, starting from abstract shapes and progressing toward recognizable facial features.

Dataset
The project uses the CelebA dataset, which contains over 200,000 celebrity images with aligned faces.

Kaggle CelebA Dataset link:- https://www.kaggle.com/jessicali9530/celeba-dataset
Place the unzipped img_align_celeba folder in the project directory and update the folder_path variable in the code to point to your dataset location.
