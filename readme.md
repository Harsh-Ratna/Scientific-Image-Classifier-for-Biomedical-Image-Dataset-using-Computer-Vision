Team Dataverse- Scientific Image Classifier 
--------------------------------------------
please open team dataverse final ppt to get an idea of our approach.

The zip file contains 4 notebooks, in order of,
1) Data Preparation, Processing and Visualization.ipynb

2) Image Enhancement (Optional).ipynb 
 in this notebook we explored different ways of refining the quality of our images.
 but on training the vgg16 model by transfer learning, not much difference was observed.

3) training cnn model from scratch.ipynb
 in this notebook we implemented the cnn model from scratch and achieved a validation accuracy of 86%. 

4) VGG16 Transfer learning.ipynb
 this model achieves the best validation accuracy of 96%.

**Dataset Information -**
* We obtained the base dataset from this repo https://github.com/vimal-isi-edu/BioFors containing 4 classes namely 'Microscopy', 'Macroscopy', 'Blob/Gel', and 'FACS'.
* we added images of X-Ray scans, https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database
* CT Scan images https://www.kaggle.com/datasets/plameneduardo/sarscov2-ctscan-dataset?select=COVID
* A negative class containing graphs, charts, tables etc. https://www.kaggle.com/datasets/sunedition/graphs-dataset/data

