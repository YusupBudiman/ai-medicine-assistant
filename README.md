# Chatbot Deployment with Flask and JavaScript
## Initial Setup:

Install dependencies
```
$ (venv) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
>>> quit
```
Modify `intents.json` with different intents and responses for your Chatbot

Run
```
$ Conda activate pytorch
$ (pytorch) (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (pytorch) (venv) python chat.py

$ (pytorch) (venv) python app.py
```
run live server

# if you have run all the commands above just run 
$ Conda activate pytorch
$ (pytorch) python app.py
```
run live server

