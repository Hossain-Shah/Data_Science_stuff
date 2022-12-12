# SELISE DS ASSESSMENT

## Installation

Run the following command to install the dependencies:

```bash
pip install -r requirements.txt
```

## Dependency

You must have the following files in your repository to operate locally:

classifier.h5 (Trained Deep learning Transfer learning based InceptionV3 model on basis of which input image will respond which class it belongs to)

classifier2.h5 (Trained Deep learning CNN model on basis of which input image will respond which class it belongs to)

classifier2.pkl (Label classifier denoting classes of given dataset accordingly regarding trained Deep learning CNN model)

ensembled_model.h5 (Ensembled model of classifier.h5(InceptionV3) and classifier2.h5(CNN) model)

Md_Shahnawaz_Hossain_CV_DS_Assessment.ipynb (Jupyter notebook regarding main answer script loaded with answers and source codes)

Added an unrelated image part in the existing dataset to distinguish it from the existing classes in the dataset. If the user selects a random photo of any object in the world which does not belong to these 4 classes in the dataset then it will classify it as unrelated_image. This part contains image data of random objects in the world except these 4 classes, but some similar images but not fully belong to these 4 classes. 



