- 80 percent of movies watched on Netflix came from recommendations [43]
- 60 percent of video clicks came from home page recommendation in YouTube [30]
- presented a deep neural network based recommendation algorithm for video recommendation on YouTube [27] 
- App recommender system for Google Play with a wide & deep model [20]
- RNN based news recommender system for Yahoo News [113]

## DL techniques
- MLP / AutoEncoder / CNN / RNN / LSTM / RBM / 
- Neural AutoRegressive Distribution Estimation
- Adversarial Networks
- Attention Models
- Deep RL

### Why Deep Learning?
- Nonlinear Transformation
- Representation Learning
- Sequence Modeling

### Petential Limitation
- Interpretability
- Data Requirement
- Extensive Hyper-param Tuning

# Summuraize
## 1.MLP based RS
#### Neural Extention of Traditional Recomm Method
* Neural Network Matrix Factorization (NNMF) [37] 
*  Neural Collaborative Filtering (NCF) [53]
* DeepFM [47]
* improved DeepMF by proposing a eXtreme deep factorization machine to jointly model the explicit and implicit feature interactions [93] 
#### Feature Representation Learning with MLP
* Wide&Deep Learning [20], [13]
* Candidata Generation, Candidata Ranking(YouTube) [27]
* Facial Makeup [2]
* Collarborative Metric Learning(VML) [60]
#### Recomm with Deep Structured Semantic Model
* DeepStructuredSemanticModel(DSSM) [65], application [39,182]
* DeepSemanticSimilarity based PersonalizedRecommendation(DSPR) [182]
* MultiViewDeepNeuralNetwork(MV-DNN) [39]

## 2.AutoEncoder based RS
#### AutoEncoder based Collarborative Filtering
* AutoRec[125], extension of AutoRec(CFN) [136,137]   <- for rate prediction
* CollarborativeDenoising AutoEncoder(CDAE) [177]   <- for ranking prediction
#### Feature Representation Learning with AE
* CollaborativeDeepLearning(CDL) [159]
* RelationalStackedDenoisingAutoEncoder(RSDAE) [158] for tag recommendation
* CollarborativeVariationalAutoEncoder(CVAE) [89] easily incorporate multimedia(video, images) data source
* CollaborativeDeepRanking(CDR) [188] for pairwise framework for top-n recommendation
* DeepCollaboraitveFilteringFramework [88] 
* AutoSVD++ [196]
* HRCD [170, 171]

## 3.CNNs based RS
#### CNNs based Collarborative Filtering
* proposed using CNNs to improve NCF and presented the ConvNCF [51] 
* presented sequential recommendation (with user identifer) with CNNs [143]
#### Feature Representation Learning with CNNs
CNNs for Image Feature Extraction
* investigated the infuences of visual features to Pointof-Interest (POI) recommendation, and proposed a visual content enhanced POI recommender system (VPOI). [165]
* exploited the effetiveness of visual information in restaurant recommendation.[25]
* designed a visual Bayesian personalized ranking (VBPR) algorithm by incorporating visual features (learned via CNNs) into matrix factorization[50]
* extended VBPR with exploring user’s fashion awareness and the evolution of visual factors that user considers
when selecting items [49]
* proposed a coupled matrix and tensor factorization model for aesthetic-based clothing recommendation[191]
* proposed a personalized tag recommendation model based on CNNs.[110]
* proposed a comparative deep leaning model with CNNs for image recommendation.[84]
* ConTagNet [118] is a context-aware tag recommender system.

CNNs for Text Feature Extraction
* DeepCoNN [202] adopts two parallel CNNs to model user behaviors and item properties from review texts. 
* extended DeepCoNN by introducing a latent layer to represent the target user-target-item pair. [11]
* built an e-learning resources recommendation model [130]
* proposed using CNNs to learn feature representations form item content information (e.g., name, descriptions, identifer and
category) to enhance the accuracy of session based recommendation.[148]
CNNs for Audio and Video Feature Extraction
* proposed using CNNs to extract features from music signals.[153]
* proposed extracting audio features with the prominent CNNs model ResNet[83]
#### Graph CNNs for RS
* Graph convolutional Networks is a powerful tool for non-Eulcidean data such as: social networks, knowledge graphs, protein-interaction networks, etc [77]
* proposed considering the recommendation problem as a link prediction task with graph CNNs[6]
* proposed using graph CNNs for recommendations in Pinterest [190]


## 4.RNNs based RS
#### Session-based RS without User Identifier
* GRU4Rec, proposed a session-based recommendation model[56]
* proposed several strategies to further improve GRU4Rec model[142]
* designed a session-based recommendation model for real-world e-commerce website[176]
Two extensions demonstrate that side information has eect on enhancing session recommendation quality. 
* introduced a parallel architecture for session-based recommendation which utilizes three GRUs to learn representations from identity one-hot vectors, image feature vectors and text feature vectors.[57]
* proposed a context-aware session-based recommender system based on conditional RNNs.[132]
#### Sequential RS with User Identifier
* Recurrent Recommender Network (RRN) [175] is a non-parametric recommendation model built on RNNs
* further improved the RRNs model by modelling text reviews and ratings simultaneously.[174]
* introduced in the following text can generate readable review tips.[87]
* proposed a multi-task learning framework to simultaneously predict the returning time of users and recommend items[73]
* designed a novel type of GatedRecurrentUnit to explicit represent individual user for next item recommendation[35]
#### Feature Representation Learning with RNNs
For side information with sequential patterns, using RNNs as the representation learning tool is an advisable choice
* presented a co-evolutionary latent model to capture the co-evolution nature of users’ and items’ latent features[29]
* proposed using GRUs to encode the text sequences into latent factor model[5]
* proposed using GRUs to learn more expressive aggregation for user browsing history (browsed news), and recommend news articles with latent factor model[113]
* presented a multitask learning framework, NRT, for predicting ratings as well as generating textual tips for users simultaneously[87]
* designed a temporal DSSM model which integrates RNNs into DSSM for recommendation[135]

## 5.RBM based RS
## 6.Neural Attention based RS
#### RS with Vanilla Attention
#### RS with Co-Attention
fff## 7.Neural AutoRegressive based RS
## 8.Deep RL based RS
## 9.Adversarial Network based RS

## 8.other Hybrid Models
