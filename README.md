# U-Net Image Segmentation Using Keras

Image segmentation is a computer vision task that segments an image into multiple areas by assigning a label to every pixel of the image. It provides much more information about an image than object detection, which draws a bounding box around the detected object, or image classification, which assigns a label to the object.

# U-Net Architecture

U-Net was introduced in the paper, U-Net: Convolutional Networks for Biomedical Image Segmentation. The model architecture is fairly simple: an encoder (for downsampling) and a decoder (for upsampling) with skip connections. As Figure shows, it shapes like the letter U hence the name U-Net.
![1_unet_architecture_paper-1536x853](https://user-images.githubusercontent.com/88283732/193401321-a288d10d-f866-4230-92b9-a1c9073a6fc4.jpeg)


# Data Set

The Oxford-IIIT pet dataset, available as part of the TensorFlow Datasets (TFDS). It can be easily loaded with TFDS, and then with a bit of data preprocessing, ready for training segmentation models.

<img width="949" alt="Screenshot 2022-10-01 at 2 19 12 PM" src="https://user-images.githubusercontent.com/88283732/193401381-f339b8f4-33f0-420e-824d-31ce257bd31a.png">


# Output After Model Training
The true masks, and the masks predicted by the U-Net model we trained.

<img width="962" alt="Screenshot 2022-10-01 at 12 33 31 PM" src="https://user-images.githubusercontent.com/88283732/193397395-259e7c29-b3af-4309-bb2c-9c8ee3e7b78a.png">
