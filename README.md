# GAN Based Synthetic Image Generation

**Part A – Dataset Preparation and Image Preprocessing:** The MNIST handwritten digit dataset is loaded using TensorFlow/Keras. The dataset is explored by checking the number of training and testing images, image dimensions, and sample images. The pixel values are normalized from **0–255 to -1 to 1**, and the images are reshaped into the required input format. A TensorFlow data pipeline is created to prepare the dataset for batch-wise training.

**Part B – Implementing the Generator:** A Generator network is created to generate synthetic handwritten digit images from a random noise vector. Dense and transposed convolutional layers are used to transform the random noise into a **28 × 28 grayscale image**. Suitable activation functions are applied, and a sample generated image is displayed before GAN training. The Generator model architecture and summary are also displayed.

**Part C – Implementing the Discriminator and GAN Model:** A Discriminator network is implemented to distinguish between real MNIST images and synthetic images produced by the Generator. Convolutional layers are used to extract image features, followed by a final output layer for classification. The Discriminator is compiled using the **Adam optimizer and Binary Cross-Entropy loss**. The Generator and Discriminator are combined to form the GAN model, and their model summaries are displayed.

**Part D – GAN Training and Synthetic Image Generation:** The Generator and Discriminator are trained using random noise, real MNIST images, and generated synthetic images. During training, the Generator tries to create realistic images while the Discriminator tries to identify fake images. Generator and Discriminator losses are recorded, and generated images are visualized at different training stages. Real and generated images are compared, and the final synthetic images are saved for further analysis.

# 24ADI006_RAMYA-R_24BAD096_EX_7
