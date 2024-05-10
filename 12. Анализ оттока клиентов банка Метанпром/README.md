Если проект не открывается, можно посмотреть его с помощью https://nbviewer.jupyter.org

## Цель проекта
В «Метанпромбанк» провести анализ оттока клиентов и сегментирование пользователей банка. 
Сегментация покажет, как клиенты пользуются услугами банка.
## Инструменты
Проект делал с помощью Python в Jupyter Notebook. Использовал библиотеку Pandas, numpy, seaborn, matplotlib, scipy, statsmodels, phik
import pandas as pd
import  as np
import seaborn as sns
import matplotlib.pyplot as plt
import scipy.stats as st
import plotly.express as px
import statsmodels.api as sm
from scipy.stats import pearsonr
!pip install phik
import phik
from statsmodels.stats.proportion import proportions_ztest
## Решение

Проведена декомпозиция исследования отточности клиентов банка «Метанпромбанк», общая отточность по банку равна 18,2%
На основе EDA выделены значения признаков оказывающих наибольшее влияние на отток клиентов
Методом проверки статистических гипотез было проверено что
оценочный доход клиента влияет на отток
Клиенты с более высоким баллом кредитного скоринга имеют меньшую вероятность оттока
Клиенты с кредитной картой имеют меньшую вероятность оттока
Выделены признаки отточных сегментов с отточностью минимум в два раза превышающей общую по банку
