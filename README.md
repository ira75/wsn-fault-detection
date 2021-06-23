# Fault Detection in Wireless Sensor Networks


Wireless sensor networks (WSNs) are widely used in various real-life applications where the sensor nodes are randomly deployed in hostile, human inaccessible environments. Despite being robust, WSNs are prone to be faulty because they are placed in wide locations and monitoring them regularly is a tough task. 

WSNs suffer from many types of faults. Some are system-centric like calibration, battery failure, hardware failure, other are transient such as data loss, spike, gain, offset etc. Our area of interest is the fault detection using machine learning approach. 

In this project, different machine learning algorithms are used for this purpose such as Support Vector Machine (SVM), Random forest, K-Nearest Neighbor (KNN), Decision Tree, Gradient Boost, XG Boost and Recurrent Neural Network (RNN) for classification. The effectiveness of these algorithms for fault detection in WSNs is shown through an experimental study and compared them to find out the best performing algorithm.

# Dataset
The original dataset labelled TelosB motes dataset is used in this work which is based on an existing dataset published in 2010 by researchers at the university of North Carolina at Greensboro. Researchers collected the data from a simple single-hop and a multi-hop WSNs using TelosB motes. This dataset was gathered from single hop and multi hop sensors. This data consists of humidity and temperature measurements measured every 5 seconds for 6 hours. Researchers used steam of hot water to increase the humidity and the temperature to collect different measures

# Fault Induction in Dataset
To obtain these results, our analysis was based on real data which has been used and published by researchers. 4 faults in the dataset were injected namely random, malfunction, drift and bias in different proportions and created 20 datasets for the analysis. This approach is a bit different than what researchers used till now. It was able to perform multiclass classification with RNN on larger datasets and obtained decent results.

# Results and Observations

| S.no | Algorithm  | Accuracy  |
| :---:   | :-- | :-: |
| 1 | SVM | 61.83% |
| 2 | Random Forest Classifier | 84.00% |
| 3 | XG Boost | 79.93% |
| 4 | Gradient Boosting Classifier | 78.06% |
| 5 | KNN | 84.27% |
| 6 | Decision Tree Classifier | 84.16% |
| 7 | RNN | 92.74% |
