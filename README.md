# Анализ свободных текстовых ответов сотрудников на вопросы об удаленной работе
  
##
В процессе обучения я сделала pet-проект по анализу свободных текстовых ответов с помощью библиотеки для обработки естественного языка [TextHero](https://texthero.org/). 
  
Эйчары компании проводили исследование, чтобы выявить отношение сотрудников к удаленной работе. В исследовании былы Результатом анализа станет публичное исследование с комментариями первых лиц компании.
  
Используемые библиотеки: `pandas`, `numpy`, `plotly.express`, `texthero, preprocessing
`import pandas as pd
import numpy as np
from scipy import stats
import plotly.express as px
from plotly import graph_objects as go

import seaborn as sns 
import matplotlib.pyplot as plt
from IPython.display import display
%matplotlib inline 

import texthero as hero
from texthero import preprocessing

from texthero import stopwords
default_stopwords = stopwords.DEFAULT

#from nltk.corpus import stopwords
#stop = set(stopwords.words('russian'))

import warnings
warnings.simplefilter('ignore')`
