# Diabetes-Prediction
hello everyone this is siddharthan in this video we are going to build a machine learning system
that can predict whether a person has diabetes or not okay so we will be using one of the
important machine learning algorithms support vector machine okay so we will do our coding in python
and first of all let's try to understand about this uh problem statement and let's try to understand about this
support vector machine algorithm then let's get into the coding part okay so first of all let me explain you about
the support vector machine model so this is one of the important algorithms of supervised learning
algorithms okay so in supervised learning we feed the data to our machine learning model and
the machine learning model learns from the data and its respective labels okay so here
the labels are the most important things so what happens is in this case we train our model with uh
several medical information such as the blood glucose level and the insulin level of patients along with whether the person
has diabetes or not so this act as labels whether that the person is diabetic or non-diabetic
so this will be the label for this case okay so once we feed this data to our support
vector machine model what happens is it tries to plot the data in a graph okay and once it plots the data it tries
to find a hyper plane so in this image you can see a hyper plane so what happens is that this hyper plane
separates these two data okay so once we feed a new data to this model so it tries to uh put
that particular data in either of these two groups okay and by that it can predict whether the person will be diabetic or
non-diabetic okay so in this case we use several medical information such as bmi
of the patient uh their blood glucose level their insulin level etc okay so now let's try to understand the
workflow for this project so first of all we need this diabetes data okay so
we will try to train our model with the data and the respective labels okay so before
feeding this to our model so there are a lot of steps in between so we need to pre-process the data where
we will try to analyze the data and this data won't be very suitable to feed
to the machine learning model and we need to standardize this data because there are a lot of attributes here a lot
of medical information and we want all these data to be in the same bridge so what we do is we try to standardize
all this data so that all this data lies in the same range so all these things will be done in the data
pre-processing step so once we pre-process the data we will split the data into training and
testing data okay so we train our machine learning model with training data and then we try to find the accuracy
score of our model in the help of test data okay so it tells us how well our model is
performing okay so once we split the data into training data and testing data so we will feed
this to our support vector machine model okay so we will be using a classifier model where this model
will classify whether the patient has you know patient is diabetic or non-diabetic okay
so once we have drained it we have a trained support vector machine classifier so when we give a new data
so it can now predict whether the patient is diabetic or non-diabetic so this is the workflow we will be
following for this project okay so now let's get into the coding part
so we will be doing it in google collaboratory so in our channel i have already made a
video on how you can access google collaboratory from your google chrome so the index of that video is 2.1 and
you can search it from there okay first of all so now we need to
import the libraries so i'll make a text here so that it's clear
importing the dependencies okay so first let's input numpy
input numpy smp now let's import pandas so we import
pandas pd now we need to standardize the data so
for that we need a standardizer function so [Music]
from sklearn
