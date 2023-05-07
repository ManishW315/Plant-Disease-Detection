# Plant-Disease-Detection-App

Detecting diseases in plants from leaf images.
The dataset used for training the model is taken from [Kaggle](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset).
The original dataset can be found on [this](https://github.com/spMohanty/PlantVillage-Dataset) github repo. 

This dataset consists of about 87K rgb images of healthy and diseased crop leaves which is categorized into 38 different classes. The total dataset is divided into 80/20 ratio of training and validation set preserving the directory structure. A new directory containing 33 test images is created later for prediction purpose.

### Steps to use the App
- The app is build using Gradio. To install gradio type in command prompt:

  `pip install gradio`

- Run the **Plant Disease Classification App**

- The demo app appear automatically within the Jupyter Notebook, or pop in a browser on http://localhost:7860


![demo_app](https://user-images.githubusercontent.com/99869931/236658620-4f9fd13b-a5a6-4927-99de-f31f7bdfbf8d.png)
