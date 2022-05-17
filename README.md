# Sarcasm Detection
![](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white)
![](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![](https://img.shields.io/badge/🤗_HuggingFace-%23F7931E.svg?style=for-the-badge)

## Goal of a Project
The goal of a project is to detect sarcasm in news headlines using neural networks. A text headline is fed into neural network and output is `sarcastic` or `not sarcastic`. 

**94% accuracy** achived on test set using roBERTa model.

## Main model architectures
Tried architetures: Deep neural networks, RNN, transformers 
- RNN based models
  - RNN
  - LSTM _(with CNN)_
  - GRU
- Transformer based models 
  - BERT
  - roBERTa
  - T5
  - GPT-2 



### Setup with miniforge environment on apple silicon m1
```conda create --prefix ./env python=3.9
conda activate ./env
conda install -c apple tensorflow-deps
python -m pip install tensorflow-macos==2.7
python -m pip install tensorflow-metal==0.3
pip install numpy pandas scikit-learn matplotlib jupyter nltk keras-tuner gensim
```
