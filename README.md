<h1 align='center'>Aviation-Prediction</h1>  
  
> This repository is a Final Year curriculum project for Bachelor of Engineering.  
  
The main idea of this project is the visualization and prediction of the Airplane Crashes and Accident Fatalities.  
The dataset used is from the National Transport Safety Board which can be downloaded from [here](https://www.ntsb.gov/_layouts/ntsb.aviation/index.aspx) or from the Dataset directory in this repo.  
  
> Anyone can contribute to this project by simply sending a pull request or opening an issue.  
  
## Requirements
1. Python 2.7
2. Numpy
3. Pandas
4. Seaborn
5. Plotly
6. Matplotlib
7. Cufflinks
8. xlrd
9. Jupyter Notebook
  
```
After installing python, you can install the python packages by simply installing using pip as
pip install numpy pandas seaborn plotly matplotlib cufflinks xlrd jupyter
```

##  Usage
The project started with cleaning the dataset that was downloaded and exported as an excel file.  
The visualization module gets you with the interactive graphs to aid the user to understand the better way of fatal and non fatal accidents.  
Functions are defined to create graphs for any parameter. This enables the reusability of the code and simply appending new dataset will automatically generate new graphs.  
The main emphasis of the visualizations is accident fatalities thus the two most obvious graphs that will be required to be generated are the Fatal Accidents and the Non-Fatal Accidents caused due to the various reasons.  
This is achieved by the two functions defined by us that requires column name as the parameter.  
```
def fatalAutoGraphs(name)
def nonFatalAutoGraphs(name)
```
  
Furthermore, from the dataset, we get the GPS Co-ordinates for the aircraft crash that can be used to plot a graph of the global accidents on the map itself. This can be visualised as  
  
____
  
<iframe width="900" height="800" frameborder="0" scrolling="no" src="//plot.ly/~Tejas-Nanaware/28.embed"></iframe>  
  
____
