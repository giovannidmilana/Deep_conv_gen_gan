# 1. Deep Convolutional Generative Adversarial Network
This code base uses tensor-flow to make two neural networks, one classifying images as being either real or fake and the other generates 128x128x3 images from a 100 interger Gaussian noise distribution. Using gradients derived from the loss(Binary Cross Entropy)the two networks train in unison with a goal of reaching a state Nash equilibrium. That is the classifying network can no longer distinguish between real or generated images beyond resorting to a coin toss and half the images produced by the generator are labeled as real by the discriminator and the other half as fake, thus reaching convergence. The dataset used to train the discriminator was 30,000 images of faces from the ([Large-scale CelebFaces Attributes (CelebA) Dataset](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html).

## Examples:
![photo 1](images/Gen_face1.png)

![photo 1](images/Gen_face2.png)

![photo 1](images/Gen_face3.png)

![photo 1](images/Gen_face4.png)

![photo 1](images/Gen_face5.png)

![photo 1](images/Gen_face6.png)

![photo 1](images/Gen_face7.png)

![photo 1](images/Gen_face8.png)

![photo 1](images/Gen_face9.png)

![photo 1](images/Gen_face10.png)

![photo 1](images/Gen_face11.png)

![photo 1](images/Gen_face12.png)

![photo 1](images/Gen_face13.png)

![photo 1](images/Gen_face14.png)

![photo 1](images/Gen_face15.png)

![photo 1](images/Gen_face16.png)

![photo 1](images/Gen_face17.png)

# Deep_conv_gen_gan
# Deep_conv_gen_gan
