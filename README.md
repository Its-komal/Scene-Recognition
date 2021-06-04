# Scene-recognition
Scene recognition is still a rising area that did not attain much success as compared to image recognition due to the vast variability of features in the scenic environment. Because of this reason, there is not a lot of work being completed these days in this area.
This project focuses on the evaluation of problem statements using all the literature surveys completed lately and offering solutions for that problem statement.

For resolving the proposed problem declaration ResNet and VGG variants are used ResNet18, 50 and 152 & VGG16, 19, and VGG19 with batch normalization are implemented. The entire scene recognition procedure is discussed in this report and the main motive is to form a foundation that can be further continued in proposing a new algorithm. Before deep learning the design and implementation of the scene recognition model depended on the low dimensional portrayal of the scene. The utilization of deep learning especially CNN for scene recognition has gotten extraordinary attention from the computer vision community.


# Dataset
To download intel-image-classification kaggle dataset 
1. we need to create an API key in Kaggle for that go to kaggle.com/ and open your user settings page.
2. Then scroll down to the API access section and click generate to download an API key. This will download a file called kaggle.json to your computer. You'll use this file in Colab to access Kaggle datasets and competitions.
3. Navigate to https://colab.research.google.com/. Upload your kaggle.json file using the following snippet in a code cell:
![image](https://user-images.githubusercontent.com/74605463/120839486-9f125380-c586-11eb-82e5-617edbdeae7e.png)
4. Install the kaggle API using *!pip install -q kaggle
5. Move the kaggle.json file into ~/.kaggle, which is where the API client expects your token to be located:
  ![image](https://user-images.githubusercontent.com/74605463/120839616-c8cb7a80-c586-11eb-8f16-ccfe0b84286a.png)


MIT indoor scene dataset:"http://groups.csail.mit.edu/vision/LabelMe/NewImages/indoorCVPR_09.tar"

Used the training image dataset which contains around 14k images across 6 classes and combines them with the MIT indoor scene dataset which makes a total of 29654 under 73 classes. The dataset is split using random split into train, test, and validation data with the training dataset having 23723 images, 2965 images invalidation dataset, and 2966 images in the test dataset.
