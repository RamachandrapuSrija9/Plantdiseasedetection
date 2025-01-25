# Plantdiseasedetection
# Plant Disease Classification Dataset Visualization

This repository contains a Python script for visualizing and exploring a plant disease classification dataset. The dataset is organized into disease classes (folders), each containing images of plants affected by different diseases. This script provides insights into the dataset, including the number of images in each class and a preview of the first image from each class.

## Requirements

Before running the script, ensure you have the following libraries installed:

- `matplotlib` for plotting images.
- `colorama` for colored text output.
- Python 3.x

You can install the required libraries using `pip`:

```bash
pip install matplotlib colorama
/train_dir
    ├── disease_class_1
    │   ├── img1.jpg
    │   ├── img2.jpg
    │   └── ...
    ├── disease_class_2
    │   ├── img1.jpg
    │   ├── img2.jpg
    │   └── ...
    └── ...
git clone https://github.com/your-username/plant-disease-visualization.git
cd plant-disease-visualization
Place your dataset inside the train_dir folder.

Run the Python script:python visualize_diseases.py
The script will display a grid of images with disease class labels and print out the total number of images in the dataset.

How it Works
The script does the following:

It loops through each disease class (subdirectory) in the train_dir.
For each class, it counts the number of images and displays the first image in a subplot.
The script also calculates the total number of images across all classes and prints it.
Output
The output will display:

A grid of images, with the first image from each disease class.
The name of each disease class will be shown under the corresponding image.
The total number of images in the dataset will be printed in the console.
Example Output:
The Number of Images in disease_class_1: 120
The Number of Images in disease_class_2: 150
...
Total Number of Images in Directory: 350
Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. All contributions are welcome!

License
This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to customize it further depending on your needs or repository details!
