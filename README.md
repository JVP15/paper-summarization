# Paper Summarization

This is a class project for CMPE 297, Natural Language Programming, for the Fall 2022 semester. We use research paper summarization algorithms to automatically generate the abstract and introduction given an input paper.

# Collecting the dataset

The `collect_dataset.ipynb` notebook can be used to download and format a collection of papers and save them in .json format. 

# Installing

To install the required packages, run:

```pip install -r requirements.txt -f https://download.pytorch.org/whl/torch_stable.html```

The installation commant is also a part of `Fine_Tune_LED_For_Abstract_Generation.ipynb` (if you already have Jupyter in your environment).

NOTE: to run Selenium, you will need to install the ChromeDriver. 
You can download it from [here](https://chromedriver.chromium.org/downloads). 
Make sure to add the path to the ChromeDriver to your PATH environment variable.
