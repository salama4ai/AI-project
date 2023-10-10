# AI-project


 The goal of this project is to implement a deep neural network model for a regression problem, the goal of this model is to predict the output of a mosfet transistor chip based on some given features and equation with some unknown variables

# problem statement
We need to build a model that predicts the transistor current value based on some parameters. Here is the list of parameters that you are allowed to use in your model as model input:

* vds (Continuous Value)

* L(um) (Continuous Value)

* W(um) (Continuous Value)

* drain_length(um) (Continuous Value)

* temperature (Continuous Value)

* vgs (Continuous Value)

* vsb (Continuous Value)

* corner (Categorical Value)



We need to predict the following value:

* id(uA) (Continuous value)



Please drop all other columns in the dataset.



The goal is optimize for minimum mean absolute percentage error for Id(uA).



Id(uA) is the current that passes through the transistor which is the same as IDS in the slides link below.



You must use tensorflow or pytorch to implement this (Deep Learning). Try to be innovative on how to choose the model architecture based on the known physical background around MOS transistors.



MOS transistors behavior could be found at:

https://redirect.cs.umbc.edu/~cpatel2/links/640/lectures/lect07_mos2.pdf



The curves of the Id vs voltage could be found in slide number 19 in the lectures above. A simplistic equation model could be found in slide 18 and above.



Data could be downloaded from:

https://drive.google.com/file/d/1F-MZMnizMAHXHRdPeh2v2Y85f7OkZCWG/view?usp=sharing



You need to create a google colab notebook and share the link here after you are done.

Please make sure to document all your work and make your code readable and make sure to use Markdown sections to describe what you are trying to do. The higher quality the documentation the better.



Deadline to complete this task is: End of Day October 15th, 2023 (The sooner you submit the better as I will hire immediately the person who is able to complete this task in high quality)



Your submission will be assessed based on the following criteria in priority order:

1. Code cleanness and readability.

2. Code documentation.

3. General documentation and usage documentation.

4. Model quality and choice decision reasoning.

5. Model performance.



As you see in the evaluation preference, model performance is the least important for me. The most important evaluation metrics are the ones above that.



I hope that clarifies everything and let me know if you have more questions.
______________________________________________________________________________________________________________________________________________________________


