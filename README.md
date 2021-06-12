# FYP - Smart Mirror
- **Face Reecognition**
- **Emotion Recognition**


## Face Recognition
1. Installing [python 3.6](https://www.python.org/downloads/release/python-360/)
2. Go to `c:/users/username/appdata/local/prgms/python/python3.6/scripts`
3. Open terminal and install following pacages:
	- `pip install opencv-python`
	- `pip install opencv-contrib-python`
	- `pip install Image`
	- `conda install tensorflow keras`
4. Open Face recognition folder
	- Run `python face_datasets.py`
	   >camera opens and captures photo to create datasets
	- Run `python training.py`
	- Run `python face_Recognition.py`
		> Face Recognition output shows up


## Emotion Recognition
1. Insalling [Conda](https://docs.anaconda.com/anaconda/install/windows/)
2. Setting up python 3.6:  
	 `conda create -n emotion python==3.6`
3. Open Anaconda and select environments
	- create new environment named `emotion`
	- select python 3 from the drop down menu
	- click on play button and open terminal
4. In the terminal pass the following commands
	-	 `pip install opencv-python`
	-	`pip install opencv-contrib-python`
	-	 `pip install Image`
	-	`pip install playsound`
	-	`pip install twilio`
	-	` pip install numpy`
	-	`pip install imutils`
	-	`pip install pandas`
	-	`conda install tensorflow keras`
	-	`pip install pygame`
5.  Open Terminal
	-	`cd Emotion_Recognition` 
	-	`python real_time_video.py`

> Emotion Recognition output shows up
