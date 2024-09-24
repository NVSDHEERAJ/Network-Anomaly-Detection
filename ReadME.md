# VAE for Network Anomaly Detection

## Introduction
This project addresses the critical need for effective anomaly detection in network security, introducing a novel Hybrid Variational Autoencoder (VAE) that integrates CNN layers. Aimed at enhancing anomaly detection within computer networks, this approach tackles the challenges posed by sophisticated cyber threats by examining network data for deviations in traffic patterns, device behavior, and system performance.

## Objectives
- Develop a comprehensive model that captures both spatial and temporal relationships in network traffic data.
- Improve the detection and mitigation of network anomalies through advanced machine learning techniques.

## Methodology
- **Dataset**: Utilized the UNSW-NB15 dataset, incorporating various attacks to mirror contemporary network conditions.
- **Data Preprocessing**: Included cleaning, feature engineering, and standardization to prepare the dataset for model training.
- **Model Architecture**: A hybrid VAE architecture with CNN components for efficient anomaly detection.

## Training
The problem is treated  as an unsupervised learning problem. The model is trained using the normal data and once the model understood the distribution of normal data, a combination of anomalous and normal data is used for inference and the reconstruction loss is thresholded to classify the anomalous points.

## Results
Our model demonstrates high precision and accuracy in anomaly detection, validated through rigorous testing and evaluation. Key performance metrics include precision, recall, F1-score, and AUC scores, highlighting the model's effectiveness in identifying network anomalies.

## Conclusions
The hybrid VAE model successfully predicts network anomalies with significant accuracy, though further improvements are recommended to reduce false positives and enhance model precision.

## Future Directions
- Explore advanced feature engineering techniques.
- Implement SHAP for feature importance analysis.
- Extend architecture to other datasets with inherent temporal dimensions.


## Contact
For further inquiries, please contact [Dheeraj NVS](mailto:vnaganaboina@ufl.edu) and for implementation details and results, please go through the report.

