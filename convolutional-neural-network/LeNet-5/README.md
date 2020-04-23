## [Paper](http://www.dengfanxin.cn/wp-content/uploads/2016/03/1998Lecun.pdf)

<pre>
@article{lecun1998gradient,
  title={Gradient-based learning applied to document recognition},
  author={LeCun, Yann and Bottou, L{\'e}on and Bengio, Yoshua and Haffner, Patrick},
  journal={Proceedings of the IEEE},
  volume={86},
  number={11},
  pages={2278--2324},
  year={1998},
  publisher={Ieee}
}
</pre>

## Description
LeNet-5 is a convolutional neural network architecture first introduced by LeCun et al. in 1998. It was primarily implemented for OCR and character recognition in documents. Here, I train LeNet-5 on the MNIST dataset for digital recognition. In a way, LeNet-5 + MNIST is the "Hello, World" equivalent of deep learning for image classification.

## MNIST Datasets
The MNIST dataset contains 70,000 images of  handwritten digits (0-9) . The goal of the dataset is usually to classify the digits in the images. Each digit is represented as a 28x28 grayscale image. The digits are placed on a black background with a light foreground. The grayscale pixel intensities are unsigned integers with values in the range [0, 255].

## Helpful Resources
1. [LeNet-5 - A Classic CNN Architecture](https://engmrk.com/lenet-5-a-classic-cnn-architecture/)
2. [Extending PyTorch with Custom Activation Functions](https://towardsdatascience.com/extending-pytorch-with-custom-activation-functions-2d8b065ef2fa)
