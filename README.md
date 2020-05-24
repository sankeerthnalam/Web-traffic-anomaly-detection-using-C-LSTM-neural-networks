# Web-traffic-anomaly-detection-using-C-LSTM-neural-networks
This project aims to detect anomalies in Web-Traffic using a C-LSTM architecture.  

---

### Web traffic anomaly detection using C-LSTM neural networks 

[Web traffic anomaly detection using C-LSTM neural networks ](http://sclab.yonsei.ac.kr/publications/Papers/IJ/2018_ESWA_TYK.pdf)

- This repository contains code to implement the research paper which closely simulate those run by Tae-Young kim in the paper linked above.

---

The model was tested on test data(Which is 30% of total data). The final test results for training the model for 500 epochs(as mentioned in the paper) are:

- Accuracy - 

- Precision -

- Recall -

- F1-Score -

## Conclusions from the experiment

- The Accuracy and F1-Score of the model increases as we increased the training epochs to 500.

- Changing loss function from mean-square-error to binary-cross-entropy also increased performance of the model because, this is a classification problem binary-cross-entropy loss function gives more accurate results.

- Combining CNN with LSTM greatly helped in detecting patterns and classifying anamolies with good accuracy and precision than most of LSTM networks.


# Instructions to run:

*It is assumed that you have a working copy of Conda installed*

Open up the terminal and type:

    git clone https://github.com/sankeerthnalam/Web-traffic-anomaly-detection-using-C-LSTM-neural-networks.git
    cd Web-traffic-anomaly-detection-using-C-LSTM-neural-networks
    conda env create -f environment.yml
    conda activate nnfl_project // optional
    jupyter notebook

Open up 'CLSTM.ipynb' and set path of the corresponding dataset.
