# Pre-trained-Image-Classifier-to-Identify-Dog-Breeds

## Overview
This project, part of the AWS AI/ML Scholarship Program Nanodegree - AI Programming with Python, uses advanced neural network models (ResNet, AlexNet, VGG) to identify dog breeds from images. The goal is to accurately label pet images, compare them against known dog breeds, and analyze how well each model performs.

## Project Components
1. check_images.py: Classifies pet images using AI models.
2. get_input_args.py: Manages command line instructions.
3. get_pet_labels.py: Extracts pet labels from image filenames.
4. classify_images.py: Uses AI models to classify pet images.
5. adjust_results4_isadog.py: Adjusts results to identify if images are dogs.
6. calculates_results_stats.py: Computes performance statistics.
7. print_results.py: Prints a summary including misclassified dogs.
8. print_functions_for_lab_checks.py: Contains functions to verify project accuracy.
9. dognames.txt: Lists all known dog names for comparison.

## How to Run
1. Open a terminal.
2. Navigate to the project folder.
3. Use this command:
```bash
python check_images.py --dir <directory_with_images> --arch <model> --dogfile dognames.txt```bash
Example:
```bash
python check_images.py --dir pet_images/ --arch vgg --dogfile dognames.txt```bash

## Results
The project generates a detailed table showing:
Total images processed.
Number of images correctly identified as dogs.
Accuracy in identifying specific dog breeds.
Misclassifications and their details if applicable.

## Acknowledgments
* This project was completed with support from the AWS AI/ML Scholarship Program Nanodegree.
* Special thanks to program mentors and contributors for their assistance.
