# Intelligent-Kitchen-Aid-for-the-Visually-Impaired

## Project Description
This project leverages machine learning and computer vision to assist visually impaired individuals in the kitchen. It identifies common kitchen items and suggests possible actions to the user through audio feedback. The goal is to provide an inclusive technology that enhances daily living for those with visual impairments.

## Dataset
The dataset used in this project can be found at [GMU Kitchens Dataset](https://cs.gmu.edu/~robot/gmu-kitchens.html).

## Installation
To install the required dependencies, run the following commands:
```bash
!pip install ultralytics --upgrade
!pip install pyttsx3
!sudo apt-get install espeak
!pip install gtts
```

## Usage
The project consists of several scripts to convert datasets, replace class names, and train a YOLO model for object detection. The main components are:

1.convert_voc_to_yolo: Converts annotations from VOC format to YOLO format.
2.replace_class_names: Replaces class names in annotations with numerical labels.
3.train_yolo_model: Trains the YOLO model with the given dataset.

## Multiview RGB-D Dataset : 
<img width="611" alt="Screenshot 2023-11-29 at 7 53 39 PM" src="https://github.com/sneha1012/Intelligent-Kitchen-Aid-for-the-Visually-Impaired/assets/79008130/892cddc9-4dde-43e4-b125-70a753a47467">


## Object Detection Looks Like: 
![Unknown](https://github.com/sneha1012/Intelligent-Kitchen-Aid-for-the-Visually-Impaired/assets/79008130/7bc8c953-ed7f-4938-a458-6ee7da8514f0)


## License: MIT

## Team Members
1.Sneha Maurya
2.Prayuj Sachdev
3.Lokavya Gabrani


