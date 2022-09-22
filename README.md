# Data analysis in Python

Tutorial of [EITN school 2022](https://eitnschool2022.sciencesconf.org/program).

Author: Bartosz Telenczuk, https://datascience.telenczuk.pl

## Installation

To view the notebooks you can open the file in your browser by clicking on the filename (with `.ipynb` extension) or by following the [Notebooks](#notebooks) section below links below.

To run this notebooks locally:

1) Download and unpack the zip file with the notebooks: https://github.com/btel/2022-09-21-eitn-school/archive/refs/heads/main.zip
2) download and install anacoda Python distribution from: https://www.anaconda.com/products/distribution.
3) Then open `JupyterLab` from the menu. The JupyterLab should open in your browser (running locally on you computer - in the URL bar you should see http://127.0.0.1:8000)
4) In the JupyterLab's file browser (left sidebar) navigate to the directory with notebooks.

## Data

Data source: "EEG data for Mental Attention State Detection" on [Kaggle](https://www.kaggle.com/datasets/inancigdem/eeg-data-for-mental-attention-state-detection).

C.I. Acı, M. Kaya, Y. Mishchenko, _"Distinguishing mental attention states of humans via an EEG-based passive BCI using Machine Learning Methods"_, Expert Systems with Applications, vol. 134, pp. 153-166, 2019. 
Data was [preprocesed](https://www.kaggle.com/code/btelenczuk/eeg-extract-features?scriptVersionId=106174038) and stored in CSV file [eeg_powers.csv](./eeg_powers.csv).

## Notebooks

Jupyter notebooks are files with Python code that have `.ipynb` extension:

- [starter_workbook_delivered.ipynb](starter_workbook_delivered.ipynb) - notebook that we created during the lecture,
- [lecture_notes.ipynb](lecture_notes.ipynb) - notebook with the lecture notes,
- "EEG extract features" ([on Kaggle](https://www.kaggle.com/code/btelenczuk/eeg-extract-features?scriptVersionId=106174038)) - notebook used to pre-process the data (not covered during the lecture)
- [eeg-extract-features.ipynb](eeg-extract-features.ipynb) - local copy of the notebook above (but without the data files)
- [starter_workbook.ipynb](starter_workbook.ipynb) -- clean notebook with lecture plan (no code) - can be used to give a tutorial from scratch (or to practice)

## Other useful links

- [Software Carpentry](https://swcarpentry.github.io/python-novice-inflammation/) - Python course for beginners
- [Adavanced Scientific Programming in Python](https://aspp.school/wiki/schedule) - advanced Python school (see schedule for next events)
