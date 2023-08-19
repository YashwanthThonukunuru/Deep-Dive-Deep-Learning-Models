# Deep Dive into Deep Learning Models

In this project, We have explored various deep learning models including Multi-layer Perceptrons (MLPs), Convolutional Neural Networks (CNNs), and Recurrent Neural Networks (RNNs). The project aims to provide insights into model architecture, performance comparison, interpretability, and application to different datasets.  The project is divided into two main sections: MLPs and Convolutional Neural Networks, as well as Recurrent Neural Networks.

## MLPs and Convolutional Neural Networks

### Dataset Preparation

We begin by loading and preprocessing the [Vehicles-in-accidents](https://github.com/Cogito2012/CarCrashDataset#overview) dataset. Necessary steps such as normalization and channel adjustments are performed to ensure optimal data representation.

### Multi-layer Perceptron Networks

Three distinct Multi-layer Perceptron networks are trained. We elaborate on the architectural decisions made, including layer configurations and parameter estimations. The models' performance is compared based on various metrics, considering layers, parameters, and accuracy.

### Convolutional Neural Networks

- Experimentation: We conduct multiple experiments to identify the optimal CNN architecture. Each experiment's procedure and decisions are detailed. We adhere to best practices and compare loss and accuracy metrics across different models and train-test sets.
- Data Augmentation: Data augmentation is applied to enhance model robustness. The augmentation procedure is explained, considering image preprocessing layers or customized data augmentation. Results are compared with the base CNN models.

### Interpretability Techniques

Two interpretability techniques are utilized to explain the decisions of the best-performing CNN model. We go beyond class examples and refer to additional resources, specifically https://arxiv.org/pdf/2004.14545.pdf.

### Transfer Learning

Transfer learning is employed to create a new model. The chosen pretrained model from Keras' applications is justified, along with adjustments made for task relevance.

### Conclusion

A comprehensive conclusion is drawn, comparing the results achieved with MLPs, CNNs, and their variations. The conclusion highlights performance trends and architectural insights.

## Recurrent Neural Networks

### Dataset and RNN Application

We identify an appropriate dataset for applying Recurrent Neural Networks (RNNs). The dataset's nature, task type (e.g., many-to-many, one-to-many), and suitability for RNNs are explained.

### RNN Experiments and Attention Mechanism

We conduct diverse experiments to identify a well-performing RNN architecture. Attention and memory mechanisms are applied to the best-performing model. Model comparisons and attention mechanism insights are presented.

### RNN vs. CNN

An appropriate CNN model is created for the dataset, and its results are compared with the RNN. Architecture differences are explained to showcase the strengths of each approach.

## Conclusion

This project provides a comprehensive exploration of deep learning models, offering insights into their architectural choices, performance comparisons, and interpretability techniques. By analyzing various types of neural networks, we deepen our understanding of their applications and strengths in different scenarios.
