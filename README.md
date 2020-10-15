# BERT-for-Mobile
Compares the [DistilBERT](https://arxiv.org/abs/1910.01108) and [MobileBERT](https://arxiv.org/abs/2004.02984) architectures for mobile deployments. It is a part of the [End-To-End TFLite Tutorials](https://github.com/ml-gde/e2e-tflite-tutorials) project. Here's blog post (TODO: link) that presents this comparison in a comprehensive manner. 

The notebooks included in this repository show how to use the DistilBERT model with the **SST-2 dataset** for text classification. The notebooks also include the code for TensorFlow Lite model conversion and evaluation. In the future, I also plan to cover question-answering with DistilBERT. 

**Note** that this repository does not contain the model training and model conversion code for MobileBERT since TensorFlow Lite has got a pretty [straightforward guide](https://www.tensorflow.org/lite/tutorials/model_maker_text_classification) already available. A similar guide is also available [here](https://www.tensorflow.org/lite/tutorials/model_maker_question_answer) for question-answering. 

## TensorFlow Lite model files and fine-tuned weights

* [ALBERT](https://github.com/sayakpaul/BERT-for-Mobile/releases/tag/v0.5.0)
* [DistilBERT](https://github.com/sayakpaul/BERT-for-Mobile/releases/tag/v0.4.0)
* [MobileBERT](https://github.com/sayakpaul/BERT-for-Mobile/releases/tag/v0.3.0)

## Benchmarks 

<div align="center"><img src="https://i.ibb.co/0GNVQRz/IMAGE.png"></img></div>

## Acknowledgements

Thanks to the [ML-GDE program](https://developers.google.com/community/experts) for providing GCP credits that were used in order to spin up an AI Platform Notebook. Thanks to [Khanh LeViet](https://twitter.com/khanhlvg) for his guidance. 

<div align="center"><img src="https://i.ibb.co/ZXtwJjV/Webp-net-resizeimage.png" width="100" height="100"></img></div>
