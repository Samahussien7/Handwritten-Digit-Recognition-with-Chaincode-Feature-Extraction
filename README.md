# Handwritten-Digit-Recognition-with-Chaincode-Feature-Extraction
This  script recognize handwritten digits using the MNIST dataset. Implementation using chaincode-based feature extraction, which offers an alternative method for capturing relevant information from digit images. The script divides the data into training and testing sets, utilizes a classifier, and evaluates its accuracy.

# Steps:

## Load MNIST Dataset:

Acquires the MNIST dataset containing images of handwritten digits along with their corresponding labels.

## Variable Number of Blocks:

Partitions each image into a variable number of blocks (e.g., 9 blocks) to facilitate more detailed feature extraction.

## Chaincode Feature Extraction:

Computes the chaincode for each block within the image.
Utilizes the chaincode as features for training the classifier.
Implements chaincode extraction logic without relying on built-in functions.

## Split Data into Train and Test Sets:

Divides the dataset into training and testing sets, typically adhering to a predefined split ratio such as 70-30%.

## Choose Classifier:

Selects a classifier from available options, such as Support Vector Machine (SVM), Random Forest, or k-Nearest Neighbors (k-NN).

## Train Classifier:

Trains the chosen classifier using the chaincode features extracted from the training set.

## Evaluate Accuracy:

Tests the trained classifier on the testing set to evaluate its accuracy.
Computes the accuracy metric, representing the percentage of correctly classified digits.
