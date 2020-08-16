# College-Chatbot
A chatbot for NMAM Institute of Technology.
## Installation

### Create an environment
```console
conda create --name myenv
```

### Activate it
Windows:
```console
conda activate myenv
```
### Install PyTorch and dependencies

 ```console
conda install pytorch
conda install nltk
 ```
 
 ```console
anaconda promt: python
>>> import nltk
>>> nltk.download('punkt')
```

## Usage
Run
```console
python train.py
```
```console
python chat.py
```
![alt text](https://github.com/Rohitjk/College-Chatbot/blob/master/Capture.PNG)
The approach is inspired by this article and ported to PyTorch: https://chatbotsmagazine.com/contextual-chat-bots-with-tensorflow-4391749d0077.
