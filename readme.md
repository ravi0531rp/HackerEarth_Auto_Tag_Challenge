# Problem statement
Galas are the biggest parties of the year. Hosting firms of these events are well aware that everyone from around the world has their eyes on these nights. It can be for inspiration or for critique. It takes months of meticulous planning and delegation to host these events.

One such firm has decided to take a data-driven approach for planning their gala nights going forward. Aesthetics and entertainment are the most crucial segments of these events. So, this firm has hired you to help them aggregate and classify all images. These images are published by attendees and the paparazzi on various social media channels and other sources. You are required to build an image auto-tagging model to classify these images into separate categories.

# Data
This data set consists of the following two columns:

# Column Name	Description
	Image		Name of Image
	Class		Category of Image ['Food', 'Attire', 'Decorationandsignage', 'misc']
	Data 		description
The data folder consists of two folders and two CSV files.

# Folders

train: Contains 5983 images for 4 classes ['Food', 'misc', 'Attire', 'Decorationandsignage']
test: Contains 3219 images

# CSV files

train.csv: (5983 x 2)
test.csv: (3219x1)
sample_submission

Image,Class
image0001.jpg,Food
image0002.jpg,Attire
image0003.jpg,Food
image0004.jpg,misc
image0005.jpg,Attire
Evaluation metric

## Note: To avoid any discrepancies in the scoring, ensure all the index column ('Image_File') values in the submitted file match the values in the provided test.csv file.