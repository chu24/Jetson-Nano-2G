# Jetson-Nano-2G
Getting started with AI on Jetson Nano

### Code Review
```sh
Interactive Classificationi Tool

Camera
	# create your camera
	# set it to running
	
Task
	# define your project TASK and what CATEGORIES of data you will collect
	# optionally define space for multiple DATASETS
	# TRANSFORMS data shape
	# make datasets

Data Collection
	# create the data collection tool widget

Model
	# choose GPU device
	# bring pre-trained model (ALEXNET, SQUEEZEDNET, RESNET18, RESTNET34)
		# the last layer of the model is modified to accept only the number of classes

Live Execution
	# set up the live execution widget

Training and Evaluation
	# define optimizer (Adam, SGD)
	# define train_eval function

Display the Interactive Tool
	# Combine all the widgets into one display
```
