# Pix2Pix: AI Powered Sattelite Mapping Tool

This [Pix2Pix paper](https://arxiv.org/abs/1611.07004v3) implementation is based on the YouTube video tutorial by Aladdin Persson, with slight modifications. It includes pre-trained weights and the required training loop, discriminator, and inference code blocks for running and testing the model. With this implementation, users can easily train and test the Pix2Pix model for image-to-image translation tasks.

<h2 align="center"></h1>

<p float="left" align="middle">
  <img src="https://media.discordapp.net/attachments/1099355697671569408/1100487535966298142/transferir.png" width="65%" hspace="0"/>
</p>
</p>
<p float="left" align="middle">
  <img src="https://media.discordapp.net/attachments/1099355697671569408/1100487535563649064/transferir_2.png" width="65%" hspace="0"/>
</p>

The Pix2Pix paper, published by Isola et al. in 2017, introduced a novel approach to image-to-image translation tasks. Unlike previous approaches, which relied on manual feature engineering and complex pipelines, the Pix2Pix model used deep convolutional neural networks to learn the mapping between input and output images directly from data. The model is trained using a combination of adversarial loss and L1 loss, which encourages the generated images to be both realistic and similar to the ground truth images. Since its introduction, the Pix2Pix model has been used for a wide range of image-to-image translation tasks, including style transfer, super-resolution, and image colorization.

<p float="left" align="middle">
 <img src="https://neurohive.io/wp-content/uploads/2018/11/Capture-10-770x507.jpg" width="65%" hspace="0"/>
</p>
