To run the code for this project, you must follow the following steps:

First, you must navigate to https://huggingface.co/datasets/lmsys/lmsys-chat-1m to download the data. As mentioned in
other notebooks and in the report, there is a data license agreement for this dataset that prohibits the distribution of 
raw data. As such, the raw data is not included in the public GitHub repository. Accessing the data is straightforward: navigate to the link above, create an account, agree to the data license agreement, navigate to the files and versions tab, and download the six parquet files. Then place the six raw data files in the data/raw folder in this repository. 

With the data added to a local repository, the notebooks must be ran in the following order:
1. data_loading.ipynb
2. initial_data_exploration.ipynb
3. tokenization.ipynb
4. feature_engineering.ipynb
5. data_visualization.ipynb
6. modeling.ipynb

If the notebooks are not run in this order, they may be variables or files that are not defined or created yet, which will result in errors. The purpose of each notebook is clear based on how they are named. They are detailed comments in all notebooks to explain methods and important decisions.