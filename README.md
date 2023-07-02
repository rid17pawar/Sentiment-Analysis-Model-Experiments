# Sentiment-Analysis-Model-Experiments

## Dataset Used: 
[Twitter US Airline Sentiment - Kaggle](https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment)
</br></br>

## Experiments:
#### Experiment-1. Using Machine Learning Algorithms and Vectorization Techniques For Sentiment Analysis

*Text-Vectorization Techniques used:*
- CountVectorizer
- TfidfVectorizer
- OneHotEncoding
</br></br>
 
*ML Algorithms used:*
- Logistic Regression
- Naive Bayes
</br></br>

#### Result:
![image](https://github.com/rid17pawar/Sentiment-Analysis-Model-Experiments/assets/47048717/f8d8b986-f142-40ef-964a-b4c99483af3a)
*BEST MODEL: TFIDFvectorizer_LogisticRegression*
</br></br>

#### Experiment-2. Multi-Layer Perceptron (MLP) Models with different Model Architectures and Optimizers For Sentiment Analysis
Model Architectures:
- Model-1  </br>
 Layer (type) -               Output Shape  </br>
 layer_1 (Dense) -            (None, 64)    </br>
 layer_2 (Dense) -            (None, 64)    </br>
 layer_3 (Dense) -            (None, 3)   
 </br>
 
- Model-2 </br>
 Layer (type) -               Output Shape     </br>
 layer_1 (Dense) -            (None, 32)       </br>
 layer_2 (Dense) -            (None, 3)            
 </br>
 
- Model-3 </br>
 Layer (type) -               Output Shape      </br>
 layer_1 (Dense) -            (None, 10)        </br>
 layer_2 (Dense) -            (None, 3)       
 </br>
  
Optimizers:
- adam
- rmsprop
- sgd
</br></br>

#### Result:
![image](https://github.com/rid17pawar/Sentiment-Analysis-Model-Experiments/assets/47048717/246e00e1-0144-41b5-a8b1-1b935cbf22c9)
</br></br>

#### Experiment-3. Recurrent Neural Network (RNN) Models For Sentiment Analysis
Model Architectures:
- Simple RNN Model  </br>
 Layer (type) -               Output Shape     </br>
 embedding_12 (Embedding)    (None, 22, 100)  </br>
 layer_1 (SimpleRNN)         (None, 128)       </br>
 layer_2 (Dense)             (None, 10)        </br>
 output_layer (Dense)        (None, 3)         </br>
 </br>
 
- LSTM Model </br>
 Layer (type) -               Output Shape     </br>
 embedding_12 (Embedding)    (None, 22, 100)  </br>
 layer_1 (LSTM)              (None, 128)      </br>
 output_layer (Dense)        (None, 3)        </br>
</br>
 
- GRU Model </br>
 Layer (type) -               Output Shape     </br>
 embedding_12 (Embedding)    (None, 22, 100)  </br>
 layer_1 (GRU)               (None, 128)      </br>
 output_layer (Dense)        (None, 3)        </br>
 </br>
 
- Bidirectional LSTM Model </br>
 Layer (type) -                     Output Shape     </br>
 embedding_12 (Embedding)          (None, 22, 100)  </br>
 bidirectional_6 (Bidirectional)   (None, 128)      </br>
 output_layer (Dense)              (None, 3)        </br>
</br></br>

#### Result:
![image](https://github.com/rid17pawar/Sentiment-Analysis-Model-Experiments/assets/47048717/854ef52a-4898-4946-9346-da5f7f242f6a)
</br></br>

#### Experiment-3. Pretrained and Finetuned BERT Model For Sentiment Analysis

#### Result:
![image](https://github.com/rid17pawar/Sentiment-Analysis-Model-Experiments/assets/47048717/602f41bd-0c16-40ea-8224-0baceca013dd)
</br>
**Overall Best Model: BERT**
</br></br>
