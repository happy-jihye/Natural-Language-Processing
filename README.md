# Natural-Language-Processing

- bentrevett의 pytorch tutorial을 통해 학습한 내용입니다. 
- 일부 코드를 수정하고, 한국어로 설명을 적어놓았습니다.

# Tutorials
- 1 - [Simple Sentiment Analysis](https://github.com/happy-jihye/Natural-Language-Processing/blob/main/1_Simple_Sentiment_Analysis.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)(https://colab.research.google.com/github/happy-jihye/Natural-Language-Processing/blob/main/1_Simple_Sentiment_Analysis.ipynb)

  Pytorch의 torchtext를 이용한 간단한 프로젝트입니다. torchtext의 인터넷 영화 데이터베이스(IMDb dataset)을 Recurrent Neural network(RNN)를 통해 학습시켜 영화의 review가 긍정적인 리뷰인지, 부정적인 리뷰인지를 판단합니다. 
  이 튜토리얼에서는 load data, create train/test/validation splits, build a vocabulary, create data iterators, define a model and implement the train/evaluate/test loop 를 배울 수 있습니다. 머신러닝 파이프라인을 간략하게나마 학습하기 위한 튜토리얼이므로 performance가 좋지 않습니다.  

# Reference 
- https://github.com/bentrevett/pytorch-sentiment-analysis
