
<body>
    <h1> Proposal: What are these plants and will they thrive? </h1>
</body>

<p align="left"> Group Name: The Below 6ft Ones</p>

Team members: Matthew Belcher, Kristal Concepcion, Jasmine Leal, Chloe Valverde



&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For this project, we will create an image recognition program that will be able to recognize and learn the difference between the flower segments and then provide information on the flowers. Specifically, we will concentrate on flower detection, once detected add a database to determine the detected flower then provide the following information: poisonous(yes/no) and flower features.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For this specific project we decided on using a convolutional neural network (CNN) model. What is a CNN? It is a class of neural networks that specializes in processing data that has a grid-like topology, such as an image. CNN is typically used for image processing, classification, segmentation and for other auto correlated data. The main characteristic about convolutional neural network is that it has convolution layer, which uses filters to almost like twist or convolute an area in input data to smaller area, detecting important or specific part within the area.  It is because of these aspects we feel like CNN would be the most fit for out project.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The target audience: Botanists and horticulturists so they can easily identify the flowers they want to research on. In addition to this, some side target audiences are florists, home gardeners, hikers, and pet owners so their pets won't eat the poisonous plants.

	


##
<p>
<ul>Research Questions to answer</ul>

<li>How accurately can we predict the flower type </li>
<li>Can we determine if they are poisonous </li>
<li>What is the flower endangered status </li>
<li>What kind of model we will use/how to improve our model (adding different features) </li>
</p>

<p>

<ul>Software to be used</ul>

<li>Python Pandas </li>
<li>Scikit-learn </li>
<li>Python Matplotlib </li>
<li>MongoDB Database </li>
</p>

<p>


## Table of Contents

- [Extract](#extract)
- [Transform](#transform)
- [Load](#load)
- [Credits](#credits)
- [Results](#results)


## Extract
We selected the Kaggle datasets because it provided a vast array of different csv files we could combine and cross reference. 
## Transform

At the very beginning of this process we ran into a problem of the csv files not being pulled in their entirety. The problem arose form an improper pull location and had to be set to the host computer in order to load.

## Load

Once the data was loaded and cleaned, we first thad to train them with x-trains and x-tests. After this we then ran the data through a machine learning algorithm and ran it through “Transfer Learning”. With transfer learning, the code was able to use the previous epoch results so it will not have to use the entire code to make inferences, thus saving memory and time since each batch of epochs take 30 to 45 minutes to run.
 
## Results

Here we have another training set, it is the same tests as the previous but here it ran 10 epochs to raise all the accuracies. We can see the validation tests stay pretty stagnant with little pulse changes but staying relatively stable. But with this one,you can see the best epoch is the 8th and 10th epoch. It is easy to say that if this program were to go any longer there would hardly be a change in the numbers as it reaches perfection. 





##
<ul>Datasets to be used</ul>

<li>https://www.kaggle.com/code/aderezapahlevi/starter-flowers-recognition-7123e64e-8/data </li>
<li>https://www.kaggle.com/code/tarunpaparaju/plant-pathology-2020-eda-models/notebook </li>
<li>https://www.kaggle.com/code/rajmehra03/flower-recognition-cnn-keras/notebook </li>
<li>https://www.kaggle.com/datasets/hanselliott/toxic-plant-classification/code</li>
<li>https://machinelearningmastery.com/train-to-the-test-set-in-machine-learning/</li>
<li>https://plants.usda.gov/home</li>
<li>https://plantdatabase.uconn.edu/</li>

</p>


<p>

<ul>Github repo</ul>

<li>https://github.com/kconcepcion/flower-identifier-and-almanac </li>
</p>


