# First TensorFlow Model

## Project Description

This project demonstrates a simple TensorFlow model created in Google Colab.

The model is trained to learn the relationship:

**y = 2x**

After training, the model predicts new values and compares the predicted values with the actual values.

## Technologies Used

- Python
- TensorFlow
- NumPy
- Matplotlib
- Google Colab

## Training Data

The model is trained using:

- Input: `[1, 2, 3, 4, 5]`
- Output: `[2, 4, 6, 8, 10]`

## Model Details

- Neural Network: Dense Layer
- Optimizer: SGD
- Loss Function: Mean Squared Error
- Epochs: 500

## Prediction Results

| Input | Predicted | Actual |
|------:|----------:|-------:|
| 6 | 11.96 | 12.00 |
| 7 | 13.94 | 14.00 |
| 8 | 15.93 | 16.00 |
| 9 | 17.91 | 18.00 |
| 10 | 19.89 | 20.00 |

## Output

The model successfully learns the relationship `y = 2x`.

A graph is included in the notebook to compare the **Predicted** and **Actual** values.

## File

`first_tensorflow_model.ipynb` – Complete Google Colab notebook containing the code, training, predictions, and graph.
