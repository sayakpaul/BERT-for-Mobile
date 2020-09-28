# BERT-for-Mobile
Compares the [DistilBERT](https://arxiv.org/abs/1910.01108) and [MobileBERT](https://arxiv.org/abs/2004.02984) architectures for mobile deployments. Part of the [End-To-End TFLite Tutorials](https://github.com/ml-gde/e2e-tflite-tutorials) project. 

The notebooks included in this repository show how to fine-tune the DistilBERT model with the SST-2 and IMDB Reviews datasets for text classification. The notebooks also include the code for TensorFlow Lite model conversion. In the future, I plan to also cover question-answering with DistilBERT. 

## TensorFlow Lite model files and fine-tuned weights

* [SST-2](https://github.com/sayakpaul/BERT-for-Mobile/releases/tag/v0.2.0) (text classification)
* [IMDB](https://github.com/sayakpaul/BERT-for-Mobile/releases/tag/v0.1.0) (text classification)

## Benchmarks 

To be updated

**Note** that this repository does not contain the training and model conversion code for MobileBERT since TensorFlow Lite has got a pretty [straightforward guide](https://www.tensorflow.org/lite/tutorials/model_maker_text_classification) already available. 

<div align="center"><img src="https://i.ibb.co/ZXtwJjV/Webp-net-resizeimage.png" width="100" height="100"></img></div>
