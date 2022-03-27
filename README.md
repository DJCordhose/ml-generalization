# Generalization in Machine Learning

Experiments about generalization of ML systems

## Experiment: Will a convolutional neural network, trained on comic images of animals only, be able to generalize to recognize pictures of actual animals

* Will it be possible to abstract away from a comic nature of training images?
* Will a network be able to grasp the abstract concept in an image like a kid can do?

Progress: https://twitter.com/DJCordhose/status/1508019125800652807

### Datasets

#### Training
* https://www.google.com/search?q=comic%20dog%20images%20collection&tbm=isch&ved=2ahUKEwi1n9uwxd72AhXawAIHHV_oA9EQ2-cCegQIABAA&oq=comic%20dog%20images%20collection&gs_lcp=CgNpbWcQAzoECAAQEzoICAAQCBAeEBM6BAgAEB46BggAEAgQHlDVBFi2EGDFE2gAcAB4AIABUogB4waSAQIxMpgBAKABAaoBC2d3cy13aXotaW1nwAEB&sclient=img&ei=Skg8YrXSLtqBi-gP39CPiA0&bih=888&biw=1440&rlz=1C1CHBF_deDE981DE981&authuser=0

#### Validation
* https://www.kaggle.com/competitions/dogs-vs-cats/data
* 

### Advanced
* Maybe a pretrained autoencoder on comic images and real world images used as a pretraining step?


## Experiment: Can we teach a model to make a connection from comic to real? 

* Can we get a real world image for a comic figure?
  * The other way round (more abstract) should be doable anyway
* Autoencoder?
* GAN?