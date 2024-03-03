Datasets and code for AI project to classify all 151 generation one pokemon :)

Dataset is from kaggle:
https://www.kaggle.com/datasets/bhawks/pokemon-generation-one-22k

It's too large to upload to GitHub

1. Model which classifies 5 pokemon (starters, pikachu and eeveee) from separate folder
   * manual classes and image numbers
   * automatic classes and image numbers
      
2a. Model which classifies 20 pokemon from separate folder with changing learning rate
 
2b. Model which classifies 20 random pokemon from folder of 151 pokemon  

3. Model Classifiyng 20 random pokemon
   * adaptive learning rates with a scehduler
   * bigger batch size
   * built in augmentation

premadepretrainedmodel_2:
   * augementation working but not got brilliant accuracy
   * both our model and a pretrained one
   * ability to save models
   * code made more concise and cleaned up
