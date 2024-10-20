# DDoS Attack Detection using Machine Learning

This project implements a machine learning-based approach to detect Distributed Denial of Service (DDoS) attacks in network traffic.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project aims to detect DDoS attacks in real-time using machine learning techniques. By analyzing network traffic patterns, our model can identify potential DDoS attacks with high accuracy, allowing for quick response and mitigation.
This Project has been devploped as part of my thesis in Cyprus Inrtnatinoal University.
## Features

- Real-time DDoS attack detection
- High accuracy and low false-positive rate
- Scalable to handle large volumes of network traffic
- Easy integration with existing network security systems

## Requirements

- Python 3.8+
- TensorFlow 2.4+
- Scikit-learn 0.24+
- Pandas 1.2+
- NumPy 1.19+

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/ddos-detection-ml.git
   cd ddos-detection-ml
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your dataset (see [Dataset](#dataset) section for details).

2. Train the model:
   ```
   python train_model.py --data_path /path/to/your/dataset
   ```

3. Run the detection script:
   ```
   python detect_ddos.py --model_path /path/to/saved/model
   ```

## Results

Our current model achieves:
- Accuracy: 99.2%
- Precision: 98.7%
- Recall: 99.5%
- F1-Score: 99.1%


## to implment this project fork it or clone it and train and test on data sets that compatible with the code.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
