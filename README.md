# ViT-Transformer-Replicate with Pytorch
Implementation of Vision Transformer (ViT) in Pytorch. Presented in the paper, An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale

# Model Overall
![image](https://github.com/DanBeverley/ViT-Transformer-Replicate/assets/161696810/8f97616c-e3b0-4d10-b698-5a163ab3613d)

Vision Transformer achieve State-of-the-Art in image recognition task with standard Transformer encoder and fixed-size patches. In order to perform classification, author use the standard approach of adding an extra learnable "classification token" to the sequence.

![image](https://github.com/DanBeverley/ViT-Transformer-Replicate/assets/161696810/be5f9e12-472b-428d-a77b-b51f9339d0fc)


# Implementation

Code was written using Pytorch , trained on CIFAR10 . ViT is a data hungry model , the more data there is the better the model will perform . Feel free to use any dataset you like

