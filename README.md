# AMLS_21-22-_SN21213556

This repository was created to implement two algorithms: a binary classifier and a multi-class classifier for MRI brain tumour images. Four files compose the project:

* **Script.ipynb**: Contains all the algorithms implemented to solve both classification tasks.
* **.gitignore**: A file required to omit files from the GitHub source control project.
* **dataset**: A folder which contains all the neccesary data for this project. The "dataset" folder contains:
  * **label.csv**: A CSV file containing a first column with image filenames and a second column with labels for each image.
  * **label_data.csv**: A CSV file inherited from "label.csv" which contains also further colums with features extracted from each image as well as a column with binary labels for Task A (see report for full description).
  * **image**: A folder containing all 3000 images from the brain MRI tumour dataset available at "Sartaj Bhuvaji, Ankita Kadam, Prajakta Bhumkar, Sameer Dedge, and Swati Kanchan, “Brain Tumor
Classification (MRI).” Kaggle, 2020, doi: 10.34740/KAGGLE/DSV/1183165"

To run the algorithms developed for this project simply follow the instructions given on the "Script.ipynb" file.

A list of all required packages and libraries is presented below:

Pillow

pandas

matplotlib

numpy

scipy

pywt

skimage 

sklearn

imblearn

seaborn

mlxtend

torch

torchvision

skorch
