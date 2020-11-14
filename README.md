# Hashtag #Image-Classification-Bot

### Image classification project || Final project ITC

Our project goal is creating a model that classifies images and labels them by common tags (multi label classification model). The classifier would be deployed on a telegram bot, allowing real time output for users.

There are many types of models (or algorithms) that can help us achieve our project goal; among them are: ResNet, Inception, VGG and Xception.

In our project we decided to focus on **VGG16**, **Inception V3** and **XCeption** and compare the results of the different models.

The reason we chose them is that they are pre-trained models and they come from different families of models (The architecture of VGG16 is considerably different from the architecture of Inception family) and we thought it is interesting to evaluate their parameters, accuracy and overall performance utilizing the same dataset. 

_In this github you will find:_

**Models’ notebooks:**
-	Create data.ipynb
-	Create vgg model.ipynb
-	Train vgg model.ipynb
-	Inception V3.ipynb
-	Xception.ipynb

**API notebook:**
-	Telegram.ipynb 

and **“Final Document”**.

We recommend you to read the “Final Document” to have a more theoretical background about the project, the process, its results and future recommendation for further work.

The weights of the models and the dataset are too heavy, so we kept them in this [google drive](https://drive.google.com/drive/folders/1ZngTd4uzFC6W-dSsN3ri0n72CXzALkys?usp=sharing).

_In the drive you will find:_ 

**X1, y1…X13, y13.pkl files** – pickle files which contain the images’ numpy array and tags.

**Models’ weights and history files:**
-	Inception_model.h5
-	Vgg_model.h5
-	Xceptio_model.h5
-	Saved_model_inception.pb 
-	Saved_model.pb

**Other files:**
-	Photos.tsv000
-	Keywords.tsv000

### Running the model:

In order to run the telegram bot, please run telegram.ipynb notebook and follow this link (from a desktop or a phone client):

[https://t.me/Pic_hashtag_bot](https://t.me/Pic_hashtag_bot)

### Authors / team members:
- Limor Nunu
- Dana Makov
- Aviv Kadair
- Ron Zehavi
