# Rock-vs-Mine-Prediction

# Introduction

This article is about predicting SONAR rocks against Mines with the help of Machine Learning. SONAR is an abbreviated form of Sound Navigation and Ranging. It uses sound waves to detect objects underwater. Machine learning-based tactics, and deep learning-based approaches have applications in detecting sonar signals and hence targets.

Fourier transform, wavelet transform, limit cycle, etc. are signal processing methods applicable for an underwater acoustic signal. Machine Learning enables the processing of sonar signals and target detection. It is a subfield of artificial intelligence which tells machines how to manipulate data more proficiently. The three stages of Machine Learning are taking some data as input, extracting features, and predicting new patterns. The most common ML algorithms in this field are Logistic Regression, support vector machine, principal component analysis, k-nearest neighbors (KNN), C-means clustering, etc.




![image](https://github.com/Niharika-Bathula/Rock-vs-Mine-Prediction/assets/142409759/6e335744-9f94-431b-b580-7505a1cbe1a1)



Outwardly SONAR technique has exploited the discovery of rocks and minerals which would have been very difficult otherwise. The technique exploits certain parameters which will aid to detect the surface targets or obstacle such as a rock or a mine. Machine learning has drawn the attention of maximum part of today’s emerging technology, related from banking to many consumer and product based industries, by showing the advancements in the predictive analytics. This prediction can be done using machine learning algorithm such as logistic regression which is implemented in google colab.

# DataSet
The dataset has been collected from UCI Repository. It has come across 61 features which define and differentiate Rocks and Mines and comprises of 209 samples. This data is used for training and testing purpose. The Last column in this dataset indicates that, whether it's a mine or a rock, which is useful in prediction. The dataset is included in this repository.

# Feature Engineering

Prior to model training, extensive feature engineering is performed to extract relevant information from the raw data.

This involves processing and transforming the data to create meaningful features that capture the distinguishing characteristics of solar rocks and mines.

# Model Training

Used many algorithms and came to know that KNN is giving me good result.

The selected machine learning model is trained using the training dataset, optimizing its parameters to achieve the best possible performance.

Techniques such as cross-validation and hyperparameter tuning are employed to improve the model's accuracy and generalization ability.

# Future Work

Further refine the model by incorporating additional features or exploring different machine learning algorithms.

Expand the dataset to include more diverse samples and improve the model's ability to generalize to unseen data.

Deploy the trained model in real-time systems for automated detection and classification of objects in space.

 # Conclusion

 Conducted data exploration, preprocessing and data visualization, including examination of data head, tail, description, and information to ensure data quality.

Utilized pandas library to investigate data and handle missing values effectively.

Split data into training and testing sets (80-20 split), applying various models including Linear Regression, K-Nearest Neighbors , Random Forest  and Stochastic Gradient Descent (SGD).

Achieved highest accuracy of 88% with KNN model, outperforming other models, and successfully utilized it to predict whether a given sample is a mine or rock.

The performance of the trained model is summarized in terms of its accuracy and other relevant metrics. Visualizations may also be provided to illustrate the model's predictions and any insights gained from the analysis.
 
![image](https://github.com/Niharika-Bathula/Rock-vs-Mine-Prediction/assets/142409759/01bd39af-6ceb-449b-b0ac-18b12bceaa9f)

I also learned about how different python libraries like scikit learn, numpy and pandas can be used to build and train the model.
Model evaluation using input data was also done in this project.


