# Анализ свободных текстовых ответов сотрудников на вопросы об удаленной работе
  
##
На текущий работе я сделала проект по анализу свободных текстовых ответов с помощью библиотеки для обработки естественного языка [TextHero](https://texthero.org/). 
  
Эйчары компании проводили исследование `Опрос сотрудников об удаленной работе`, чтобы выявить отношение сотрудников к удаленной работе. Вопросы в первых двух блоках были сформулированы как утверждения, с которыми нужно согласиться в той или иной степени по шкале от 1 до 10. Заключительный третий блок включал вопросы открытого типа, на которые предлагалось оставить комментарий. Я предобработала текст и  проанализировала комментарии и дополнила данные анализ первых двух блоков, предварительно предобработав текст. 

![alt](https://yadi.sk/i/N_TU8D9DKGWfig) 

частоты используемых в свободных ответах слов визуализировала с помощью scatterplot и 


В исследовании былы Результатом анализа станет публичное исследование с комментариями первых лиц компании.
  
### Используемые библиотеки: `pandas`, `numpy`, `plotly.express`, `texthero`, `preprocessing`

```import pandas as pd
import numpy as np
from scipy import stats

import plotly.express as px
from plotly import graph_objects as go
import matplotlib.pyplot as plt
from IPython.display import display
%matplotlib inline 

import texthero as hero
from texthero import preprocessing
from texthero import stopwords
default_stopwords = stopwords.DEFAULT

import warnings
warnings.simplefilter('ignore')
```
#
