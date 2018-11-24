# Text_Summarizer_On_Patents
NLP Project on summarizing patent abstract into single sentences using Encoder-Decoder architecture in Recurrent Neural Networks.

## Abstract
The idea behind the project is to generate summary of any short documentation. It can be applied to various fields and for our case, we generated Patent titles using the Patent Abstract. We have used encoder-decoder Recurrent Neural Networks, experimenting with majorly LSTM and GRU cell units. The dataset contains patents from various domains which makes the problem more challenging. The project report is attached for your reference.

## Dataset
The dataset was generated using BigQuery on Google Patents website. The patents were extracted from various domains including but not limited to Physics, Biology, Algebra. The details of the dataset are present in the project report.

## Word Embeddings
We used 300 dimensional Glove Embeddings trained on 2.2M vocabulary and 840B tokens. (https://nlp.stanford.edu/projects/glove/)
