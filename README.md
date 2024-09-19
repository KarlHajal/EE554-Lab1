#EE554 - Lab1 : Speech Signal Processing

This repo contains the code for the course's Speech Signal Processing Lab.
Answers to the exercises in the notebook are provided in the PDF.

## Running the Notebook on Noto

### Cloning the repo
1. Go to Git > Clone a Repository
2. Enter the URL for the Repo: https://github.com/KarlHajal/EE554-Lab1
   
### Creating the kernel
1. Open a terminal: File > New > Terminal
2. Go the project's directory: ```cd EE554-Lab1/```
3. Run the following command to create the kernel: ```kbuilder_create EE554_Lab1 requirements.txt```

### Activating the kernel
1. Refresh your browser
2. Open the notebok (speech_analysis.ipynb)
3. Go to Kernel > Change Kernel
4. Choose EE554_Lab1

The notebook is now ready to run!

## Running the Notebook Locally
### Create conda environment

```bash
conda env create -f environment.yml
conda activate speech_analysis
```

### Launch the notebook

```bash
jupyter notebook speech_analysis.ipynb
```

## Acknowledgements

This lab was originally developed in Matlab for the *Speech Processing and
Speech Recognition* course at École polytechnique fédérale de Lausanne (EPFL).
