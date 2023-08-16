# Bachelor Mask R-CNN 3D Object Detection

This repository contains code and instructions for using Mask R-CNN to perform 3D object detection and instance segmentation on images. The model is based on Feature Pyramid Network (FPN) and a ResNet101 backbone.

## Introduction

Bachelor Mask R-CNN 3D Object Detection is a deep learning model for 3D object detection and segmentation tasks. It can generate bounding boxes and segmentation masks for each instance of an object in a 3D image stack.

## Installation

1. Clone this repository:
git clone https://github.com/Becker99/Bachelor-Mask-R-CNN-3D-Object-Detection.git

2. Navigate to the project directory:
cd Bachelor-Mask-R-CNN-3D-Object-Detection

3. Install the required packages:
pip install -r requirements.txt

## Usage

1. Prepare your dataset as described in the `dataset` section.

2. Train the model using the provided Jupyter notebook `main_jupyter_training.ipynb`.

3. After training, use the notebook `predict_organoid.ipynb` to perform inference on new 3D image stacks.

4. Post-process the predicted results using the notebook `postProcess.ipynb`.

5. Convert processed images to stacks using `preProcess.ipynb`.

## Dataset

The dataset used in this project consists of 3D image stacks containing organoids. The images are annotated with nucleus regions for training.

## Training

1. Run the `main_jupyter_training.ipynb` notebook to train the Mask R-CNN model on your dataset.

2. Specify the dataset directory, image annotations, and other configurations in the notebook.

## Inference

1. Use the `predict_organoid.ipynb` notebook to perform inference on new 3D image stacks.

2. Specify the path to the trained model weights and the directory containing the 3D image stacks to predict.

## Results

The trained model can predict nucleus regions in new 3D image stacks. The results can be post-processed and visualized using the provided notebooks.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
