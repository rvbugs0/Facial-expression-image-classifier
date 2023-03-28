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

