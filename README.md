# Facial Emotion Recognition

## Introduction
This project applies computer vision and deep learning techniques to recognize and classify facial emotions from video input. Leveraging the power of convolutional neural networks (CNN) and transfer learning, the system is capable of understanding visual cues to accurately identify human emotions.

## Table of Contents
- [Introduction](#introduction)
- [Methodology](#methodology)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)
- [References](#references)

## Methodology
The methodology employs transfer learning on well-known architectures such as MobileNet, adapting these models to classify seven distinct facial emotions. The project uses the FER-2013 dataset, which is preprocessed to meet the input requirements of the neural network.

## Dataset
The FER-2013 dataset, originally compiled by Ian Goodfellow, contains 28,709 grayscale images categorized into the following emotions:
- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

## Installation
To set up the project environment, follow these steps:

1. Ensure Python 3 is installed on your system.
2. Create and activate a virtual environment:

    ```
    bash
    python -m venv venv
    # On Unix/macOS
    source venv/bin/activate
    # On Windows
    venv\Scripts\activate
    ```

3. Install the required dependencies:

    ```
    bash
    pip install -r requirements.txt
    ```

## Usage
To run the application, execute the following command:

```
bash
python app.py
```
Make sure to update the app.py file with the correct directory paths for your input videos and model file.

## Demo
To see a demonstration of the emotion recognition system, launch the Jupyter notebook provided:
```
jupyter notebook EmotionRecognition.ipynb
```
This will open the notebook in your web browser where you can run each cell to see the results.

## Results
The model's performance, as detailed in the Jupyter notebook, reflects an accuracy of over 60% on the validation set, showcasing the potential for this technology in real-world applications.



## Contributing
If you wish to contribute to this project, please fork the repository and propose your changes via a pull request.


## Acknowledgments
- Credit to the researchers and developers of the MobileNet architecture.
- Appreciation for the maintainers of the FER-2013 dataset.

