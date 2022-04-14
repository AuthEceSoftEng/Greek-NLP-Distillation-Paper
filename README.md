# Greek NLP Distillation Paper

This is the online material of our paper "A Methodology for Enabling NLP Capabilities on edge and low-resource Devices" which will be presented in [NLDB 22](https://nldb2022.prhlt.upv.es/) conference.


## Abstract

Conversational assistants with increasing NLP capabilities are becoming commodity functionality for most new devices. However, the underlying language models responsible for language-related intelligence are typically characterized by a large number of parameters and high demand for memory and resources. This makes them a no-go for edge and low-resource devices, forcing them to be cloud-hosted, hence experiencing delays. To this end, we design a systematic language-agnostic methodology to develop powerful lightweight NLP models using knowledge distillation techniques, this way building models suitable for such low resource devices. We follow the steps of the proposed approach for the Greek language and build the first - to the best of our knowledge - lightweight Greek language model, which we make publicly available. We train and evaluate GloVe word embeddings in Greek and efficiently distill Greek-BERT into various BiLSTM models, without considerable loss in performance. Experiments indicate that knowledge distillation and data augmentation can improve the performance of simple BiLSTM models for two NLP tasks in Modern Greek, i.e., Topic Classification and Natural Language Inference, making them suitable candidates for low-resource devices.

#### Keywords

- Natural Language Processing
- Knowledge Distillation
- Word Embeddings
- Lightweight Models

## Material

- Greek GloVe embeddings
- Distilled BiLSTM models

The detailed code can be found in the [GreekBERT Distillation](https://github.com/andreasgoulas/greek-bert-distil) repository.


## License

The code and models are licensed under the [MIT License](https://opensource.org/licenses/MIT).
