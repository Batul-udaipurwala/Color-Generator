# Color-Generator
This project predicts a unique RGB color representation for a given name using a trained deep-learning model. It leverages tokenization, one-hot encoding, and sequence padding to preprocess names, enabling the model to learn patterns and map text inputs to color outputs.


##Introduction


This project demonstrates how deep learning can be applied to generate color mappings for text inputs, specifically names. It tokenizes input names at the character level, preprocesses them for model compatibility, and predicts RGB values using a trained neural network.


##Features


Character-Level Tokenization: Converts input names into sequences of numerical tokens.

One-Hot Encoding and Padding: Ensures consistent input size for the model.

Deep Learning Prediction: Maps names to RGB color codes.

Visualization: Displays the predicted RGB color.


##Model Details


Architecture:

Embedding layer for tokenized input.

LSTM layer to capture sequential patterns in names.

Dense layers to map LSTM outputs to RGB values.

Input: Character-level tokenized names (padded and one-hot encoded).

Output: Three continuous values representing RGB.
