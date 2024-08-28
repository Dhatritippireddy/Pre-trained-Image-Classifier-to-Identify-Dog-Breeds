# Pre-trained-Image-Classifier-to-Identify-Dog-Breeds
# Overview
This project is part of the Nanodegree in AI Programming with Python offered by the AWS AI/ML Scholarship Program. The goal is to classify dog breeds based on photos using pre-trained convolutional neural network (CNN) models, such as ResNet, AlexNet, and VGG. In this research, labels for pet photos are extracted from their filenames, the images are classified using CNN models, and the results are analyzed to determine how accurate each model is at identifying dog breeds.
# Project Structure
The project is organized into the following main components:

1.check_images.py: Python script for classifying pet images using pre-trained CNN models.

2.get_input_args.py: Python script for handling command line arguments.

3.get_pet_labels.py: Python script for extracting pet image labels from filenames.

4.classify_images.py: Python script for classifying pet images using the specified CNN model.

5.adjust_results4_isadog.py: Python script for adjusting the results dictionary to indicate whether the pet image label and classifier label are of a dog.

6.calculates_results_stats.py: Python script for calculating results statistics.

7.print_results.py: Python script for printing a summary of the results, including incorrectly classified dogs and breeds.

8.print_functions_for_lab_checks.py: Python script containing print functions for checking the lab.

9.dognames.txt: Text file containing names of all dogs from the classifier function and pet image files.
# How to Run
To run the project, follow these steps:

Open a terminal window.

Navigate to the project directory.

Run the command:

python check_images.py --dir <directory_with_images> --arch <model> --dogfile dognames.txt

Example:

python check_images.py --dir pet_images/ --arch vgg --dogfile dognames.txt
# Results
The project generates a summary table with key statistics, including:

Number of Images

Number of Dog Images

Number of Not-a-Dog Images

% Correct Dogs

% Correct Breed

% Correct Not-a-Dog

% Match

The table also shows counts for different metrics, including the number of photos, the number of dogs that were successfully identified, and the number of breeds that were correctly identified, for each model (ResNet, AlexNet, and VGG). If needed, it also prints out the incorrectly classified pets and breeds.
# Acknowledgments
This project was completed as part of the AWS AI/ML Scholarship Program Nanodegree - AI Programming with Python.

Special thanks to the mentors and contributors in the program.
