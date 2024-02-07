Instance Segmentation with Detectron2

This repository contains code for performing instance segmentation using Detectron2, a powerful library for object detection and instance segmentation tasks.

Requirements

Python 3.x
PyTorch
Detectron2
Other dependencies (listed in requirements.txt)
Installation

Clone the repository:
bash
Copy code
git clone <repository_url>
cd <repository_name>
Install dependencies:
Copy code
pip install -r requirements.txt
Usage

Training: To train the instance segmentation model, run the main() function in the train.py script.
Copy code
python train.py
Inference: To perform inference on an image using the trained model, run the on_image() function in the inference.py script.
php
Copy code
python inference.py <image_path>
Plot Samples: To visualize samples from the training dataset, use the plot_samples() function in the utils.py script.
Copy code
python utils.py
Configuration

config_file_path: Path to the configuration file for the model.
checkpoint_url: URL or path to the pre-trained model checkpoint.
output_dir: Directory to save the trained model and logs.
num_classes: Number of classes for instance segmentation.
device: Device to use for training (e.g., "cuda" or "cpu").
train_dataset_name: Name of the training dataset.
train_images_path: Path to the directory containing training images.
train_json_annot_path: Path to the JSON annotation file for training.
test_dataset_name: Name of the testing dataset.
test_images_path: Path to the directory containing testing images.
test_json_annot_path: Path to the JSON annotation file for testing.
cfg_save_path: Path to save the configuration object.
License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

This project is based on Detectron2, developed by Facebook AI Research.