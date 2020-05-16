## GANs used for face generation
This project was completed as a part of Udacity's Deep Learning Nanodegree.<br />
GANs short for Generative Adversarial Networks consist of two neural networks(Generator network and Discriminator network) contesting with each other in a game. The generator's role is to output realistic data(face images in this case). The discriminator's role is differentiate between real data and manufactured data. The generator network learns to output realistic data  to fool the dicriminator and discriminator learns to differentiate the generator's data from real data. Both networks get better over time. Eventually, the generator is able to produce data passable as real data. To learn more about Generative Adversarial Networks you can check out Google's tutorial [here](https://developers.google.com/machine-learning/gan).

## Dataset
This uses the celebA dataset put together by Liu et al.
You can download the dataset [here](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html).

## Honor System
I am leaving this open source on the honor system. Please do not plagarize my code! You will only learn by investing the time to work through the projects yourself!

## Requirements
- Jupyter Notebook
- Python 3
- Numpy
- Pytorch
- Torchvision
