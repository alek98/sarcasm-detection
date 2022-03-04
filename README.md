# Sarcasm Detection

# Setup with miniforge environment on apple silicon m1
```conda create --prefix ./env python=3.9
conda activate ./env
conda install -c apple tensorflow-deps
python -m pip install tensorflow-macos==2.7
python -m pip install tensorflow-metal==0.3
pip install numpy pandas scikit-learn matplotlib jupyter nltk keras-tuner
```