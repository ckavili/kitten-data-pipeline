# Cat Image Transformer 🐱✨

Welcome to the **Cat Image Transformer** repository! This project is designed to help you practice basic image processing techniques in the context of machine learning. The goal is to convert raw cat images into a format suitable for machine learning models.

## 📦 Repository Structure

- **`images/`**: This folder contains the raw cat images you’ll be processing.
- **`processed_images/`**: Here, the transformed images will be saved after processing.
- **`dataset.csv`**: This file will store metadata for the processed images, including the filename and their corresponding labels.
- **`transform_images.py`**: A Python script that transforms the images (resize, grayscale) and updates the metadata in `dataset.csv`.

## 📝 Task Overview

1. **Fork and Clone**  
   Fork this repository and clone it to your local environment.

2. **Download Cat Images**  
   Download a few cat images from an open-source image repository (like [Unsplash](https://unsplash.com/s/photos/cat) or [Pixabay](https://pixabay.com/images/search/cat/)) and place them into the `images/` folder.

3. **Run the Transformation Script**  
   Run the `transform_images.ipynb` Notebook to:
   - Resize the images to 128x128 pixels.
   - Convert them to grayscale (because cats look great in grayscale).
   - Save the transformed images to the `processed_images/` folder.
   - Update `dataset.csv` with metadata about the transformed images.

4. **Commit and Push**  
   After running the script, **commit and push** the following changes:
   - The transformed images in `processed_images/`.
   - The updated `dataset.csv` file.

5. **Stop and Restart Your Workbench**  
   - Don’t forget to stop and restart your workbench to ensure everything is saved!
