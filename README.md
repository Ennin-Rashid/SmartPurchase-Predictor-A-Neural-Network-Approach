# SmartPurchase Predictor: A Neural Network Approach

This project demonstrates a simple neural network model for predicting purchase behavior based on user activity data. It employs Python, NumPy, Pandas, scikit-learn, and TensorFlow/Keras to generate synthetic data, train a binary classifier, and evaluate its performance.

## Features

- Generates synthetic user activity data (visit duration, pages visited)
- Binary classification: predicts whether a purchase occurs
- Train/test data split with reproducible results
- Neural network implementation using TensorFlow/Keras
- Model performance evaluation on a held-out test set

## Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ennin-Rashid/SmartPurchase-Predictor-A-Neural-Network-Approach.git
   cd SmartPurchase-Predictor-A-Neural-Network-Approach
   ```

2. **Install requirements**
   ```bash
   pip install -r requirements.txt
   ```
   *(If `requirements.txt` is not present, install: numpy, pandas, scikit-learn, tensorflow)*

3. **Run the notebook**
   - Open `NeuralNetwork.ipynb` in Jupyter Notebook or any compatible environment.
   - Execute the cells in order to generate data, train the model, and evaluate accuracy.

## Project Structure

- `NeuralNetwork.ipynb` — Main Jupyter notebook containing all code and documentation

## Results

- Achieves approximately 72% accuracy on synthetic binary classification.

## Requirements

- Python 3.7+
- NumPy
- Pandas
- scikit-learn
- TensorFlow (>=2.x)

## License

This project is open source and available under the [MIT License](LICENSE).
