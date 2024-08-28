# 基于深度学习的文本分类

## 环境依赖  
torch=2.4.0, collections, sklearn, matplotlib, numpy, nltk  

## 文件说明
### 代码
cnn_word_model_train.py————CNN-wordEmb模型及训练代码  
cnn_rand_model_train.py————CNN-randEmb模型及训练代码  
cnn_word_infer.py————CNN-wordEmb模型推理代码  
cnn_rand_infer.py————CNN-randEmb模型推理代码  
utils_wjy.py————模型评估工具  
cnn_glove_model.py————CNN-gloveEmb模型代码  
rnn_word_model.py————GRU-wordEmb-bi模型代码，含GRU-wordEmb-one与RNN-wordEmb-bi模型代码  
rnn_word_train.py————GRU-wordEmb-bi模型以及变体训练代码  
cnn_glove_train.py————CNN-gloveEmb模型训练代码，含构建glove嵌入  
rnn_word_infer.py————GRU-wordEmb-bi模型以及变体推理代码  
cnn_glove_infer.py————CNN-gloveEmb模型推理代码，含构建glove嵌入  
utils_wdl.py————构建词表与生成输入张量数据集代码  
rnn_rand_predict.py  RNN使用随机embedding初始化 预测脚本    
rnn_rand_train.py  RNN使用随机embedding初始化 训练脚本   
rnn_glove_predict.py  RNN使用Glove初始化 预测脚本  
rnn_glove_train.py  RNN使用Glove初始化 训练脚本   
bert_predict.py bert预测脚本 
bert_train.py bert训练脚本  
### 模型参数
cnn_word_model.pt————CNN-wordEmb完整模型  
cnn_rand_model.pt————CNN-randEmb完整模型  
cnn_glove_model_pre.pth————CNN-gloveEmb模型参数  
rnn_word_model.pth————GRU-wordEmb-bi模型参数  
rnn_word_model64_r.pth————RNN-wordEmb-bi模型参数  
rnn_word_model64_single.pth————GRU-wordEmb-one模型参数  
rnn_rand_model 随机embedding初始化模型参数    
rnn_glove_model Glove初始化模型参数  

## 使用  
`python 训练文件.py`
`python 推理文件.py`

## 数据集
数据集采用Kaggle Sentiment Analysis on Movie Reviews提供的训练集与测试集  [https://www.kaggle.com/competitions/sentiment-analysis-on-movie-reviews/data](https://www.kaggle.com/competitions/sentiment-analysis-on-movie-reviews/data)

## 模型参数
模型参数托管于GitHub  
[https://github.com/kinetsuou/Sentence-Classification](https://github.com/kinetsuou/Sentence-Classification)
