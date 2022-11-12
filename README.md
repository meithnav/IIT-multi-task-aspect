# Multi-Task Approach to Aspect Category & Sentiment


## Download the project source folder

Can download the source code using `git clone` or the `zip file`.


## Notebooks:

### 1)  Our Proposed Model:
This notebook consists our proposed multi-task model for aspect category classification and sentiment detection.  

### 2) POS-SciBERT Model: 
This notebook consists another competitve variant of our proposed model, wherein we feed <b>POS one-hot-encoded </b> and <b> SciBERT embeddings</b> parallelly. 

### 3) Ablation Variants Models: 
This notebook consists 3 variants viz, WithoutBiLSTM, WithoutAttention, WithoutBoth. In the notebook we have 3 different cells after <b>Models</b> header for initialising each model. Uncomment the one that you want to reproduce and let the other two be commented. Note:  


### 4) Attention Analysis: 
This notebook loads our proposed model and produces a sentence-wise heatmap distribution for aspect categories for 2 selected Reviews which is discussed in depth in our paper. 

#### IMPORTANT POINTS BEFORE RUNNING: 
a) Change the `URL PATH` accordingly before loading the dataset(pickle files) <br>
b) The 1st tab in the notebook consists all the additional dependencies required and will be downloaded on running the cell <br>
c) For `SAVE_PATH` set the URL path where you want to save the trained model <br>
  
Once all the setup is complete then execute `run all`. 


## Libraries & Dependencies used:
  <li>TensorFlow
  <li>Keras
  <li>Hugging Face
  <li>Matplotlib, numpy, pandas, pickle
