# Face_mask_detection

## Table of Contents
1. [Project Description](#project-description)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Features](#features)
5. [Contributing](#contributing)
6. [License](#license)

---

## 1. Project Description

This project aims to detect whether a person is wearing a face mask or not using deep learning techniques. It utilizes TensorFlow and Keras to build and train a neural network model for this task. With the increasing importance of face mask compliance in various settings, this project can be used for real-world applications such as monitoring public spaces, healthcare, and more.

## 2. Installation

To use this Face Mask Detection system, follow these installation steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/face-mask-detection.git
   ```

2. Install the required Python dependencies using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. Download the pre-trained model weights (if provided) or train your own model (instructions in the Usage section).

## 3. Usage

### Training a Model

To train your own face mask detection model, follow these steps:

1. Prepare your dataset, organizing it into two classes: "with_mask" and "without_mask."

2. Use the provided training script to train the model:
   ```bash
   python train.py --dataset /path/to/dataset --model /path/to/save/model
   ```

### Testing and Inference

To perform face mask detection on images or video streams, you can use the trained model:

1. Use the provided inference script to detect masks on images:
   ```bash
   python detect.py --image /path/to/image --model /path/to/model
   ```

2. To perform real-time mask detection on a webcam feed, use the following command:
   ```bash
   python webcam.py --model /path/to/model
   ```

## 4. Features

- Real-time face mask detection.
- Easy-to-use training and inference scripts.
- Ability to use pre-trained or custom-trained models.
- Adaptable for various use cases.

## 5. Contributing

Contributions to this project are welcome! To contribute, please follow the guidelines outlined in [CONTRIBUTING.md](CONTRIBUTING.md). We appreciate your help in improving this project.

## 6. License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute this project in accordance with the terms specified in the license.

---

### Additional Information

For any questions, suggestions, or bug reports, please feel free to contact us at anandaparna1203@gmail.com(mailto:anandaparna1203@gmail.com). We appreciate your interest in our Face Mask Detection project.
```
