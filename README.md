# Image Dataset Augmentation Script for Maize Disease Dataset

This script is designed to augment an existing dataset of images of maize plants with symptoms of various diseases. The augmentation is performed using the [imgaug](https://imgaug.readthedocs.io/en/latest/) library in Python.

## Requirements
- Python 3.x
- imgaug library
- Numpy
- OpenCV

## Usage
1. Clone or download the repository
2. Place the original dataset in the `data` folder.
3. Run the script using command : python augment_images.py
4. The augmented images will be saved in the `augmented_data` folder.

## Augmentations performed
- Flipping (horizontal and vertical)
- Rotation 
- Scaling
- Shearing
- Changing Brightness and Contrast

## Note
- Make sure to modify the path to the dataset in the script according to the location on your local machine.
- The script can be easily modified to perform different types of augmentations or to change the augmentation parameters as per requirements.

## References
- [imgaug library documentation](https://imgaug.readthedocs.io/en/latest/)
- [Data augmentation with imgaug library](https://www.pyimagesearch.com/2019/07/08/keras-imagedatagenerator-and-data-augmentation/)
