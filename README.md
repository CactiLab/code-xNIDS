
![](https://img.shields.io/badge/license-MIT-green.svg)
![](https://img.shields.io/badge/language-python-blue.svg)
![](https://img.shields.io/badge/framework-keras-orange.svg)



# xNIDS: Explaining Deep Learning-based Network Intrusion Detection Systems for Active Intrusion Responses

This repo includes the source code for the "Explaining Deep Learning-based Network Intrusion Detection Systems for Active Intrusion Responses" project. The code is hardware-independent and can be optimized for execution on Google Colab.

 
# Implementation Notes

Testing and running the code is straightforward, giving users the flexibility to utilize either Google Colab or a local machine for their testing purposes.

1. **Google Colab**:
   > git clone https://github.com/CactiLab/code-xNIDS.git
   - Rename the folder
   > mv code-xNIDS   xNIDS
   - Upload the folder to **Colab Notebooks**
   - Run the **explanation.ipynb** notebook

2. **Local Machine**:
   
   > pip install -r requirement.txt
   
   - Please update the file path within the script (**explanation.py**) to match your current folder.
   - Remove the unneccesary lines.
   > python explanation.py
 3. **Retrain the DL-NIDS**
    - Please carefully update the testcases accordingly in the **explantion.py** if the users want to retrain the models. 
    - **kitsune.ipynb** contains the reimplementation of kitnet.
    - **kdd.ipynb** includes one *Autoencoder* and one **stateless** *RNN* based DL-NIDS
    - **kdd_histroy.ipynb** contains one **stateful** LSTM based DL-NIDS
# Citation & Paper


The results of this project was published in the paper entitled "xNIDS: Explaining Deep Learning-based Network Intrusion Detection Systems for Active Intrusion Responses" in the USENIX Security 2023. If you want to cite our paper in your work, please use the following BibTeX entry.

```
@inproceedings{wei2023xnids,
 title = {{xNIDS: Explaining Deep Learning-based Network Intrusion Detection Systems for Active Intrusion Responses}},
 author = {Wei, Feng and Li, Hongda and Zhao, Ziming and Hu, Hongxin},
 booktitle = {{USENIX Security}},
 year = {2023},
}

```