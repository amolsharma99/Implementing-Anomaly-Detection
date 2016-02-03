Implementing Anomaly Detection

Anomaly is a point which deviates from our expectation by a significant margin. Our expectation should be more dependent on the recent past than the whole history. Our definition of significant should be more dependent on the recent past than the whole history. 

Example showing sample implementation of an anomaly detection system

Applications of anomaly detection - Fraud detection. Manufacturing (e.g, aircraft engine), Monitoring in Data Center.

Strategies -
One Class SVM
covriance.EllipticalEnvelope (If data is known to be gaussian distributed)


Refs -
1. A good talk on anomaly detection using holt method(or holt winters). Predict the future by exponentially weighted mean of the past. https://speakerdeck.com/rosiebloxsom/anomaly-detection-with-python
2. http://scikit-learn.org/stable/auto_examples/covariance/plot_outlier_detection.html
3. http://scikit-learn.org/stable/auto_examples/applications/plot_outlier_detection_housing.html
