<h2>Malicious_URL_Detection</h2>
<h2>Introduction</h2>
Nowadays most cybercriminals create and spread malicious URLs to the target machine through different mediums like email, WhatsApp messages, etc. 
Whenever the victim visits these web pages through URLs. Automatically it will install the malware in the system and steal the victim's confidential/sensitive information. 
This has been the most common cyber-attack technique so far. So, it is very important and necessary to develop a model/system where it has to detect whether a URL is legitimate or malicious. 
There are so many methods available in the market to detect these activities. But it has been proven that machine learning-based models are far better than the other methods.
So, the proposed model is a machine learning-based detection method. In this project, a lightweight model is implemented which includes only lexical features of the URL.
A model will be developed and the efficiency will be compared with other classifiers like Logistic Regression, KNN, Naïve Bayes, and Random Forest in terms of accuracy.
Later it can be extended to a web-based user interface to validate the URL.
<h2>The Model Process Contains 3 Phases of work: </h2>
<li>Feature Extraction</li>
<li>Feature Reduction </li>
<li>Training and Testing the Model</li>
The Dataset is divided in the ratio of 70:30 for Training and Testing the Model. We have used library called “train-test split” for splitting the dataset. 
<h2>Algorithms Used</h2>
<li>Naive Bayes (NB)</li>
<li>Logistic Regression (LOR)</li>
<li>Support Vector Machine (SVM): </li>
<li>K-Nearest Neighbors (KNN)</li>
<li>Random Forest Classifier (RFC)</li>
Based on the performance measures like Accuracy, Precision, Recall and F1-Score, we find out which is the efficient model to detect whether a URL is malicious or not.

Result shows that the Random Forest classifier outperformed the other classifiers. SVC takes a lot of execution time when compared to other features

We can use this model to predict the Real time URL. So, we developed a Graphical User Interface (GUI) for User experience using the Flask framework. At present it is working on a local machine. 
