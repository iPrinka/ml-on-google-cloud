# TensorFlow on Google Cloud

## Week1

- **Introduction to the TensorFlow Ecosystem**
  - Recall the TensorFlow API hierarchy
  - Understand TensorFlow’s building blocks: Tensors and operations
  - Write low-level TensorFlow programs

- **Design and Build Input Data Pipelines**
  - Train on large datasets with tf.data
  - Work with in-memory files
  - Get the data ready for training
  - Describe embeddings
  - Understand scaling data with tf.Keras preprocessing layers
  - In the labs, you will learn how to:
    - Use tf.data to read data from memory
    - Use tf.data in a training loop
    - Use tf.data to read data from disk
    - Write production input pipelines with feature engineering (batching, shuffling, etc.)
    - Map from columns in the CSV to features used to train the model using Keras preprocessing layers
    - Build, train, and evaluate a model using Keras

## Week2

- **Building Neural Networks with the TensorFlow and Keras API**
  - Describe how activation functions, loss, and optimizers work
  - Build a DNN model using the Keras Sequential API
  - Use feature columns in a Keras model
  - Save/load, and deploy a Keras model on Vertex AI
  - Describe model subclassing


## Week3

- **Training at scale with Vertex AI**
  - Use TensorFlow to create your training job
  - Package up a TensorFlow model as Python package
  - Configure, start, and monitor a Vertex AI training job
