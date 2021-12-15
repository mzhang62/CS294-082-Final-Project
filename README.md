# CS294-082-Final-Project

Repo for CS2940-082 final project.

The project notebook contains the implementation of Algorithm 1 and Algorithm 2 in [Gerald's Chapter 9](https://piazza.com/redirect/s3?bucket=uploads&prefix=paste%2Fjeqdgp7ec8fv4%2Fbb8d09923f28f8df1326688d66f267909167aa329fce3b0f33616c54e562338e%2FInformation_View_on_Data_Science.pdf). It also processes our own dataset and generate the expected MEC and the progression curve plot.

`transformer_data_with_label.csv` is the original dataset of our project. In order to satisfy Brainome's minimum dataset requirement (at least 100 instances per class), we formulate the dataset into `balanced_df_with_default_labels.csv` by only keeping classes with at least 100 instances.