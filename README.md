# AML-in-Bitcoin-using-GAT-ResNet

Steps to run:

1. Install Python 3.9.16.
2. Install Jupyter Notebook.
3. Create a python environment to run the experiments.
4. Activate this environment using command line.
5. Install all other requirements from the requirements.txt file. (pip install -r requirements.txt)
6. Open this directory in jupyter notebook,
7. The Dataset folder contain the Elliptic Bitcoin Transaction Dataset.(Download dataset from Elliptic AML Graph Data: https://www.kaggle.com/datasets/ellipticco/elliptic-data-set)
8. The files representing each model are :
	-LR : Logistic Regression Model
	-RF : Random Forest Model
	-XGB: XGBoost Model
	-GCN: Graph Convolutional Network Model
	-GAT: Graph Attention Network Model
	-GAT-ResNet: Graph Attention Network-Residual Network Model
8. After running these model .ipynb files, the required models for evaluation are saved in Models directory.
9. Evaluation.ipynb contains the evaluation code for MCC metric used to these graph network models.	


