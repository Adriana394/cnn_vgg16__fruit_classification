
# Small Customer CNN & VGG16 for Fruit Classification

This project is aimed at building and comparing two models, a small Convolutional Neural Network (CNN) and the VGG16 architecture, for the purpose of classifying fruits, vegetables, and nuts using the Fruits-360 dataset from Kaggle.

## About the Dataset
The Fruits-360 dataset (Version: 2020.05.18.0) consists of images of various fruits, vegetables, and nuts. Here are some key details:

*__Total Images__*: 90,483

__*Training Set Size*__: 67,692 images (100x100 pixels)

*__Test Set Size__*: 22,688 images (100x100 pixels)

*__Number of Classes__*: 131

*__Image Format__*: Each image is named with a format like image_index_100.jpg or variations (r_image_index_100.jpg, r2_image_index_100.jpg).

The dataset includes a wide range of classes such as apples (various types), bananas, blueberries, cactus fruit, eggplants, lemons, pineapples, strawberries, tomatoes, and more.

## Tools and Libraries
*__Scikit-Learn__*: For data preprocessing and evaluation metrics.

*__TensorFlow & Keras__*: For building and training the neural network models.


## Project Structure

The project consists of the following main components:

*__Data Preprocessing__*: Images are loaded, resized to 100x100 pixels, and normalized for model training.

*__Model Architectures__*:

Small CNN: A custom CNN architecture designed for this task.

VGG16: Transfer learning using the pre-trained VGG16 model.

*__Training and Evaluation__*: Models are trained on the training dataset and evaluated using the test dataset.

*__Comparison__*: Performance metrics and visualizations are used to compare the Small CNN and VGG16 models.

*__References__*
Fruits-360 Dataset: *[Kaggle](https://www.kaggle.com/datasets/moltean/fruits)*