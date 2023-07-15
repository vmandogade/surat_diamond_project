1) venv created
2) README.md file created
3) requirements.txt
4) setup.py
5) app.py
6) notebooks folder-> data folder, EDA.ipynb, model_trainer.ipynb
7) src folder-> 1]components-> 1) data_ingestion.py 2) data_transformation.py 3)model_trainer.py
                2]exception.py
                3]logger.py
                4]utils.py
                5]pipeline folder-> 1)training_pipeline.py 2)prediction_pipeline.py
8) templates folder -> 1)form.html 2)index.html 3)results.html
8) Dockerfile
9) .github -> workflows ->main.yaml


Diamond Price Prediction
Introduction About the Data :
The dataset The goal is to predict price of given diamond (Regression Analysis).

There are 10 independent variables (including id):

id : unique identifier of each diamond
carat : Carat (ct.) refers to the unique unit of weight measurement used exclusively to weigh gemstones and diamonds.
cut : Quality of Diamond Cut
color : Color of Diamond
clarity : Diamond clarity is a measure of the purity and rarity of the stone, graded by the visibility of these characteristics under 10-power magnification.
depth : The depth of diamond is its height (in millimeters) measured from the culet (bottom tip) to the table (flat, top surface)
table : A diamond's table is the facet which can be seen when the stone is viewed face up.
x : Diamond X dimension
y : Diamond Y dimension
x : Diamond Z dimension
Target variable:

price: Price of the given Diamond.