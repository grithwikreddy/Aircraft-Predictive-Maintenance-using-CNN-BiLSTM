# Aircraft-Predictive-Maintenance-using-CNN-BiLSTM
This project uses a hybrid CNN-BiLSTM model to predict aircraft engine failures with 97.85% accuracy. By analyzing sensor data, it enables early detection, improving safety and reducing maintenance costs through timely alerts and proactive measures.

## Overview
Aircraft safety is paramount, with engine failures posing significant risks. This project leverages a hybrid Convolutional Neural Network (CNN) and Bidirectional Long Short-Term Memory (BiLSTM) model to predict potential aircraft engine failures. By analyzing multivariate time-series data from 21 engine sensors, the system ensures early detection, enabling proactive maintenance and improving aviation safety.

## Features
- **High Accuracy:** Achieves a test accuracy of 97.85%, with precision (96.30%), recall (98.53%), and F1-score (97.33%).
- **Hybrid Model:** Combines CNN for spatial feature extraction and BiLSTM for temporal dependencies.
- **Robust Preprocessing:** Includes advanced techniques for handling high-dimensional and noisy sensor data.
- **Explainability Module:** Identifies influential features to improve model interpretability.
- **Proactive Maintenance:** Enables early failure detection, reducing downtime and costs.

## Dataset
The model was trained and tested on a comprehensive dataset comprising multivariate time-series data from 21 engine sensors, monitoring parameters like:
- Temperature
- Pressure
- Vibration
- Rotational Speed

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/aircraft-predictive-maintenance.git
   cd aircraft-predictive-maintenance
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Preprocess the data:
   ```bash
   python preprocess.py
   ```
2. Train the model:
   ```bash
   python train.py
   ```
3. Evaluate the model:
   ```bash
   python evaluate.py
   ```
4. Run predictions:
   ```bash
   python predict.py --input <path_to_input_data>
   ```

## Results
- **Test Accuracy:** 97.85%
- **Precision (Macro):** 96.30%
- **Recall (Macro):** 98.53%
- **F1-Score (Macro):** 97.33%

## Benefits
- **Enhanced Safety:** Early detection allows timely corrective actions.
- **Cost Savings:** Reduces unplanned downtime and maintenance costs.
- **Explainable AI:** Provides insights into key sensor features influencing predictions.

## Future Work
- Real-time integration with flight management systems.
- Inclusion of additional sensor data.
- Exploration of unsupervised learning for anomaly detection.

## Contributing
Contributions are welcome! Please fork the repository, create a feature branch, and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
Special thanks to the research community and open-source contributors for datasets and libraries that made this project possible.
