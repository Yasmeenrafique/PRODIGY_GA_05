# 🧠 Neural Style Transfer using Deep Learning (VGG19)

This project implements **Neural Style Transfer (NST)** using a **pre-trained VGG19 Convolutional Neural Network**.  
The model takes a **content image** and a **style image** and generates a new image that preserves the content while applying the artistic style.

This project demonstrates the use of **deep learning, CNN feature extraction, Gram matrices, and optimization-based image generation**.

---

## 📌 Project Objective

To generate an artistic image by:
- Preserving the structure of a content image  
- Applying the artistic texture and color patterns of a style image  

This is achieved using **feature maps extracted from VGG19** and optimized through **backpropagation**.

---

## 🛠️ Technologies Used

- Python  
- PyTorch  
- Torchvision  
- VGG19 Pre-trained Model  
- PIL (Image Processing)  
- Matplotlib  
- Google Colab 

---

---

## ⚙️ How the System Works

1. Load the **content** and **style** images  
2. Load **VGG19** pre-trained CNN  
3. Extract deep features from both images  
4. Compute **Gram matrices** for style representation  
5. Create a trainable **target image**  
6. Minimize **content loss + style loss**  
7. Iteratively update the target image using **backpropagation**  
8. Generate the final stylized image  

---

## 📊 Loss Functions

### Content Loss  
Measures how much the generated image differs from the original content.

### Style Loss  
Measures how much the textures and patterns differ from the style image using **Gram Matrices**.

### Total Loss 
Total Loss = Content Loss + Style Loss

## 🎯 Key Learning Outcomes

- Understanding CNN feature extraction  
- Gram Matrix computation  
- Image optimization using gradient descent  
- Practical implementation of Neural Style Transfer  
- Using pre-trained deep learning models  

---

**Yasmeen Rafique**  
Neural Style Transfer Project

