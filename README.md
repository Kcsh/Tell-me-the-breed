

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
```	
git clone https://github.com/udacity/dog-project.git
cd dog-project
```

2. Download the [dog dataset] https://www.dropbox.com/sh/plmgzn5wpsuy1vq/AAAaX0RgPSElZ7anmcLLC_TKa?dl=0
3. Download the [human dataset] https://www.dropbox.com/sh/plmgzn5wpsuy1vq/AAAaX0RgPSElZ7anmcLLC_TKa?dl=0
4. Donwload the [VGG-16 bottleneck features] https://www.dropbox.com/sh/plmgzn5wpsuy1vq/AAAaX0RgPSElZ7anmcLLC_TKa?dl=0


5. (Optional) **If you are running the project on your local machine (and not using AWS)**, create (and activate) a new environment.

	- __Linux__ (to install with __GPU support__, change `requirements/dog-linux.yml` to `requirements/dog-linux-gpu.yml`): 
	```
	conda env create -f requirements/dog-linux.yml
	source activate dog-project
	```  
	- __Windows__ (to install with __GPU support__, change `requirements/dog-windows.yml` to `requirements/dog-windows-gpu.yml`):  
	```
	conda env create -f requirements/dog-windows.yml
	activate dog-project
	```

	
6. **If you are using AWS**, install Tensorflow.
```
sudo python3 -m pip install -r requirements/requirements-gpu.txt
```
	
7. Switch [Keras backend](https://keras.io/backend/) to TensorFlow.
	- __Linux__ or __Mac__: 
		```
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
		```
	- __Windows__: 
		```
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
		```
