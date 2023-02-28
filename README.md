# Exploring the Depths of Sound: An Analysis of CNNs for Environmental Sound Classification

This project explores different convolutional neural network (CNN) architectures for environmental sound classification (ESC). The goal of ESC is to identify and categorize sounds in various surroundings, and CNNs have emerged as a powerful tool for this task due to their ability to learn and extract features from raw audio data.

# Introduction

The field of ESC is becoming increasingly important with the rise of audio-based technologies such as smart speakers, virtual assistants, and surveillance systems. The dynamic and unstructured nature of acoustic environments poses a significant practical challenge for designing suitable features for ESC. Many current ESC methods design features based on prior knowledge of acoustic environments and then train a classifier using these features to determine the category probability of each environmental sound signal.

This project explores different CNN architectures for ESC, including traditional Conv-Pool layers, residual layers, and Convolutional Recurrent Neural Networks (CRNNs). The models are built with up to 6 layers, and we experiment with various regularization techniques to optimize their performance. Our results provide a comprehensive analysis of different approaches to ESC, including width scaling, depth scaling, and the use of pooling layers. Additionally, we perform a grid search to fine-tune the hyperparameters of our models.

# Installation

To run the code in this project, use Google Colab or you will need to have the following dependencies installed:

    Python (version 3.6 or later)
    NumPy
    TensorFlow (version 2.0 or later)
    librosa

You can install these dependencies using pip:

pip install numpy tensorflow librosa

# Usage

To run the models, you can use the CNN class and specify the number of layers or filters. Set `residual` to True if you wish to use residual layers.


# Results

Our experiments show that the use of residual layers and CRNNs can improve the performance of CNN architectures for ESC. A quantitative analysis can be found in the report.


# License

This project is licensed under the MIT License - see the LICENSE file for details.
Contact

# Contact

If you have any questions or feedback about this project, please contact the authors at georgepantelimon.prodan@studenti.unipd.it or elaheh.ahmadieslamloo@studenti.unipd.it.
