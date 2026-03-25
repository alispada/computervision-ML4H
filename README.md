# computervision-ML4H
<h1>Art Technique Classifier - An AI model trained for technique classification in the art field</h1>
<h2>Contents</h2>

**Notebook**: [technique_recognition.ipynb](technique_recognition.ipynb), with the dataprocessing and the training of the EfficientNet-B0 model for art techniques recognition. 

**Dataset folder**: this folder contains the [toy_dataset_label.csv](toy_dataset_label.csv), used for the model training. For limited space reasons, the entire dataset with the images used was not uploaded in this repository. The zipped version can be dowloaded at the following link: (to be created) In order to reproduce the training it is required that, once downloaded and unzipped on your local computer, the folder is placed inside the dataset folder.  

**Model folder**: It contains the trained model which is a fine tuning of the EfficientNet-B0 architecture, pretrained on the  ImageNet database and subsequently adapted for the role of art technique recognition.

**The application**: ... spiega

**Templates folder** ... spiega

<h2>Installation</h2>

1. Download ....

2. Place it inside the **dataset** folder

3. Set up your environment
   ```bash
   python -m venv .venv
   
   # on Windows:
   .venv\Scripts\activate
   
   # on Mac/Linux:
   source .venv/bin/activate

5. Install dependencies:
   ```bash
   pip install -r requirements.txt

6. Launch the app:
   ```bash
   python app.py
