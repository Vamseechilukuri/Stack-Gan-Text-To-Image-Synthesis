# Stack Gan Text-To-Image Synthesis
Create 3 folders (test, weights,results_stage2) in your current working directory.
weights (your model weights will be saved here) test (generated images from our stage I StackGAN)
results_stage2 will have the generated images from stage2 fo StackGAN

## About Dataset
Dataset Name: Caltech-UCSD Birds-200-2011
Download from : http://www.vision.caltech.edu/visipedia/CUB-200-2011.html

## Text Embedding Model
Download char-CNN-RNN text embeddings for birds from :

https://drive.google.com/file/d/0B3y_msrWZaXLT1BZdVdycDY5TEE/view?resourcekey=0-sZrhftoEfdvHq6MweAeCjA

1. char-CNN-RNN-embeddings.pickle — Dataframe for the pre-trained embeddings of the text.
2. filenames.pickle — Dataframe containing the filenames of the images.
3. class_info.pickle — Dataframe containing the info of classes for each image.

## File View:
Project File Name:
---birds
-------test
-------text_c10
-------train
---CUB_200_2011
-------attributes
-------images
-------parts
---results
---results_2
