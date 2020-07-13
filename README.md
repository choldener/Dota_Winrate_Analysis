# A Regression and Deep Learning Approach to Predictive Dota-2 Winrate Analysis

## Readme is a a WIP

A full writeup can be found [here](https://github.com/choldener/Dota_Winrate_Analysis/blob/master/Documents/The%20odds%20are%20with%20us.docx).
1. [Requirements](#requirements)		
2. [Overview](#overview)	
3. [FAQ](#faq)


## Requirements <a name="requirements"></a>
The project requires a handful of python packages. Install them using:
```bash
pip install -r requirements.txt
```
In addition this project utilizes JupyterLab which can be found at [https://jupyter.org/](https://jupyter.org/).
## Project Overview <a name="overview"></a>
Each of the following Notebook Files will walk you through step by step on 
* [Data Gathering and Processing](https://github.com/choldener/Dota_Winrate_Analysis/blob/master/Models/Data%20Processing.ipynb)
* [Regression Model](https://github.com/choldener/Dota_Winrate_Analysis/blob/master/Models/Logistical%20Regression.ipynb)
* [Deep Learning Model](https://github.com/choldener/Dota_Winrate_Analysis/blob/master/Models/Tensorflow.ipynb)
* [Model Comparison](https://github.com/choldener/Dota_Winrate_Analysis/blob/master/Models/Model%20Comparison.ipynb)


## FAQ <a name="faq"></a>
  1. Only 60% accuracy? That is not much better than predicting that radiant always wins.
        * Yes
  2. How did you generate similarities and plot the hero map?
        * I c
  3. Why don't you use only 6k+ games to train your model then get rich by betting on pro games?
        * Sadly, 
  4. Why did you not use other statistics, such as XPM, GPM or itemization?
        * This 
  5. How many games do I need to achieve the best accuracy possible?
        * Experimentally,
