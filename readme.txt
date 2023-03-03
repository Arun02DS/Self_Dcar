Self Driving Car project

source: https://images.nvidia.com/content/tegra/automotive/images/2016/solutions/pdf/end-to-end-dl-using-px.pdf

An powerful end to end approach is used to create a model on convolutional Neural Network ( CNN ).

Due to restriction of powerful GPU, Google colab free version is used . Overall after 50 epoches results are good.

To collect the Raw data a udacity simulator is used which uses the three cameras left, center and right to capture the images.
Steps in project -
	1. Data Ingestion - Data is taken from github.
	2. Imports of all important libraries.
	3. Cleaning the data and visualizing the data.
	4. Correcting Data Imbalance
	5. Splitting data into training and validation set
	6. Data augmentation
	7. Image preprocessing
	8. Batch generation
	9. CNN model from Nvidia paper
	10. Model Training
Model prediction on Udacity simulator coding on pycharm.

Modules used -

opencv-contrib-python
numpy
matplotlib
tensorflow
keras
python-socketio
Flask
eventlet