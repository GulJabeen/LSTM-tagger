### This repository contains two solutions:
#### 1. LSTM tagger (main solution)

#### 2. LSTM + CRF tagger


#### Observations and Future Work
Following tags have been predicted: iloc, i-misc, i-org, i-per <br/>
- Other tags have not been found, we need more state-of-the-art method to improve our results. As CRF can find more patterns within a text
so I tried it but didnt get good results because mistakenly I haved used old version which was deprecated. <br/>
- This model could improve more if we use character embedding and GloVe embeddings. 
- Bert could also improve the model.
