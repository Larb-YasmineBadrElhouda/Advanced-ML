### Climate Change Analysis and Intelligent Decision Agent

In this project , I implemenetd a complete end-to-end pipeline for : 

\- analyzing Algeria’s climate

\- forecasting future trends

\- building an interactive intelligent agent for querying climate information.

\- It leverages historical climate data, machine learning, reinforcement learning, and interactive visualization.

### GAN-based Cartoon Face Generation

In this Notebook I implemenetd a Generative Adversarial Network (GAN) to generate realistic cartoon faces. 

Using the cartoon-faces-googles-cartoon-set dataset , the model consists of  : 
\- a Generator that transforms random latent vectors into 64×64 RGB images

\- a Discriminator that classifies images as real or fake. 

\- Through adversarial training, the Generator gradually learns to produce images that can fool the Discriminator, while the Discriminator continually improves its ability to distinguish real from generated images.

\- The training process demonstrates the characteristic GAN dynamics, with alternating improvements in both Generator and Discriminator performance.

**Keywords**: Generative Adversarial Network, image synthesis, cartoon faces, adversarial training, PyTorch.

### Watermark Removal with U-Net Autoencoder

This notebook presents my implementation of  a U-Net autoencoder for removing watermarks from images. 

\- Using the CLWD dataset, the model learns a mapping from watermarked images to their clean counterparts. 

\- The encoder extracts hierarchical features and compresses the input, the bottleneck captures high-level patterns differentiating watermark and content, and the decoder reconstructs the clean image. 

\- Skip connections allow fine details from the encoder to aid reconstruction. 

\- The network is trained with a combined loss of pixel-wise L1 and SSIM, balancing numerical accuracy with perceptual similarity.

\- Results demonstrate effective watermark removal while preserving image details, with steady convergence on both training and validation sets.

**Keywords**: U-Net, autoencoder, watermark removal, image restoration, structural similarity, TensorFlow/Keras.

### Conditional Variational Autoencoder for CelebA Smiling Faces 

In this Notebook , I explored the use of Conditional Variational Autoencoders (CVAE) for facial expression generation. 

\- Using the CelebA dataset, a CVAE was trained to generate smiling faces from non-smiling inputs by conditioning both the encoder and decoder on a binary smile label.

\- The model learns a structured latent representation of facial features, enabling controlled manipulation of expressions while preserving individual identity. 

\- Evaluation demonstrates successful generation of realistic smiling faces . 

**Keywords**: Variational Autoencoder, conditional generation, facial expression, CelebA dataset, latent representation.

### Transformer-based Time Series Forecasting of Electricity Consumption

In this notebook I implemented a Transformer neural network for forecasting hourly household electricity consumption.

\- The model leverages self-attention mechanisms and positional encoding to capture temporal dependencies in sequential data. 

\- Using past consumption patterns, the model predicts future values, demonstrating high accuracy in short-term forecasting. 

\- Results indicate that Transformers can effectively model complex temporal structures in time series data, providing a scalable approach for energy demand prediction and temporal pattern learning.

**Keywords**: Transformer, time series forecasting, electricity consumption, self-attention, temporal modeling.

