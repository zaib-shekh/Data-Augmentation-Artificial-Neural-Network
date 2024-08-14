# MNIST Handwritten Digit Recognition using ANN with Data Augmentation [![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)

### Overview
This project involves building an Artificial Neural Network (ANN) using TensorFlow to recognize handwritten digits from the MNIST dataset. The MNIST dataset is a large database of 28x28 grayscale images of handwritten digits (0-9), widely used for training various image processing systems.

## Key Features
1. Artificial Neural Network (ANN): The core of this project is an ANN that learns to classify the digits. The architecture includes multiple layers, including dense and dropout layers, to optimize performance and prevent overfitting.

1. Data Augmentation: To enhance the model's robustness, I employed TensorFlow's ImageDataGenerator for data augmentation. This technique generates new training samples by applying random transformations like rotation, zoom, shift, and flip to the existing images. Data augmentation helps the model generalize better by making it less sensitive to the specific characteristics of the training data.

1. Training & Validation: The model is trained on the augmented dataset and evaluated using a validation set. The training process includes monitoring metrics like accuracy and loss to ensure the model's performance is on track.

## Language and Libraries used
<img align="left" alt="Python" width="50px" src="https://imgs.search.brave.com/8-8oAD6jzHKqO6WTV6XaQ1AJZO_DITrF0uoAVo5dlfo/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9zMy5k/dWFsc3RhY2sudXMt/ZWFzdC0yLmFtYXpv/bmF3cy5jb20vcHl0/aG9uZG90b3JnLWFz/c2V0cy9tZWRpYS9j/b21tdW5pdHkvbG9n/b3MvcHl0aG9uLWxv/Z28tb25seS5wbmc" style="padding-right:10px;" />
<img align="left" alt="Pandas" width="50px" src="https://numfocus.org/wp-content/uploads/2016/07/pandas-logo-300.png" style="padding-right:10px;" />
<img align="left" alt="Jupyter Notebook" width="50px" src="https://imgs.search.brave.com/4EmYC1AfgR85pGtDtAiWdobPZ-516SyICT2bao0t0jg/rs:fit:500:0:0/g:ce/aHR0cHM6Ly9yYXcu/Z2l0aHVidXNlcmNv/bnRlbnQuY29tL2dp/dGh1Yi9leHBsb3Jl/L2E0NjkxZjA0ZmYy/MTljMWMyYWEwMmZj/NjFmZGE0MWFhNDNm/MTQ1OWEvdG9waWNz/L2p1cHl0ZXItbm90/ZWJvb2svanVweXRl/ci1ub3RlYm9vay5w/bmc" style="padding-right:10px;" />
<img align="left" alt="Tensorflow" width="50px" height="50" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQEsqbuvRgmIsxTT1R_bCdv8txFKkw2ylx5Lg&s" style="padding-right:10px;" />
<img align="left" alt="Keras" width="50px" src="https://static.javatpoint.com/tutorial/keras/images/keras.png" style="padding-right:10px;" />
