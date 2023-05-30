# P04_Wrangle_and_Analyze_Data
This is the fourth project from the Data Analyst Nanodegree at Udacity.

## Project Overview
The goal of this project is to analyze the tweets from **WeRateDogs**, 
a Twitter account that rates dogs in pictures. Its grades often go 
above 10/10, making the grading system unique.

### Steps of this project:
1. Gathering data
2. Assessing, and Cleaning data
3. Storing data
4. Analyzing, and Visualizing data
5. Reporting

### Data sets used in this analysis:
* **Enhanced Twitter Archive** - Provided by Udacity. It’s a file containing 
more than 2000 tweets with dog ratings, each with basic tweet data. 
The method applied to use it in the Jupyter Notebook was `pd.read_csv`.
* **Image Predictions File** - Provided by Udacity. This file contains 
predictions of dog breeds based on images in the tweets and a neural network. 
I made a request using an URL and downloaded the file in my notebook.
* **Additional Data via the Twitter API** - for additional data about favorite 
count and retweet count I queried the Twitter API. The resulting file was a 
continuous JSON file.

### Files present in this repository:
* `act_report.pdf`: report with the analysis results
* `image_predictions.tsv`: file with predictions of dog breeds based on tweets images and a neural network
* `tweet_json.txt`: file built via Twitter API
* `twitter_archive_enhanced.csv`: WeRateDogs tweet archive with dog ratings
* `twitter_archive_master.csv`: combined and cleaned data
* `wrangle_act.ipynb`: notebook with the data analysis process


## Libraries required:
* pandas
* NumPy
* requests
* tweepy
* json

## Author:
* Affonso Ciekalski Soares Campos

## License
<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">
  <img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a>
  <br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">
  Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.
 
