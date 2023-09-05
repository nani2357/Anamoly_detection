# **ANAMOLY DETECTION**

Anamoly Detection is also known as outlier detection. Let us understand the Outlier in the Laymen language. For instance, you are asked to remove the rotten tomatoes from bucket because if not separated it will also spoil the other good tomatoes.
 
Similarly, there are variable/features/data points which are of no use or making no difference but could be responsible for greater loss. Thus we need to find the Outliers and remove them for better accuracy.


![alt text](https://developer.mindsphere.io/apis/analytics-anomalydetection/images/DBSCAN.png)


The noise are the data points which are detected as the outliers.



***Anamolies and is classifications***

Anamoly is use to identify the rare items, suspcious items, events and outcomes which can raise a harm to the model.

The anamolies have several classifications - 

1. **Point anamolies**
When a single data point is too far from the rest data points which makes it merely impossible to make the cluster or map it to the data points or cluster then we simply remove such data points. This is called the point anamolies.
![alt text](https://www.holehouse.org/mlclass/15_Anomaly_Detection_files/Image%20[2].png)

2. **Contextual anamolies**
If the abnormality is context specific, For instance investing 1000 rupee everyday on buying shoe since you play football is normal, but odd anyway.

![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS3k8-YQ-IONhaaJUXT0kebMOi8_PmguyQNchMFYXgeWnIMHZSmjQ&s)

3. **Collective anamolies**
A set of data instance is responsible to track this anamoly. If someone is remotely using a machine and extracting the information to the local host. It gives the sign of the cyber attack.

![alt text](https://i.stack.imgur.com/4ZArw.jpg)

# **Maths used in Anamoly Detection**

![alt text](https://image.slidesharecdn.com/anomalydetectionpart120150114-150121042933-conversion-gate01/95/anomaly-detection-part-1-12-638.jpg?cb=1421820000)


## How is it Used?

Anomaly detection is widely used in various domains such as:

- **Finance**: To identify fraudulent transactions
- **Healthcare**: To detect abnormal patient readings
- **Industrial Operations**: To monitor the health of machinery
- **Security**: To detect intrusions or malware activities
- **Retail**: To identify fraudulent purchase activities

---

## Types of Anomaly Detection

1. **Supervised Anomaly Detection**: Requires a labeled dataset containing both normal and anomalous samples to train its model.
2. **Unsupervised Anomaly Detection**: Works on an unlabeled dataset to identify anomalies.
3. **Semi-supervised Anomaly Detection**: Uses both labeled and unlabeled data for training.

---

## Algorithms Used

- **Isolation Forest**
- **K-Nearest Neighbors (K-NN)**
- **One-Class SVM**
- **Autoencoders**
- **DBSCAN**

---

## Use Cases

- **Credit Card Fraud Detection**: Identifying unusual patterns that do not conform to expected behavior.
- **Health Monitoring**: Detecting unusual patient conditions.
- **Intrusion Detection**: Identifying abnormal patterns in network traffic that could signify a network or system attack.
- **Fault Detection in Manufacturing**: Identifying defects or faults in system machinery.

---

## Exploratory Data Analysis (EDA) for Anomaly Detection

EDA is crucial for understanding the dataset and making informed decisions on which algorithm to use. Some common EDA techniques for anomaly detection include:

- **Histograms**: To understand the distribution
- **Box Plots**: To identify outliers
- **Correlation Matrix**: To understand the relationships between variables
- **Scatter Plots**: To spot clustered data and anomalies

---

## Metrics for Evaluating Anomaly Detection Models

- **Precision**: The ratio of correctly predicted positive observations to the total predicted positives.
- **Recall**: The ratio of correctly predicted positive observations to the all observations in actual class.
- **F1-Score**: The weighted average of Precision and Recall.
- **Area Under ROC Curve (AUC-ROC)**: A performance measurement for classification problem at various thresholds settings.

---

## Challenges in Anomaly Detection

- **Imbalanced Data**: Anomalies are rare events, and the datasets are often highly imbalanced.
- **High Dimensionality**: Handling high-dimensional data can be computationally expensive.
- **Noise and Variability**: Anomalies can often be masked by noise in the data.

---

## Future Scope

- **Real-time Anomaly Detection**: With the advent of IoT and big data, real-time anomaly detection is becoming increasingly important.
- **Explainable AI**: Making the anomaly detection models more interpretable for better decision-making.

