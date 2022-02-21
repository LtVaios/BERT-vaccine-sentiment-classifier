# BERT Vaccine Sentiment Classifier

## More info about BERT
📖 (https://aclanthology.org/N19-1423.pdf)

## Installation / Run
🛠️ You can download and open the jupyter notebook in any platform that supports it, like google collab which is where this classifier was developed. You will also find the datasets in /data/ that the model uses to train and evaluate. Make sure to make a file named "data" in google collab and upload the datasets inside in order to instantly run the code. Alternatively change the path in the code.

## Dataset
📄 Used a ready-to-go twitter dataset with each tweet marked with a label symbolising if it is an anti-vax, pro-vax or a neutral.


## BERT model
🤖 User the bert-base-uncased automodel available on (https://huggingface.co/models).

## Hyperparameters
    ▶️Activation function: PReLU <br />
    ▶️Layers: 2 <br />
    ▶️Size of layers: 768 -> 383 -> 3 (output) <br />
    ▶️Learning Rate: 5e-5 <br />
    ▶️Loss Function: Cross Entropy Loss  
    ▶️Optimizer: Adam <br />
    ▶️Batch size: 32 <br /> 
    ▶️Epochs: 3
    ▶️Also used:  dataset cleaning (removing puctuation, emojis, stopwords etc.), dataset tokenization and encoding
Note: The above layers and activation function are eqquiped on the output of BERT.

## Metrics 📈
    🔸 Accuracy of the model <br />
    🔸 F1, recall, precision for the whole model <br />
    🔸 F1, recall, precision for each label <br />

 ## Built With
<p float="left">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/110px-Python-logo-notext.svg.png" alt="MarineGEO circle logo" style="height: 100px; width:100px;"/>  
&emsp;&emsp;<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/10/PyTorch_logo_icon.svg/198px-PyTorch_logo_icon.svg.png" alt="MarineGEO circle logo" style="height: 120px; width:100px;"/>   <t />  
&emsp;&emsp;<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/207px-Jupyter_logo.svg.png" style="height: 100px; width:100px;"/>
&emsp;&emsp;<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/320px-NumPy_logo_2020.svg.png" alt="MarineGEO circle logo" style="height: 100px; width:200px;"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d0/Google_Colaboratory_SVG_Logo.svg/320px-Google_Colaboratory_SVG_Logo.svg.png" alt="MarineGEO circle logo" style="height: 100px; width:170px;"/>

 </p>
