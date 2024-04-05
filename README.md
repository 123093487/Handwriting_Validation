# Handwriting_Validation
Deep Learning model built to validate between valid invalid and zoomed images
Model Link: https://drive.google.com/file/d/1RVhUdyHdqnBPfJCCTy0Kfi9U0mvBtUil/view?usp=drive_link

1.Handwritten Image Analysis (Main Function)
This block cleans up a data folder containing image files by removing any files that aren't recognizable image formats (e.g., jpeg, png).

2.Pdf Extraction (Main Function)
This block extracts images from a PDF file and saves them in a specified folder.

3.Number Marking (Main Function)
This block renames image filenames in a folder with sequential numbers starting from 1.

4.Name Resetting (Main Function)
This block renames image filenames in a folder with random strings.

5.Zoom Creation (Main Function):
This block crops a specific region of interest from each image in a folder and saves the cropped images in another folder.

6.IAM Dataset Cropping (Main Function):
This block crops a specific region of interest from each image in a folder and saves the cropped images in another folder.

7.Augmentation (Main Function):
This block applies random transformations (like shift, scale, rotation, brightness/contrast changes, and horizontal flip) to existing images and saves the augmented versions with specific naming conventions.

8.Data Loading (Main Function):
This block loads image data from a folder along with their class labels into a format suitable for training a machine learning model.

9.Visualization (Main Function):
This block displays a sample batch of images with their corresponding class labels in a grid format.

10.Preprocessing (Main Function):
This block prepares the loaded image data for training a machine learning model by converting them to a specific numerical format and applying one-hot encoding to class labels.

11.Train Test Validation Split (Main Function):
This block splits the preprocessed data into three sets: training set (used to train the model), validation set (used to monitor the model's performance during training), and test set (used to evaluate the final model performance).

12.Model Architecture (Main Function):
This block defines the architecture of a convolutional neural network (CNN) model for image classification. It uses a pre-trained model (DenseNet169) as a feature extractor and adds additional layers on top for classification.

13.Val Model Performance (Main Function):
This block trains the CNN model on the training data and evaluates its performance on the validation data.

14.Testing (Main Function):
This block loads an image, predicts its class label using the trained model, and displays the prediction result.

15.LIME Explainability (Main Function):
This block uses LIME (Local Interpretable Model-agnostic Explanations) to explain the predictions made by the model for a specific image. It highlights the regions of the image that contribute most to the prediction.
