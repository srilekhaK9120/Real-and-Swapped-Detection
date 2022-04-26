# Real-and-Swapped-Detection
Model to detect between Real Images and Various GAN Generated Images

## Dependencies
Tensorflow
Keras
Scipy
Numpy
Matplotlib
Tqdm
openCV
Pandas
CUDA Toolkit

## Training the Model
1. To train the model, first upload the Training.ipynb file to google colab and run the notebook. 
2. Adjust the epochs according to the requirement.
3. After that, save the model as a .h5 file.

To load the datasets from kaggle, firstly, you should get the API token and save as kaggle.json and mount it to the colab and run the cells given wrt the datasets.

To run the pretrained model, which is uploaded as ‘completed_trained_model.h5’, open the prediction.ipynb notebook in google colab and mount the model. Then run the cells respectively. 

