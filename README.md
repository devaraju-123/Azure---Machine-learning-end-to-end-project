# Azure---Machine-learning-end-to-end-project
Azure - Machine learning end to end project


Azure ML MI@ pipe line:
=================
Prepare DAta
Train Model
Package Model
vlidate Model
Deploy Model
Moniter Model

____________________________
	
Azure ML service followed by below 3 phazes
	1. Prepare Model: Using azure data bricks whichis using spark cluster for scalable environment
	2. Experiment: Trining  and test your model to build in your favorite IDE
	3. Deployee: Firstr reigister and manage your model, take fully trained model packeging your docker container
		and deployed in web service with rest end point

Azure have 2 envirnoments 1) Training Env, 2) Deployment Env

- Azure followed to train a model in 3 choise (options)
	1- local system - small data set algo is not complecated to run in windows or linux platform with cond env

	2- Remote computers -  data centers like nvidia  GPUS, ready made clusters
	3-  Microsoft provide VM clusters along with cpus and gpus


------------------------------------------
install azure sdk in python
pip install azure-storage-blob
pip install azure-mgmt-storage
pip install azureml-core

steps to create sdk python azure model
- Import standard Python modules
- Import Azure ML SDK modules
- Create Azure ML Workspace
- Write configuration to local file
- Create Azure ML Experiment - for training and test data
- Freeze the model in pickel model
- Test the model
- Log metrics to Azure ML Experiment
- End Azure ML Experiment
- Get Portal URLs
- Register the model
- Define Azure ML Deploymemt configuration
- Create enviroment configuration file
- Create Azure ML Scoring file¶
- Deploy the model to Azure Container Instance
- Expose web service
- Get the Web Service URL
