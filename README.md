# datamining
pratice test
from google.colab import drive
drive.mount('/content/drive')
import pandas as pd 
import numpy as np 
import warnings
warnings.filterwarnings('ignore')
pd.set_option('display.max_columns', None)
import scipy.stats
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
from plotly.subplots import make_subplots
df = pd.read_csv(r'/content/drive/MyDrive/marketing_campaign.csv',delimiter="\t")
df
