
# NLP-extra-credit
NLP-extra-credit

First things first, clone this repo to get started.  

Okay, so this is a lecture on how to use tensorflow to build a neural network to classify text using word2vec.  

First thing, tensorflow is amazingly annoying.  It is always breaking in the strangest ways.  So what you have to do is to first create a virtual environment.  

You might have to run `pip install virtualenv` if you dont have virtual env installed yet.  


First, navigate to this folder, and run the following commands in your terminal:
```
mkdir env
python3 -m venv env/
source env/bin/activate
```
That creates a virtual env, and activates it.  


Once you have created your virtual env, you have to install the packages so you run this command:
```pip install -r requirements.txt```

Next, what we need to do is to download and extract the pre-trained word2vec model. [You download it here](https://www.kaggle.com/datasets/danielwillgeorge/glove6b100dtxt).  It's a zipped file, so unzip it and place the `glove.6B.100d.txt` file in the models folder. 

Once you do that, you should be able to run jupyter notebook.  If you dont know how to run a jupyter notebook you obviously have been sleeping through ever class.  Then follow along in the files with the video.  
