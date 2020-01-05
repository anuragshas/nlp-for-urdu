# NLP for Urdu

This repository contains State of the Art Language models and Classifier for Urdu,
 spoken mainly in Pakistan and India, and also in Nepal, Bangladesh and several other countries.

The models trained here have been used in [Natural Language Toolkit for Indic Languages
 (iNLTK)](https://github.com/goru001/inltk)
 
## Dataset

#### Created as part of this project

1. [Urdu Wikipedia Articles](https://www.kaggle.com/disisbig/urdu-wikipedia-articles)

2. [Urdu News Dataset](https://www.kaggle.com/disisbig/urdu-news-dataset)


## Results

#### Language Model Perplexity

| Architecture/Dataset | Urdu Wikipedia Articles |
|:--------:|:----:|
|   ULMFiT  |  13.19  |
|  TransformerXL |  12.55  |

#### Classification Metrics

##### ULMFiT

| Dataset | Accuracy | Kappa Score |
|:--------:|:----:|:----:|
| Urdu News Dataset |  95.28  |  91.58  |

#### Visualizations
 
##### Embedding Space

| Architecture | Visualization |
|:--------:|:----:|
| ULMFiT | [Embeddings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/anuragshas/nlp-for-urdu/master/language-model/embedding_projector_config.json) |
| TransformerXL | [Embeddings projection](https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/anuragshas/nlp-for-urdu/master/language-model/embedding_projector_transformer_config.json)  |

## Pretrained Language Model

Download pretrained Language Model from [here](https://drive.google.com/open?id=19LLOys3H4h9ElHmdc6mt5ylZUw5dQedB)


## Classifier

Download classifier from [here](https://drive.google.com/open?id=1MOE8GWK6RUFmN2_IhLihrugU6NOLshr2)


## Tokenizer

Trained tokenizer using Google's [sentencepiece](https://github.com/google/sentencepiece)

Download the trained model and vocabulary from [here](https://drive.google.com/open?id=19I6EKDuSkxZ_zPBiAPPriUiSGi8Bh2ma)

### Credits
[NLP for Marathi](https://github.com/goru001/nlp-for-marathi) 
