#DDos Detect with DNN (Deep Neutral Network)

## Project Description
* This project aims to create a DDoS Detection Classifier trained on labelled network traffic data.
* This model is trained to detect SSH-Bruteforce and FTP-Bruteforce.


##Details of algorithms used
###Deep Neural Networks
* One of the most well-known and recent models is the Deep Neural network which can be considered as a stack of neural networks i.e., a network composed of several layers. DNN has been successfully applied in several applications, including regression, classification, or time series prediction problems using simple auto-regressive models. The architecture comprises of at least 3 layers of nodes namely input layer, hidden layer and output layer which are interconnected; the flow of data takes place via one direction from input nodes to output node. Further DNN uses backpropagation as the training algorithm and activation function (usually sigmoid) for classification process. We train a deep neural network to classify normal and DDoS attack states by using a carefully chosen set of network statistics as an input signal.

##Dataset Description
* [Dataset]() from [Kaggle](https://www.kaggle.com/)
###Background Information
This dataset was originally created by the University of New Brunswick for analyzing DDoS data. You can find the full dataset here. This dataset was sourced fully from 2018. The dataset itself was based on logs of the university's servers, which found various DoS attacks throughout the publicly available period. When writing machine learning notebooks for this data, note that the Label column is arguably the most important portion of data, as it determines if the packets sent are malicious or not. Reference the below Column Structures heading for more information about this and more columns.

File Structure
Data is divided into various files based on date. But this project only use "02-14-2018.csv"

Column Structure
In total, there are eighty columns within this dataset, each of which corresponds to an entry in the IDS logging system that the Unversity of New Brunswick has in place. Since their system classifies traffic as both forward and backward, there are columns for both. The most important columns within this dataset are listed below.

* Dst Port (Destination port)
* Protocol
* Flow Duration
* Tot Fwd Pkts (Total forward packets)
* Tot Bwd Pkts (Total backward packets)
* Label (Label)

##Getting Started
Follow these instructions to setup the project.

###Prerequisites
Project is created using:

* Jupyter Notebook
* Python 
* Tensorflow 
* Keras
* Numpy
* Pandas 
* Matplotlib
* Pylotly
* Seaborn: 0.11.2
* Sklearn

###Installation
Can build and run direct on Kaggle with [link](https://www.kaggle.com/code/nguyentoangz/ddos-detection)
Or clone this project and setup all above lib and run it :P