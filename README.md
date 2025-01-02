# MLP-Flower-Classification
<p>The provided program implements a MultiLayer Perceptron (MLP) model for classifying flower images into five categories. The program utilizes TensorFlow and Keras, showcasing the process of data augmentation, model creation, training, and evaluation. The images are preprocessed using `ImageDataGenerator` for efficient augmentation and normalization.</p>

### Here's a brief breakdown of the program:
Data Handling: The dataset is extracted from a zip file and structured into training and validation directories.
Data Augmentation: The program applies various transformations such as rotation, zoom, and flipping to enhance the diversity of training data.
Image Normalization: Pixel values are rescaled to the range [0, 1] to ensure consistent input to the model.

### MLP Model Architecture:
Input layer for images of size (150, 150, 3).
Flattening layer to convert image data into a 1D vector.
Two dense (fully connected) hidden layers with ReLU activation.
Output layer with Softmax activation for multi-class classification.
#### Training Process: The model is trained for 30 epochs using the Adam optimizer and categorical cross-entropy loss.
#### Model Evaluation: Tracks accuracy and loss on both training and validation datasets during training.
#### Visualizations: The program plots training and validation loss and accuracy over epochs to assess model performance.
## Install the Package
pip install tensorflow matplotlib
<p>in the terminal of a Python environment</p> <p>Ensure you have TensorFlow and Matplotlib installed before running the program. For TensorFlow installation instructions, visit [TensorFlow Installation](https://www.tensorflow.org/install).</p>

### Running the Program
Dataset Preparation
Extract the flower dataset from the zip file to the appropriate directory.
### On Google Colab
Mount Google Drive and set paths to the dataset accordingly.
### On Local Machine
Ensure the dataset path is correctly set in the script for training and validation directories.
### Execution
Run the script to preprocess the data, train the model, and evaluate its performance. Use the visualizations to analyze results.

## Contributor
<p>Lawrence Menegus</p>
