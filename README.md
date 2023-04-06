# 📷 Emotion Recognition on Video Thumbnails

This code performs emotion recognition on a set of video thumbnail images from the official YouTube channel of [Zelenskyi](https://www.youtube.com/@Zelenskyy_President) using a pre-trained VGG-16 convolutional neural network. It then creates several visualizations of the results.

## 🎓Usage

To use this code, you need to have the necessary data files and dependencies installed. The full code and documentation can be found in the **Jupyter Notebook file**.

## Used Libraries

| Library | Description | Documentation |
| --- | --- | --- |
| numpy | Numerical computing library | https://numpy.org/doc/stable/ |
| pandas | Data manipulation library | https://pandas.pydata.org/docs/ |
| os | Operating system interface | https://docs.python.org/3/library/os.html |
| IPython | Interactive computing in Python | https://ipython.readthedocs.io/en/stable/ |
| cv2 | Computer vision library | https://docs.opencv.org/4.5.4/ |
| matplotlib | Data visualization library | https://matplotlib.org/stable/contents.html |
| tensorflow | Machine learning library | https://www.tensorflow.org/api_docs |
| seaborn | Data visualization library | https://seaborn.pydata.org/ |
| ast | Abstract syntax tree library | https://docs.python.org/3/library/ast.html |
## Plan of Code:

- Importing Libraries 📚
- Loading the Data 📂
- Filtering the Data 🔍
- Extracting the Day from the Title 📅
- Extracting the Thumbnail URL 🖼️
- Downloading the Thumbnails ⬇️
- Loading the Pre-trained VGG-16 Model 🧠
- Preprocessing the Images ⚙️
- Prediction Function 🔮
- Emotion Prediction ✨
- Creating Emotion Visualizations 📈

## 🚀 Future Work

This analysis could include additional video datasets and different emotion recognition models for comparison.
