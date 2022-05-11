## American Sign Language Recognition using Deep Learning techniques

### Introduction
This project was part of our coursework at EE-541 Computation Introduction to Deep Learning at USC taught by Professor. Brandon Franzke in Spring 2022. 

The main idea behind this project was to apply Deep Learning based techniques to solve American Sign Language Recognition problem. We tried several CNN architectures and also explored training from scratch and transfer learning.

### Instruction to reproduce the results
Since we used Jupyter notebook to perform our experiments, we have put inline instructions in `EE541_ASL_model.ipynb` itself, please refer that and in case of any issues please reach out to us.

Currently code is suitable to run ResNet-18, ResNet-34, ResNet-50 and Custom CNN called CNNBaseline in the notebook.

The notebook has some outputs which we got while finetuning it for ResNet-34 architecture.

We recommend to open this notebook in Google-Colab with GPU-runtime

### Models available on request
As per the guidelines on Piazza, we have following models (`.pth`) available and we can share the same based on further instructions.

1. CNNBaseline_sc_checkpoint_98.70.pth:

   This is the baseline CNN model that we trained as a baseline for comparing with ResNet architectures. Please note we had also tried a smaller version of the baseline that performed poor due to which we also explored state-of-the-art ResNet variant. Unfortunately we didn't save the model as it didn't perform well.

2. res50_sc_checkpoint_97.74.pth:

   This is the ResNet-50 based finetuned model.
3. res34_sc_checkpoint_95.67.pth:

   This is the ResNet-34 based finetuned model.

4. res18_sc_checkpoint_94.48.pth

   This is the ResNet-18 based finetuned model.

### Acknowledgement
This project builds upon the solution prepared by the fellow kagglers from whose notebook we adapted our code. Few of the kagglers whose notebooks that was helpful in this project are given below:
1. https://www.kaggle.com/grassknoted (Dataset contributor)
2. https://www.kaggle.com/julichitai
3. https://jovian.ai/gry-galario/project

