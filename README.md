# Handwritten Character Recognition

This project uses a Convolutional Neural Network (CNN) to classify handwritten characters (letters and digits) from images. It preprocesses the dataset, builds and trains a CNN model, and evaluates its performance.

# Steps:
1. Dataset Loading: Loads image paths and labels from a CSV file, resizes images to 28x28 pixels, and normalizes them.
2. Preprocessing: Converts images to grayscale, reshapes them, and one-hot encodes the labels.
3. Model Building: Builds a CNN with 2 convolutional layers, max-pooling, fully connected layers, and a softmax output for multi-class classification (62 classes: 0-9, A-Z, a-z).
4. Training: Trains the model for 10 epochs with a batch size of 32, using a validation split.
5. Evaluation: Evaluates the model on a test set and prints the accuracy.

# Project Structure:

Handwritten-Character-Recognition/
├── data/
│   ├── english.csv  # CSV with image paths and labels
│   └── Img/         # Images directory
├── model/
│   ├── cnn_model.py # CNN model architecture
│   └── train_model.py # Script for training
├── notebooks/
│   └── Handwritten_Character_Recognition.ipynb # Jupyter notebook
├── requirements.txt # Python dependencies
└── README.md # Project overview and instructions
```


## License:
This project is licensed under the MIT License.
