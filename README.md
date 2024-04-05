# Data Labeling for NLP model using ChatGPT

Small tryout of the data labeling concept leveraging the posibilies of the ChatGPT API.

## About

This project is done with Python(Jupyter).  
Python libraries: Pandas, json, and ChatGPT(api).  

The script does next:
1. Generates (via API) the sentences about moutains (with some diversity, variety in structure, complexity etc.)
2. Tags (again via API) the sentences one by one following the specified tagging scheme.

On the output we get the json file with tagged tokens that can be potentially used to train or fine-tune a pre-trained NLP model.

There are also possibilities to make the efficiency of the script better.
The idea before just generating the sentences was to get the ChatGPT to give the list of links to mountain-related articles and then scrape that for labeling, but later it was concidered to have a lot of redundant text. So that idea was scraped.
