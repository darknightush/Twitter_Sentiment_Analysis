# Tweet Sentiment Analysis 

Developed a deep learning neural network for a tweets of US airlines customers. This dataset is avaialble on Kaggle.


https://www.kaggle.com/crowdflower/twitter-airline-sentiment


The `LSTM` Recurrent Neural Network based Flask Web App that classifies the sentiment of Customer Textual Review as Positive or Negative. 

Firstly, developed a LTSM Model by using Flask Framework and then dockerized it. Later, streamlit app is created to show the gist of sentiments.


# Getting Started

To get the app working locally:
1. Clone or download the repository locally.
2. Within the Tweet_Sentiment_Analysis directory, create a virtual Python environment with the Terminal command `python -m venv sentiment` where `sentiment` is the name of your environment. You can choose any name.
3. Activate the virtual environment with the command        `
    ```bash                 
    flaskapp\scripts\activate.bat
    ```
4. Then run the command `pip install -r requirements.txt` (In case of error in Windows at this point, you need to set the LongPathsEnabled Registry value to 1. [See here](https://stackoverflow.com/questions/54778630/could-not-install-packages-due-to-an-environmenterror-errno-2-no-such-file-or/55189256#55189256))
5. Next, set the FLASK_APP variable to app.py and FLASK_ENV to development by running the following command (for windows) 
   ```bash
    set FLASK_APP=app.py
    ```
6. Also, set the FLASK_ENV to `development` by running the following command (for windows)
    ```bash
    set FLASK_ENV=development
    ```
7. And finally, run the command `python -m flask run` to start the app
8. The terminal will output the local web address and port where the app is running. As an example, this might be `http://127.0.0.1:5000/`. Now, open a web browser and go to that web address.

9. You can also access it typing by `http://localhost:5000/`


###  Docker image : https://hub.docker.com/r/tusharbedse/flaskapp

Docker Pull Command :   `docker pull tusharbedse/flaskapp`

# Prerequisites

You will need (Python=3.8)[Python3 installed](https://www.python.org/downloads/) on your local machine.


# Built With

* [Python](https://www.python.org/) - Programming language
* [Tensorflow](https://www.tensorflow.org/) - RNN Model
* [Flask](http://flask.pocoo.org/) - Web Development Framework
* [Pandas](https://pandas.pydata.org/) - Data Manipulation and Analysis

# Interface Sample

![image](https://raw.githubusercontent.com/TusharBedse/Sentiment_Analysis/master/static/Screenshot.PNG)

 

