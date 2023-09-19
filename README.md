## Facial expression image classifier

Classifying an image into a particular class or category based on its content is known as image classification. In order to accomplish this, a machine learning model must be trained to recognize specific patterns or characteristics in an image related to a particular class or category.

We would want a dataset of labeled images representing each emotion to train an image classifier that can identify several emotions, including happy, angry, sad, fear, disgust, neutral, and surprise.

The Facial Emotion Expressions dataset available at Kaggle, which consists of 48 x 48-pixel grayscale tagged images of human faces exhibiting various emotions, is one such dataset. My objective is to develop a neural network by utilizing this dataset and subsequently train it to determine an image’s emotional category.

##### Feel free to use this code for reference to learn from my work. Please maintain academic Integrity.
<hr>


<h3>Packages Required (Essential)</h3>
Python = 3.10.9
Tensorflow = 2.9.1
<br/>

<h4>Step-1: upload images.zip in google drive root</h4>
<h4>Step-2: Upload the notebook and add a code block at the top with the following code</h4>

```python
from google.colab import drive
drive.mount('/content/drive')
import zipfile
zip_ref = zipfile.ZipFile("/content/drive/MyDrive/images.zip", 'r')
zip_ref.extractall("/content/images")
zip_ref.close()
!pip install livelossplot
```

<h4>Step-3: On google colab click on menu->Runtime-> Run All </h4>

