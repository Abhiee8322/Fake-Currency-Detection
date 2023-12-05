# Fake-Currency-Detection-System

Detects Counterfeit Indian Currency using Image Processing Techniques

## Project	Overview
The aim of this project is to test the authenticity of Indian currency notes by preparing a system which takes the image of currency bill as input and gives the ﬁnal result by applying various image processing and computer vision techniques and algorithms. 
This currency authentication system has been designed completely using Python language in Jupyter Notebooks. **OpenCV** library has been used for image processing and **Tkinter** library has been used for building the GUI. 

## Libraries and Tools
1. OpenCV
2. Tkinter
3. Numpy
4. Matplotlib
5. Jupyter Notebook

## Dataset
This currency detection currently works only for Indian Currency notes of denomination of only 500. The dataset used for this purpose is included in this repository and has been custom-built by collecting necessary images from various sources.

## Structure
1. **Dataset:** Contains all necessary images. This directory also contains images of real 500 rupee notes which you can use to test the system.
2. **Fake Notes:** Contains images of fake 500 rupee notes. You can use these images to test the system if you want.
3. **500_testing.ipynb:** This notebook processes input image of 500 denomination currency bills.
4. **controller.ipynb:** This notebook is the main notebook which takes the input, runs all necessary notebooks and displays the output.
6. **gui_1.ipynb:** This notebook produces a GUI to take the input data from the user.
7. **gui_2.ipynb:** This notebook produces a GUI to display the result.
8. **CV video submission:** Video containing the report and code explaantion with live testing of 2 500 fake denominations.

## Working

1. Clone the repository to your local machine.
2. Open the notebook controller.ipynb as a Jupyter Notebook
3. Run the entire notebook:
> Cell > Run All
4. This will open a GUI window:
	- Click 'Select An Image'. 
	- Browse the input image of the currency note that you want to authenticate. Sample images of currency notes (both real and fake) are already present in the dataset. You can select an image from there too. 
	- Choose the denomination of the currency note.
	- Click 'Submit' button
5. This will lead to another GUI window. Select 'Click To Continue' and wait for the processing to end. The progress can be seen in the progress bar.
6. Finally, the results will be displayed in another GUI window. The following details will be displayed.
	- Input image
	- Result statement (Number of features that are authentic)
	- Image of each feature of input currency note
	- Average and Maximum Similarity score (SSIM score) of each feature
	- Status of each feature (Pass/ Fail)


