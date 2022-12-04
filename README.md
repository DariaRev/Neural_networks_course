# НИС "Нейросетевые методы в обработке текстов"

## Задание 1. 
### Создать двухслойный перцептрон и протестировать модель. Для этого используем F-score. 
Ноутбук с заданием находится в файлах. Назание - Homework1_Part1_Revenko.ipynb

## Задание 2. 
### Исследовать CBOW и skipgram. Применение и рассмотрение word2vec. Обучение модели и сравнение с "эталоном"
Ноутбук с заданием находится в файлах. Назание - Homework2_word2vec_Revenko1.ipynb. Для корректного запуска файл с обработанным текстом должен лежать в той же директории, что и файл .ipynb

В тетрадке при открытии на гитхабе не показывается лосс, поэтому я решила включить скриншоты сюда:

Закачка данных

![Закачка данных](https://user-images.githubusercontent.com/32986053/202277398-07908125-7395-4220-bce8-81be251662fa.png)

Первый раз обучение модели

![Первый раз обучение модели](https://user-images.githubusercontent.com/32986053/202277465-dfd4794c-e0d6-4fbc-88e3-a3c5d7ebbb7d.png)

Второй раз обучение модели

![Второй раз обучение модели](https://user-images.githubusercontent.com/32986053/202277563-157e7414-013d-460a-a225-7fe5ec405515.png)

## Задание 3.
### Обучить модель и улучшить точность
Ноутбук с заданием находится в файлах. Название - Homework3_classification_Revenko.ipynb
Помимо этого я попробовала обучить модель при помощи bert, тетрадка называется BERT_Fine_Tuning_Sentence_Revenko_ipynb_.ipynb

Итог: берт справился лучше за меньшее количество эпох, но это заняло больше времени, чем LSTM и CNN.
