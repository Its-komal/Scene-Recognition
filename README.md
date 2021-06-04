# Scene-recognition
To download intel-image-classification kaggle dataset 
1. we need to create an API key in Kaggle for that go to kaggle.com/ and open your user settings page.
2. Then scroll down to the API access section and click generate to download an API key. This will download a file called kaggle.json to your computer. You'll use this file in Colab to access Kaggle datasets and competitions.
3. Navigate to https://colab.research.google.com/. Upload your kaggle.json file using the following snippet in a code cell:
![image](https://user-images.githubusercontent.com/74605463/120839486-9f125380-c586-11eb-82e5-617edbdeae7e.png)
4. Install the kaggle API using *!pip install -q kaggle
5. Move the kaggle.json file into ~/.kaggle, which is where the API client expects your token to be located:
  ![image](https://user-images.githubusercontent.com/74605463/120839616-c8cb7a80-c586-11eb-8f16-ccfe0b84286a.png)
