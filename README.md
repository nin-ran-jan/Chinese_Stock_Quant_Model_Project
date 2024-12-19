This is the code for the AML Project Deliverable 3. 

Due to privacy concerns, we cannot share the dataset that we acquired. However, you can use this code to test on any dummy stock data. You would need to make changes to the path variables (at the start of most Jupyter files).

Before training models on the raw dataset, you need to engineer some features for better represnetation of the data. To do so, run the Feature Engineering.ipynb file. You can now train models.

We have trained various models for our task -- MLP, XGBoost, and RNNs. To train each of these models, please run their respective jupyter notebook files. 

We have also performed SMOTE, Undersampling, and Oversampling to tackle our imbalanced dataset. To run that code, kindly run the corresponding .ipynb file. 

Once you have a good model, to simulate its running on real-world conditions, you can run the backtesting module. As you can see, the best results from our XGBoost model are shown in the outputs of the corresponding .ipynb file. 