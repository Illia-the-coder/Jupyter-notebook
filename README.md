# Jupyter-notebook

# Emotion Recognition on Video Thumbnails

This code performs emotion recognition on a set of video thumbnail images using a pre-trained VGG-16 convolutional neural network. It then creates several visualizations of the results. This type of analysis could be useful for understanding how emotions are portrayed in video content.

## Usage

To use this code, you will need to have the necessary data files and dependencies installed. The full code and documentation can be found in the Jupyter notebook file.

## Code Documentation

The following code performs emotion recognition on thumbnails using a VGG-16 convolutional neural network. It then creates several visualizations of the results.

### Importing Libraries

This code imports the necessary libraries for the analysis.

### Loading the Data

This code loads the dataset of video data that contains columns for the video's title, description, thumbnails, publication date, and other information.

### Filtering the Data

This code filters the dataset to only include videos with titles containing the string 'день війни', which means 'day of war' in Ukrainian.

### Extracting the Day from the Title

This code extracts the day of the video from the title and creates a new column with the day as an integer value.

### Extracting the Thumbnail URL

This code extracts the URL for the thumbnail image of each video and stores it in a new column.

### Downloading the Thumbnails

This code downloads the thumbnail images for each video and saves them in a local directory.

### Loading the Pre-trained VGG-16 Model

This code loads the VGG-16 convolutional neural network and adds several custom layers for emotion recognition. The resulting model is saved as an h5 file.

### Preprocessing the Images

This code defines a function for preprocessing images. The function resizes the image to the specified target size, converts grayscale images to RGB, applies VGG-16 preprocessing, and expands the dimensions of the image array to fit the model's input shape.

### Prediction Function

This code defines a function for predicting the emotions in an image using the pre-trained VGG-16 model. The function preprocesses the image, passes it through the model, and returns a dictionary of the top 5 predicted emotions and their corresponding scores.

### Emotion Prediction

This code applies the `em()` function to each thumbnail image and saves the resulting emotion predictions in a new column of the `img` dataframe.

### Creating Emotion Visualizations

This code creates several visualizations of the emotion predictions, including bar charts and a table of mean values.

## Future Work

This analysis could be expanded to include additional video datasets and different types of emotion recognition models for comparison.
