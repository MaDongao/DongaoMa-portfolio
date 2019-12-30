---
title: SiftingGAN
published: true
---

[1] SiftingGAN: Generating and Sifting Labeled Samples to Improve the Remote Sensing Image Scene Classification Baseline In Vitro, IEEE Geoscience and Remote Sensing Letters , 01/14/2019
<https://ieeexplore.ieee.org/document/8611213>

**Abstract**:
Lack of annotated samples greatly restrains the direct application of deep learning in remote sensing image scene classification. Although research studies have been done to tackle this issue by data augmentation with various image transformation operations, they are still limited in quantity and diversity. Recently, the advent of the unsupervised learning-based generative adversarial networks (GANs) brings us a new way to generate augmented samples. However, such GAN-generated samples are currently only served for training GANs model itself and for improving the performance of the discriminator in GANs internally (in vivo). It becomes a question of serious doubt whether the GAN-generated samples can help better improve the scene classification performance of other deep learning networks (in vitro), compared with the widely used transformed samples. To answer this question, this letter proposes a SiftingGAN approach to generate more numerous, more diverse, and more authentic labeled samples for data augmentation. SiftingGAN extends tradition a l G AN framew ork w ith an Online-Output method for sample generation, a Generative-Model-Sifting method for model sifting, and a Labeled-Sample-Discriminating method for sample sifting. Experiments on the well-known aerial image data set demonstrate that the proposed SiftingGAN method can not only effectively improve the performance of the scene classification baseline that is achieved without data augmentation but also significantly excels the comparison methods based on traditional geometric/radiometric transformation operations.

![](https://github.com/MaDongao/DongaoMa-portfolio/master/assets/SiftingGAN.png)
