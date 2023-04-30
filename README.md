#  NYUAD-2023-FeeQra

  

This project implements Quantum Transformer model to forecast time series data coming from health sector and implements quantum transformer to classify the time series data as malignant or benign.

 
There are two major components in this project :

* Feature Predictor 
* Anomaly Detector 

The image below shows the workflow of the system.

![alt text](https://github.com/obliviateandsurrender/NYUAD-2023-FeeQra/blob/main/workflow.png)

The [Feature predictor](https://github.com/obliviateandsurrender/NYUAD-2023-FeeQra/blob/main/QRNN.ipynb) predicts the future data and the [Quantum transformer](https://github.com/obliviateandsurrender/NYUAD-2023-FeeQra/blob/main/QuantumSentenceTransformer.py) classifies the data based on the data forecasted by the feature predictor.

References used for the projects : 
> [Transfer learning in hybrid classical-quantum neural networks](https://arxiv.org/abs/1912.08278)

> [Quantum variational rewinding for time series anomaly detection](https://arxiv.org/pdf/2210.16438.pdf)
