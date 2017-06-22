![ucl-logo](http://static.ucl.ac.uk/img/ucl-logo.svg)

This repository contains a wide range of my API models and tests written on machine learning topics

Work in process ......

## Contents
* [Machine Learning](https://github.com/zhedongzheng/finch/blob/master/README.md#machine-learning)
  * [Linear Model](https://github.com/zhedongzheng/finch/blob/master/README.md#linear-model)
  * [Support Vector Machine](https://github.com/zhedongzheng/finch/blob/master/README.md#support-vector-machine)
  * [Ensemble](https://github.com/zhedongzheng/finch/blob/master/README.md#ensemble)
  * [Decomposition](https://github.com/zhedongzheng/finch/blob/master/README.md#decomposition)
* [Deep Learning](https://github.com/zhedongzheng/finch/blob/master/README.md#deep-learning)
  * [Multilayer Perceptron](https://github.com/zhedongzheng/finch/blob/master/README.md#multilayer-perceptron)
  * [Convolutional Network](https://github.com/zhedongzheng/finch/blob/master/README.md#convolutional-network)
  * [Recurrent Network](https://github.com/zhedongzheng/finch/blob/master/README.md#recurrent-network)
  * [Autoencoder](https://github.com/zhedongzheng/finch/blob/master/README.md#autoencoder)
  * [Highway Network](https://github.com/zhedongzheng/finch/blob/master/README.md#highway-network)
  * [Generative Adversarial Network](https://github.com/zhedongzheng/finch/blob/master/README.md#generative-adversarial-network)
* [Natural Language Processing](https://github.com/zhedongzheng/finch/blob/master/README.md#natural-language-processing)
  * [Preprocessing](https://github.com/zhedongzheng/finch/blob/master/README.md#preprocessing)
  * [Language Model](https://github.com/zhedongzheng/finch/blob/master/README.md#language-model)
  * [Sentiment Classification](https://github.com/zhedongzheng/finch/blob/master/README.md#sentiment-classification)
  * [POS Tagging](https://github.com/zhedongzheng/finch/blob/master/README.md#pos-tagging)
  * [Text Generation](https://github.com/zhedongzheng/finch/blob/master/README.md#text-generation)
  * [Segmentation](https://github.com/zhedongzheng/finch/blob/master/README.md#segmentation)
* [Computer Vision](https://github.com/zhedongzheng/finch/blob/master/README.md#computer-vision)
  * [OpenCV](https://github.com/zhedongzheng/finch/blob/master/README.md#opencv)

## Machine Learning
#### Linear Model
* TensorFlow &nbsp; | &nbsp; Linear Regression &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/linear_model/linear_regr.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/linear_model/linear_regr_test.py) &nbsp; | &nbsp;

* TensorFlow &nbsp; | &nbsp; Logistic Regression &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/linear_model/logistic.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/linear_model/logistic_test.py) &nbsp; | &nbsp;

* Java &nbsp; | &nbsp; Logistic Regression &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/java-models/LogisticRegression.java) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/java-models/LogisticRegressionTest.java) &nbsp; | &nbsp;
#### Support Vector Machine
* TensorFlow &nbsp; | &nbsp; Linear SVM Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/svm/svm_linear_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/svm/svm_linear_clf_test.py) &nbsp; | &nbsp;

* Java &nbsp; | &nbsp; Linear SVM Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/java-models/LinearSVM.java) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/java-models/LinearSVMTest.java) &nbsp; | &nbsp;

* Libsvm &nbsp; | &nbsp; Non-linear SVM Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/classic-models/libsvm_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/classic-models/libsvm_clf_test.py) &nbsp; | &nbsp;
#### Ensemble
* Python &nbsp; | &nbsp; Bagging Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/classic-models/bagging_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/classic-models/bagging_clf_test.py) &nbsp; | &nbsp;

* Python &nbsp; | &nbsp; Adaboost Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/classic-models/adaboost_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/classic-models/adaboost_clf_test.py) &nbsp; | &nbsp;

* Python &nbsp; | &nbsp; Random Forest Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/classic-models/random_forest_clf.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/classic-models/random_forest_clf_test.py) &nbsp; | &nbsp;
#### Decomposition
* TensorFlow &nbsp; | &nbsp; Non-negative Matrix Factorization &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/decomposition/nmf.py) &nbsp; | &nbsp; [MovieLens Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/decomposition/nmf_movielens_test.py) &nbsp; | &nbsp;
## Deep Learning
#### Multilayer Perceptron
* TensorFlow &nbsp; | &nbsp; MLP Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/mlp/mlp_clf.py) &nbsp; | &nbsp; [MNIST Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/mlp/mlp_clf_mnist_test.py) &nbsp; | &nbsp; [CIFAR10 Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/mlp/mlp_clf_cifar10_test.py) &nbsp; | &nbsp;

* PyTorch &nbsp; | &nbsp; MLP Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/mlp/mlp_clf.py) &nbsp; | &nbsp; [MNIST Test](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/mlp/mlp_clf_mnist_test.py) &nbsp; | &nbsp; [CIFAR10 Test](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/mlp/mlp_clf_cifar10_test.py) &nbsp; | &nbsp; 
#### Convolutional Network
* TensorFlow &nbsp; | &nbsp; Conv2D Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/cnn/conv_2d_clf.py) &nbsp; | &nbsp; [MNIST Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/cnn/conv_2d_clf_mnist_test.py) &nbsp; | &nbsp; [CIFAR10 Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/cnn/conv_2d_clf_cifar10_keras_idg_test.py) &nbsp; | &nbsp;

* PyTorch &nbsp; | &nbsp; Conv2D Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/cnn/cnn_clf.py) &nbsp; | &nbsp; [MNIST Test](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/cnn/cnn_clf_mnist_test.py) &nbsp; | &nbsp; [CIFAR10 Test](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/cnn/cnn_clf_cifar10_test.py) &nbsp; | &nbsp;
#### Recurrent Network
* TensorFlow &nbsp; | &nbsp; LSTM Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn/rnn_clf.py) &nbsp; | &nbsp; [MNIST Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn/rnn_clf_mnist_test.py) &nbsp; | &nbsp; [CIFAR10 Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn/rnn_clf_cifar10_test.py) &nbsp; | &nbsp;

* TensorFlow &nbsp; | &nbsp; LSTM Regressor &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn/rnn_regr.py) &nbsp; | &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn/rnn_regr_plot.py) &nbsp; &nbsp; [Preview](https://github.com/zhedongzheng/finch/blob/master/assets/rnn_regr_plot.gif) &nbsp; | &nbsp;

* PyTorch &nbsp; | &nbsp; LSTM Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/rnn/rnn_clf.py) &nbsp; | &nbsp; [MNIST Test](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/rnn/rnn_clf_mnist_test.py) &nbsp; | &nbsp; [CIFAR10 Test](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/rnn/rnn_clf_cifar10_test.py) &nbsp; | &nbsp;

#### Autoencoder
* TensorFlow &nbsp; | &nbsp; MLP Autoencoder &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/autoencoder/mlp_ae.py) &nbsp; | &nbsp; [MNIST Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/autoencoder/mlp_ae_mnist_test.py) &nbsp; | &nbsp;

* TensorFlow &nbsp; | &nbsp; Conv2D Autoencoder &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/autoencoder/conv_ae.py) &nbsp; | &nbsp; [MNIST Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/autoencoder/conv_ae_mnist_test.py) &nbsp; | &nbsp; [CIFAR10 Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/autoencoder/conv_ae_cifar10_test.py) &nbsp; | &nbsp;
#### Highway Network
* TensorFlow &nbsp; | &nbsp; MLP Highway Classifier &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/highway/mlp_hn_clf.py) &nbsp; | &nbsp; [MNIST Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/highway/mlp_hn_clf_mnist_test.py) &nbsp; | &nbsp;

#### Generative Adversarial Network
* TensorFlow &nbsp; | &nbsp; MLP GAN &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/gan/mlp_gan.py) &nbsp; &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/gan/mlp_gan_test.py) &nbsp; | &nbsp; [Conditional Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/gan/mlp_cond_gan.py) &nbsp; &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/gan/mlp_cond_gan_test.py) &nbsp; | &nbsp;

* TensorFlow &nbsp; | &nbsp; Conv GAN &nbsp; | &nbsp; MNIST &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/gan/conv_gan_mnist.py) &nbsp; &nbsp; [Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/gan/conv_gan_mnist_test.py) &nbsp; | &nbsp;

## Natural Language Processing
#### Text Preprocessing
* Python &nbsp; | &nbsp; [Text Cleaning](https://github.com/zhedongzheng/finch/blob/master/nlp-models/text-cleaning.ipynb)

* Python &nbsp; | &nbsp; [Word Indexing](https://github.com/zhedongzheng/finch/blob/master/nlp-models/word-indexing.ipynb)

#### Language Model
* Python &nbsp; | &nbsp; LSA &nbsp; | &nbsp; [Book Titles Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/lsa_test.py)

* Python &nbsp; | &nbsp; Tri-Gram &nbsp; | &nbsp; [Amazon Review Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/trigram_test.py) &nbsp; | &nbsp;

* Python &nbsp; | &nbsp; TF-IDF &nbsp; | &nbsp; [Brown Corpus Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tfidf_brown_test.py) &nbsp; | &nbsp;

* TensorFlow &nbsp; | &nbsp; Skip-Gram &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/word2vec_skipgram.py) &nbsp; | &nbsp; [Text8 Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/word2vec_skipgram_text8_test.py) &nbsp; | &nbsp;

#### Sentiment Classification
* Python &nbsp; | &nbsp; TF-IDF + Logistic Regression &nbsp; | &nbsp; [IMDB Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/tfidf_imdb_test.py) &nbsp; | &nbsp;

* TensorFlow &nbsp; | &nbsp; LSTM &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn/rnn_text_clf.py) &nbsp; | &nbsp; [IMDB Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/rnn/rnn_text_clf_imdb_test.py) &nbsp; | &nbsp;

* TensorFlow &nbsp; | &nbsp; Conv1D &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/cnn/conv_1d_text_clf.py) &nbsp; &nbsp; [IMDB Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/cnn/conv_1d_text_clf_imdb_test.py) &nbsp; | &nbsp; Concatenated Conv1D &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/cnn/concat_conv_1d_text_clf.py) &nbsp; &nbsp; [IMDB Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/cnn/concat_conv_1d_text_clf_imdb_test.py) &nbsp; | &nbsp; Highway Conv1D &nbsp; &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/highway/conv_1d_hn_text_clf.py) &nbsp; &nbsp; [IMDB Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/highway/conv_1d_hn_text_clf_imdb_test.py) &nbsp; | &nbsp;

* TensorFlow &nbsp; | &nbsp; Conv1D-LSTM &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/cnn_rnn/conv_rnn_text_clf.py) &nbsp; | &nbsp; [IMDB Test](https://github.com/zhedongzheng/finch/blob/master/tensorflow-models/cnn_rnn/conv_rnn_text_clf_imdb_test.py) &nbsp; | &nbsp;

* PyTorch &nbsp; | &nbsp; LSTM &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/rnn/rnn_text_clf.py) &nbsp; | &nbsp; [IMDB Test](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/rnn/rnn_text_clf_imdb_test.py) &nbsp; | &nbsp;

#### POS Tagging
* TensorFlow &nbsp; | &nbsp; LSTM &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/rnn_seq2seq_clf.py) &nbsp; | &nbsp; [CoNLL-2000 Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/pos_rnn_test.py) &nbsp; | &nbsp;

* PyTorch &nbsp; | &nbsp; LSTM &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/rnn/rnn_seq_clf.py) &nbsp; | &nbsp; [CoNLL-2000 Test](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/rnn/rnn_tagging_test.py) &nbsp; | &nbsp;

#### Text Generation
* TensorFlow &nbsp; | &nbsp; Char-LSTM &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/rnn_text_gen.py) &nbsp; | &nbsp; [Anna Karenina Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/rnn_text_gen_anna_test.py) &nbsp; | &nbsp;

#### Segmentation
* TensorFlow &nbsp; | &nbsp; LSTM &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/nlp-models/rnn_seq2seq_clf.py) &nbsp; | &nbsp; [ICWB2 Test](https://github.com/zhedongzheng/finch/blob/master/nlp-models/chseg_rnn_test.py) &nbsp; | &nbsp;

* PyTorch &nbsp; | &nbsp; LSTM &nbsp; | &nbsp; [Model](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/rnn/rnn_seq_clf.py) &nbsp; | &nbsp; [ICWB2 Test](https://github.com/zhedongzheng/finch/blob/master/pytorch-models/rnn/rnn_chseg_test.py) &nbsp; | &nbsp;

## Computer Vision
#### OpenCV
* OP &nbsp; | &nbsp; [Resize](https://github.com/zhedongzheng/finch/blob/master/cv-models/resize.ipynb)

* OP &nbsp; | &nbsp; [Rotations](https://github.com/zhedongzheng/finch/blob/master/cv-models/rotations.ipynb)

* Segmentation &nbsp; | &nbsp; [Contours](https://github.com/zhedongzheng/finch/blob/master/cv-models/contours.ipynb)

* Segmentation &nbsp; | &nbsp; [Sorting Contours](https://github.com/zhedongzheng/finch/blob/master/cv-models/sorting-contours.ipynb)

* Detection &nbsp; | &nbsp; [Face & Eye Detection Using Cascade Classifier](https://github.com/zhedongzheng/finch/blob/master/cv-models/face-eye-detection.ipynb)

* Detection &nbsp; | &nbsp; [Walker & Car Detection Using Cascade Classifier](https://github.com/zhedongzheng/finch/blob/master/cv-models/car-walker-detection.ipynb)
