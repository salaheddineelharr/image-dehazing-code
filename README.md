# A novel Transformer_based network for image dehazing 

Abstract: Image haze represents a challenging task for computer vision and image processing applications. To reduce/remove the haze from the image, in this paper we propose a novel method that combines convolutional neural networks (CNN) architecture with a Vision Transformer (ViT) network for image dehazing. The proposed method consists of a transformer-based encoder. The feature maps of different scales of the encoder as well as the features map of the first Convolutinal layers are fused at each time followed by convolutional layers to obtain the final output. The proposed method allows to conservation of the high resolution of the image as well as learning from different scales. The performance of our proposed method is evaluated using metrics such as PSNR and SSIM which are widely used in image quality assessment. The obtained results demonstrate a notable enhancement compared to some state-of-the-art methods. Also, the proposed method is trained and tested on four datasets including REalistic Single Image DEhazing (RESIDE) , DENSE-HAZE, O-HAZE, and NH-HAZE, and gives promising results compared to some of the state-of-the-art methods.

---

## 🧰 Requirements

- Python 3.8+
- PyTorch 2.0
- OpenCV
- NumPy
- (Optional) CUDA for GPU acceleration
