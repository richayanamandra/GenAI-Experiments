# Objective

## Pix2Pix (GAN-Based Image-to-Image Translation)
To implement Pix2Pix GAN using a U-Net generator and PatchGAN discriminator and compare results with CNN.

### Generator: U-Net, Discriminator: PatchGAN
1.	To understand paired image-to-image translation using GANs
2.  To implement Pix2Pix architecture with:
•	U-Net Generator
•	PatchGAN Discriminator
3. To train the model using adversarial + reconstruction loss
4.  To compare Pix2Pix outputs with baseline CNN encoder–decoder

## Pix2Pix Architecture
Pix2Pix is a conditional GAN (cGAN) consisting of:

### Generator (G): U-Net
•	Encoder–decoder CNN with skip connections
•	Preserves low-level spatial features
•	Reduces information loss caused by pooling
### Discriminator (D): PatchGAN
•	Classifies local image patches as real or fake
•	Encourages sharpness and texture realism

## Task 1: Dataset Preparation
•	Use paired images (Edges → Real Images)
•	Dataset may be used Edges2Shoes
•	Split into training and testing sets

## Task 2: Implement U-Net Generator
•	Downsampling blocks with convolution
•	Upsampling blocks with skip connections

## Task 3: Implement PatchGAN Discriminator
•	Convolutional layers
•	No fully connected layers
•	Output patch-level authenticity map

## Task 4: Model Training
•	Optimizer: Adam
•	Learning rate: 0.0002
•	Losses:
o	Adversarial loss
o	L1 reconstruction loss
•	Alternate training of Generator and Discriminator

## Task 5: Performance Comparison
Compare:
•	Pix2Pix GAN with Baseline CNN Encoder–Decoder
