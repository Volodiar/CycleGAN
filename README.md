# CycleGAN

Unpaired image to image translation using Cycle-Consistent Adversarial Networks. 

CycleGAN uses a cycle consistency loss to enable training without the need for paired data. In other words, it can translate from one domain to another without a one-to-one mapping between the source and target domain.

This opens up the possibility to do a lot of interesting tasks like photo-enhancement, image colorization, style transfer, etc. All you need is the source and the target dataset (which is simply a directory of images).

https://www.tensorflow.org/tutorials/generative/cyclegan