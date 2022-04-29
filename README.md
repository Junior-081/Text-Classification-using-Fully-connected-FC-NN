## Problem understanding: Text Classification Using Fully-connected (FC) Neural Network (NN).
In this project we use NN, namely FC NNs, for the task of text classification. </br>

<!-- <img src="images/cat.0.jpg" align="center">
<img src="images/dog.0.jpg" align="right"> -->

![](./figures/flow-1.png) 
<!-- <br> -->
Refer to this [link](https://www.kaggle.com/datasets/prakharrathi25/google-play-store-reviews) to get the data.

# Run the project #
In this project, we have two steps: training and predicting. In the predict step, you can write any sentence for the model from your laptop and predict the class of review the sentence belongs to. Let's show you how to run the project.

If you do not have venv package, please refer to this [link](https://linuxize.com/post/how-to-create-python-virtual-environments-on-ubuntu-18-04/)
</br>

## Create virtual environment ##

```
$ python3 -m venv ENV_NAME
```
## Activate your environment ##

```
$ source ENV_NAME/bin/activate
```

## Requirement installations ##
To run this, make sure to install all the requirements by:

```
$ pip install -r requirements.txt 
```
# Training the model #

```
$ python3 main.py --model MODEL_NAME --num_epochs
```
## Example of running models ##

```
$ python3 main.py --model resnet --10
```

```
$ python3 main.py --model cnn --10
```

# Results Presentation

``` Word2Vec Loss```  </br>
![caption](./figures/W2V.jpeg) 

``` GloVe Loss```  </br>
![caption](./figures/glove1.jpeg) 

# Make prediction #

```
$python3 predict.py --image_path "./data/Images/cat.0.jpg"
```

``` Example: Result```  </br>

{sentence: "Thank you for your nice presentation" 'predicted class': ''}
---
___

---
___


# Related Projects #

* <a href= 'https://www.kaggle.com/code/preatcher/spam-classification-lstm-word2vec-98/notebook'> spam classification lstm, word2vec 98% </a>



# Contributors #
<div style="display:flex;align-items:center">

<div style="display:flex;align-items:center">
    <div>
        <h5> <a href='..'> Ababacar Dioubhane</a> </h5> <img src="./figures/Aba.jpeg" height= 7% width= 7%>
<div>
    <h5> <a href='.'> Stephen Kiilu </a> </h5> <img src="./figures/stephen.jpeg" height= 7% width= 7%>
    
<div>
    <h5> <a href='.'> Mouhamadou Mansour Sow</a> </h5> <img src="./figures/monsur.jpeg" height= 7% width= 7%>
    
</div>
 <h5> <a href='.'> Ademola Abiodun Saheed</a> </h5> <img src="./figures/IMG_20201220_154414_1.jpg" height= 7% width= 7%>
    
</div>