# Aspect_Extraction_using_Bi-LSTM_with_Attention

## Overview
This repository contains the implementation of an Aspect Extraction model using a Bidirectional Long Short-Term Memory (Bi-LSTM) network with an Attention mechanism. The model is trained on the SemEval 2014 Task 4 dataset, which is widely used for aspect-based sentiment analysis.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training Details](#training-details)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Aspect Extraction is a crucial task in aspect-based sentiment analysis, where the goal is to identify the aspects or features of a product or service mentioned in a text. This repository leverages a Bi-LSTM network with an Attention mechanism to effectively capture the contextual dependencies and focus on relevant parts of the input text.

## Dataset
The model is trained on the SemEval 2014 Task 4 dataset, which contains annotated customer reviews. The dataset is provided in JSON format and includes various aspects and their corresponding sentiment labels.

## Model Architecture
The model employs a Bidirectional Long Short-Term Memory (Bi-LSTM) network to capture the sequential dependencies in the text. An Attention mechanism is added on top of the Bi-LSTM to focus on the important words in the text, enhancing the model's ability to identify relevant aspects.

## Training Details
- **Epochs**: 50
- **Batch Size**: 32

## Installation
To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/Aspect_Extraction_using_Bi-LSTM_with_Attention.git
cd Aspect_Extraction_using_Bi-LSTM_with_Attention
pip install -r requirements.txt
```

## Usage
1. **Prepare the Dataset**: Ensure the SemEval 2014 Task 4 dataset is in the `data/` directory in JSON format.
2. **Train the Model**: Run the training script.
   ```bash
   python train.py
   ```
3. **Evaluate the Model**: After training, you can evaluate the model using:
   ```bash
   python evaluate.py
   ```

## Results
The model's performance is evaluated based on standard metrics such as Precision, Recall, and F1-score. Detailed results will be provided upon running the evaluation script.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to customize it further based on any additional details or specific requirements you have for your project.
