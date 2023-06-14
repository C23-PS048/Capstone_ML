# Capstone_ML

## Dataset 

We have gathered a wide variety of data about the plants available on Kaggle, in total we have collected 15 types of plants and their respective diseases. However, the dataset as a whole is still unbalanced due to the limitations of the data available in the public dataset. To avoid highly biased models, we and our advisor decided to split the dataset into subsets which currently only support 3 crops: Chili, Tomato, Cauliflower. All plant details regarding plant names, short descriptions, along with diseases are available on our Google Spreadsheet.

### Links
* Google Spreadsheet: 
[Plants Detail](https://docs.google.com/spreadsheets/d/1obRxc-jtOfpJ0Ps-FyBmf4tMVE0eUovyHegHInBZg50/edit?hl=id#gid=1322000601)

* Kaggle:
    * [Full Dataset](https://www.kaggle.com/datasets/dimasirfan/added-plant-dataset)
    Provided 15 Plants, 54 Class
    * [Subset Dataset](https://www.kaggle.com/datasets/dimasirfan/plants-disease-dataset-subset)
    Provided 3 Plants: Chili, Tomato, Cauliflower

### Notes
We have already put our data (subset) which include 3 plants inside Github repo, but you can also use our kaggle to use in Google Colab. For the complete guidance and syntax needed is already included in GColab_prepare_data.ipynb. After you complete with preparing and storing the data you can continue to begin the model training in each plants model.