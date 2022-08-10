# Cleansea CNN Model (Read below)

Our CNN model for the Cleansea Mobile App. It classifies four of the most common and critical types of trash, debris, etc. from the TACO Custom dataset, which we adapted from the original Taco dataset. This original Taco dataset was created for object detection, so we modified it to be used for classification. See original Taco dataset here: http://tacodataset.org/ <br>

*Model and adapted dataset were developed by Julia Huang from Team cloud9 - Deep Learning Track.

# What's In This Repository:
<li> Materials Used to Develop Dataset + Model </li>
<li> Our Dataset We Used (see below) </li>
<li> Model Architecture </li>
<li> Model Classification Results </li>
<li> Model Code (2 Google Colab Notebook versions in surreal_version folder) :)</li>
<li> Saved Model in .h5 format for easy mobile app deployment, such as using Flutter </li>
<li> Cleansea App User Journey Diagram  </li>
<li> Machine Learning Process Flow Diagram  </li>

# Our Google Colab Notebook
includes process from dataset loading, processing, to model training (also linked in this github repo)
https://colab.research.google.com/drive/14dzlJOXXuSqTsd5M4WJco5ubBpb7OxO_?usp=sharing

# About Our Taco Custom Dataset
TACO Custom dataset in Google Drive: https://drive.google.com/drive/folders/1MMX_i6e6GTondUnDtLiPjdbqegihMAVU?usp=sharing <br>
TACO Custom dataset published on Kaggle: https://www.kaggle.com/datasets/julesh7/taco-dataset-revised-230-imgs <br>
To create this dataset, I labeled images of 4 important debris types and placed them in four folders - cans, bottles, plastics, containers. Images were resized and rescaled to match our tasks.

# Canva Slides Presentation for Cleansea ML Mobile App
https://www.canva.com/design/DAFIGOsvodM/QWxmbrADZLBg_JPwwZjQmg/view?utm_content=DAFIGOsvodM&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink
