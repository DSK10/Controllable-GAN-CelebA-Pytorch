# Controllable-GAN-CelebA-Pytorch
Like in Conditional GAN we generated images based on classes, similarly in this Controllable GAN we can change specific features.
Here the latent space vector is updated by the information provide with a new classifier that classifies features in a generated images.
This info is used to move in a direction of a desired feature.
To encourage disentanglement a loss function is used (eg, BCE, W-loss)


Due to large filesize of a pretrained model of a classifier there isn't any model uploaded, 
you can train a new model or download via internet sources
