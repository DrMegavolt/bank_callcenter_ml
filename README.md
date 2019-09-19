# Using Google BERT to predict which product type by customer narrative. 

# Dataset
- 5 Product types which represent bank products.
- reasonably long complain text
- each complain can have only one product type (class)

# model
+ BERT uncased base
+ top 2 layers fine tuned
+ 1 Dense layer 
+ final 5 node layer for multiclass classification 


![Confusion matrix after 2 epochs](https://raw.githubusercontent.com/DrMegavolt/bank_callcenter_ml/master/conf_matrix_2_epochs.png)
