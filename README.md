# AI2025-EMI
**AI Journey 2025 in CHU**

![image](https://github.com/user-attachments/assets/568f1c12-eaa2-49b6-ae9a-e213f09bb4e9)

### 1. **Generative Adversarial Networks (GANs)**  
GANs are a type of generative model composed of two neural networks: a **Generator** and a **Discriminator**, which compete against each other in an adversarial training process to improve the quality of generated data.  
- **Generator**: Creates fake samples from random noise, trying to deceive the discriminator.  
- **Discriminator**: Distinguishes between real and generated data, providing feedback on authenticity.  
- Through this competition, the generator learns to produce high-quality data that closely resembles real samples.  
- Typical applications include image generation (e.g., StyleGAN), super-resolution (e.g., SRGAN), and image-to-image translation (e.g., CycleGAN).  

---

### 2. **Variational Autoencoders (VAE)**  
VAEs are a type of probabilistic generative model based on the **Autoencoder** architecture but incorporate stochastic variables during encoding to ensure smooth and continuous data generation.  
- Consist of an **Encoder** and a **Decoder**:  
  - **Encoder** maps input data to a latent space representation.  
  - **Decoder** generates new data from the latent space, ensuring that the generated samples match the real data distribution.  
- VAEs maximize the **Evidence Lower Bound (ELBO)** through variational inference, ensuring that the latent variables follow a Gaussian distribution for efficient sample generation.  
- Applications include image generation (e.g., VAE-GAN), style transfer, and feature learning.  

---

### 3. **Transformer (e.g., GPT-4)**  
The Transformer is a neural network architecture based on the **Self-Attention Mechanism**, excelling in handling sequential data and widely used in Natural Language Processing (NLP).  
- **Key Technologies**:  
  - **Self-Attention Mechanism**: Allows the model to focus on different parts of a sequence, solving long-range dependency issues.  
  - **Multi-Head Attention**: Enhances the model’s ability to capture diverse features.  
  - **Positional Encoding**: Provides sequence order information to compensate for the lack of CNNs/RNNs.  
- **Features of GPT-4**:  
  - A **autoregressive Transformer model**, predicting the next token in a sequence for language modeling.  
  - Trained on **large-scale datasets with deep learning**, resulting in strong contextual understanding.  
  - Supports **multimodal learning**, allowing it to process text, images, and more.  
- It is widely used in **machine translation (e.g., DeepL)**, **chatbots (e.g., ChatGPT)**, **text generation (e.g., Bard, Claude)**, and **code assistance (e.g., GitHub Copilot)**.  

