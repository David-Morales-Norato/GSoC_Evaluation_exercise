# Evaluation exercise for Google Summer of Code - ATLAS autoencoders

This repository contains the notebook of my solution to the evaluation exercise for the GSoC to ATLAS autoencoders project.

In this repository, you can find the notebook with the code of the solution as `GSoC_Evaluation_exercise.ipynb`, the plots generated in the folder `plotOutput`, and the figures used in the presentation in `figures_presentation`

---------
## How to run

For your convenience, I set up two ways to run the notebook
### Run locally

To install de dependencies  you can create a conda environment from the `enviroment.yml` file

    conda env create -f enviroment.yml

Those are the requeriments to run the notebook locally.

### Run in Google Colab

If the hardware is a problem an easy solution is run the notebook with Google Colaboratory, just make sure to set up the path to the folder of the notebook and the data just like this
```Python
from google.colab import drive
import os
drive.mount('/content/gdrive')
os.chdir("/content/gdrive/MyDrive/path_to_folder")
```
## Aditional files

In the repository, the file `motivation.md` contains my motivation to apply to this project. Besides the slides are in the file `presentation.pdf`
