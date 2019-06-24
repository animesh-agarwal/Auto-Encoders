# Auto-Encoders
This repository contains code examples for autoencoders using Tensorflow


* **Reverse Image Search** - CNN model is used to learn the latent represenations of the Fashion-MNIST dataset. The dataset contains 60000 train samples and it is comprised of 10 product categories. The encodings are indexed using Annoy to perform fast retrieval of similar images. Some sample images are
![alt text](https://github.com/animesh-agarwal/Auto-Encoders/blob/master/images/fashion_dataset.png)

The rencostructed images are 

![alt text](https://github.com/animesh-agarwal/Auto-Encoders/blob/master/images/fashion_reconstructed.png)

For the query image, 

![alt text](https://github.com/animesh-agarwal/Auto-Encoders/blob/master/images/query_image.png)

Similar images are 

![alt text](https://github.com/animesh-agarwal/Auto-Encoders/blob/master/images/similar_images.png)


* **Simple Auto Encoder** - Network with one hidden layer is trained on MNIST Dataset
* **Convolutional Auto Encoder** - CNN model is used to learn the latent representations of the MNIST Dataset. 
Original vs reconstructed images

![alt text](https://github.com/animesh-agarwal/Auto-Encoders/blob/master/images/reconstructed.png)

* **Denoising Convolutional Auto Encoder** - CNN model is trained to remove noise from the original images. 
![alt text](https://github.com/animesh-agarwal/Auto-Encoders/blob/master/images/denoising.png)

