# Face Recognition (SVM , GridSearchCV, PCA, ML-Pipeline)
<!-- ![image](https://github.com/Kmohamedalie/Oxford-Parkinson-Diesease-Detection/assets/63104472/a4673a89-67d5-40c8-b9b5-daf60e18293e) -->

![image](https://github.com/Kmohamedalie/Face-Recognition-PCA-SVM/assets/63104472/ea4a25c8-adb4-4d50-8a36-4fa317585cd7)

**image source:**  [UMASS](http://vis-www.cs.umass.edu/lfw/) 


 
 




**Task:** In this repository we are only going to classify the faces of famous people, while the database contains over five (500) different people.


**Techniques and Algorithms applied:** [Principal Component Analysis](https://en.wikipedia.org/wiki/Principal_component_analysis), [Support Vector Machine](https://en.wikipedia.org/wiki/Support_vector_machine), [Pipeline](https://medium.com/analytics-vidhya/what-is-a-pipeline-in-machine-learning-how-to-create-one-bda91d0ceaca), [GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)







**Dataset:**  <a href="https://scikit-learn.org/0.19/auto_examples/applications/plot_face_recognition.html#sphx-glr-auto-examples-applications-plot-face-recognition-pyv">SKlearn Labeled Faces in the Wild </a>, [http://vis-www.cs.umass.edu/lfw/](http://vis-www.cs.umass.edu/lfw/)


**Complete JupyterNotebook:** [Link](https://github.com/Kmohamedalie/Face-Recognition-PCA-SVM/blob/master/Notebook/Face%20Recognition%20(SVM%20%2C%20GridSearchCV%2C%20PCA%2C%20Ml-Pipeline).ipynb)


### **Achieved metrics:**
| Algorithm | Recall | Precision | F1-score | Accuracy |
| --------- |--------|-----------|----------|----------|
|Support Vector Machine | 91.85% |	91.93%	| 91.93%  |	91.93% |


    

<br> 
<br>

**DISCLAIMER FROM THE DATABASE CREATORS:**

Labeled Faces in the Wild is a public benchmark for face verification, also known as pair matching. No matter what the performance of an algorithm on LFW, it should not be used to conclude that an algorithm is suitable for any commercial purpose. [**-Universtiy of Massachusetts**](http://vis-www.cs.umass.edu/lfw/)


    

<br>

### **Additional Information about the dataset**
Welcome to Labeled Faces in the Wild, a database of face photographs designed for studying the problem of unconstrained face recognition. The data set contains more than 13,000 images of faces collected from the web. Each face has been labeled with the name of the person pictured. 1680 of the people pictured have two or more distinct photos in the data set. The only constraint on these faces is that they were detected by the Viola-Jones face detector. More details can be found in the technical report below.

There are now four different sets of LFW images including the original and three different types of "aligned" images. The aligned images include "funneled images" (ICCV 2007), LFW-a, which uses an unpublished method of alignment, and "deep funneled" images (NIPS 2012). Among these, LFW-a and the deep funneled images produce superior results for most face verification algorithms over the original images and over the funneled images (ICCV 2007). 
  [**-umass**](http://vis-www.cs.umass.edu/lfw/)
