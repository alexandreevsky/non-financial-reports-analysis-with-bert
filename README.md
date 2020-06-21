# Non-financial Reports Sentiment Analysis With BERT
[![Open In Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1wgpN7A_FyxO9hBz0wxPthvP9jTrnsseq?usp=sharing)

Нефинансовая отчетность используется компаниями для раскрытия информации о достижениях в области устойчивого развития, защиты окружающей среды, социальной политики, корпоративного управления.

В качестве прокси для раскрываемых нефинансовых сведений в данном исследовании используется тональность нефинансовой отчетности, оцененная при помощи модели BERT и классификаторов (Logistic Regression, SVM, Naïve Bayes, Decision Trees, Random Forest). 

При обучении моделей используется размеченная обучающая выборка, вручную составленная из текстов нефинансовых отчетов российских компаний.

В результате обучения на контрольной выборке удалось добиться *Accuracy 83%, F1 Score 81%*.  
