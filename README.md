# Deep Learning and Advanced AI Course Work

## Medical Conversational AI

The Medical Dialogue Task involves developing a dialogue system that can effectively communicate
with patients or medical professionals in natural language. This task is important for improving
patient care, reducing medical errors, and enhancing the overall efficiency of the healthcare system.
In this coursework, we will use the MedDialog dataset, which is a large-scale collection of medical
conversations between patients and healthcare professionals to build a medical AI based chatbot.

## Dataset

https://www.kaggle.com/datasets/dsxavier/diagnoise-me

## Instructions

The code in the notebook should run one cell at a time starting from the top down. Please make sure you have a working python installation and install torch with CUDA support for your specific operating system

Run everything one at a time, The code has been written and tested on Windows and Kaggle. If you are using linux you may need to adjust any path names to include forward slashes instead of back slashes.

### Running on Kaggle

1. To run this code on Kaggle, load the notebook into a new Kaggle notebook.
2. On the right hand side in the panel, click the "Add Input" button at the top. Select "dataset" and search for "Diagnoise me" from the available Kaggle datasets.
3. Once selected, allow time for Kaggle to import the dataset before continuing.
4. Run the code one cell at a time, starting from the top.
5. IF IN KAGGLE, PLEASE IGNORE THE CODE CELLS UNDER "Downloading MedDialog Dataset"

### Running on a local machine

1. To run this code on a local machine you will need a kaggle.json file in the working directory, containing your Kaggle username and key in the following format:
   {"username":"name","key":"ThisIsAnExampleKey"}
2. Now run the code one cell at a time
3. Please ensure you have a GPU with enough VRAM otherwise the code will not run. 16Gb+ was just about enough in our testing.

### MEMORY LIMITATIONS

At various points throughout the code are cells for clearing the GPU VRAM so the rest of the code works, everything works for us in the current layout but it may not work for you depending on environment and memory limitations. Please keep re-running these memory clearing code cells to clear memory to a sufficient level for your system.

### notes

Some code cells have comments tell you to ignore it, please don't worry about running these cells, they are for things like saving a trained model to the hub

If you have any issues please contact either one of use immediately

## Contributors

-   https://github.com/SurtMcGert
-   https://github.com/ameorazlan
