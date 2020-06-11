# Data-Wrangling-Twitter_data
Real-world data rarely comes clean. Using Python and its libraries, I will gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it.   
The dataset that I will be wrangling (and analyzing and visualizing) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog.  
This project contains document of wrangling efforts in a Jupyter Notebook, plus document of analyses and visualizations using Python and its libraries  
# Libraries need to import  
import pandas as pd  
import numpy as np  
import requests  
import tweepy 
import json    
import re   
from tweepy import OAuthHandler  
from timeit import default_timer as timer
import matplotlib.pyplot as plt    
