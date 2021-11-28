# Crop_Disease_Identifiaction
### Identification of crop diseases form image dataset - Kaggle

The dataset contains images for 15 types of crop diseases placed in individual folders. Different CNN models have been tried out some handcrafted some based on transfer learning and the accuracy score has been used to compare the models. 
The images were first read into arrays and scaled down to 64x64 rgb due to conputational constraints. A comparison for the 224x224 images would also be tried out later.
Simple CNN architecture comprising of 3 Conv layers along woth Dropout and Batchnormalization was able ot get an accuracy score of **94%**
