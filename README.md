# Dog Breed Identification using Image Classifier

## Project Goal
The main objective of this project is to enhance programming skills using Python by building an image classifier to identify dog breeds. The focus of this project is on Python programming, and I will be utilizing an already developed image classifier for this purpose.

## Description
The city is organizing a citywide dog show, and my role is to assist the organizing committee with contestant registration. Participants registering for the dog show must submit an image of their dog along with biographical information about their pet. The registration system tags the images based on the provided information.

However, some participants may try to register pets that are not actual dogs. To ensure the accuracy of the registration process, I will use a pre-trained Python image classifier to determine whether the submitted images are of dogs or not.

## Tasks
In this project, I need to accomplish the following tasks:

1. Determine the best image classification algorithm that works most accurately for classifying images as "dogs" or "not dogs."
2. Evaluate the performance of the "best" classification algorithm in correctly identifying a dog's breed.
3. Time the execution of each algorithm to understand the trade-off between accuracy and runtime. More accurate algorithms might require more computational resources and time to execute.

## Image Classifier
An image classifier is a tool that takes an image as input and produces an output, determining what the image depicts (e.g., a dog or not a dog. I will leverage a pre-trained image classifier for this project to streamline the focus on Python programming and not on building the classifier from scratch.

## How to Use
To run this project, follow these steps:

1. Ensure you have Python installed on your system.
2. Clone this repository to your local machine.
3. Install the required Python libraries and dependencies as specified in the `requirements.txt` file.
4. Run the Python script to perform the dog breed identification using the image classifier.

## Project Structure
The project structure is organized as follows:
- project/
  |-- README.md
  |-- adjust_results4_isadog.py
  |-- calculates_results_stats.py
  |-- check_images.py
  |-- classifier.py
  |-- classify_images.py
  |-- get_input_args.py
  |-- get_pet_labels.py
  |-- imagenet1000_clsid_to_human.txt
  |-- print_functions_for_lab_checks.py
  |-- print_results.py
  |-- requirements.txt
  |-- run_models_batch_uploaded.sh
  |-- run_models_batch.sh
  |-- test_classifier.py
  |-- dognames.txt
  |-- pet_images/
  |   |-- Basenji_00963.jpg
  |   |-- Basenji_00974.jpg
  |   |-- ...
  |-- uploaded_images/
  |   |-- Dog_01.jpg
  |   |-- Dog_02.jpg
  |   |-- ...


- `README.md`: This file provides an overview of the project, its purpose, and instructions on how to run the code.
- `requirements.txt`: Contains a list of Python libraries and dependencies required to run the project.
- `adjust_results4_isadog.py`: Creates a function that adjusts the results dictionary to determine whether or not the pet image label is of-a-dog and to indicate whether or not the classifier image kabel iis of-a-dog.
- `calculates_results_stats.py`: Creates a function that calculates the results of the run and puts the results statistics in a dictionary (results_stats_dic).
- `check_images.py`: Classifies pet images using a pretrained CNN model, compares these classifications to the true identity of the pets in the images, and summarizes how well the CNN performed on the image classification task.
- `classifier.py`: Function taht allows you to use three CNN architectures (AlexNet, VGG, and ResNet) to classify images.
- `classify_images.py`: Creates a function that uses the classifier function to create the classifier labels and then compares the classifier labels to the pet image labels.
- `dognmes.txt`: Contains a list of valid dog names.
- `get_input_args.py`: Creates a function that retrieves the following 3 command line inputs from the user using the Argparse Python module. If the user fails to provide some or all of the 3 inputs, then the default values are used for the missing inputs.
- `get_pet_labels.py`: Creates the function that creates a dictionary of pet labels (results_dic) based upon the filenames of the image files. These pet image labels are used to check the accuracy of the labels that are returned by the classifier function.
- `imagenet1000_clsid_to_human.txt`: Contains the labels the classifier function returns.
- `print_functions_for_lab_checks.py`: Creates a set of functions that can be used to check your code after programming each function.
- `print_results.py`: Creates a function that prints the results statistics (percent correctly classified, percent not dogs correctly classified, percent dogs correctly classified, and percent of breeds of dogs correctly classified) calculated by the calculates_results_stats() function.
- `run_models_batch_uploaded.sh`:  Runs all three models to test which provides the 'best' solution on the Uploaded Images. Please note, output from each run will be piped into a text file.
- `run_models_batch.sh`:  Runs all three models to test which provides the 'best' solution on the Pet Images. Please note, output from each run will be piped into a text file.
- `test_classifier.py`: To demonstrate the proper usage of the classifier() function that is defined in classifier.
- `pet_images/`: Folder containing sample dog images for testing the classifier.
- `uploaded_images/`: Folder containing your own images for testing the classifier.

## Contribution
I welcome contributions to this project. If you find any bugs or want to improve the image classifier's performance, please feel free to create pull requests or raise issues.

Let's work together to make this project better and more accurate in identifying dog breeds! Happy coding! 🐶🐾


