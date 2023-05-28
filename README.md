# ML-DL

Реализованные методические работы с разработкой своих моделей машинного обучения и нейросетей методами глубокого обучения на Python в рамках прохождения дисциплины "Технологии анализа данных и машинного обучения" в Финансовом университете.

### Deep Learning (DL)

- [PyTorch](https://github.com/Valyaevgeorgiy/ML-DL/blob/deep-learning/Tensor_structure.ipynb) — полноценное изучение фреймворка Torch и его главных методов, функций.
- [LinearNN](https://github.com/Valyaevgeorgiy/ML-DL/blob/deep-learning/NN_blocks_backprop.ipynb) — построение полносвязного слоя ручным методом и использованием созданного модуля в PyTorch (torch.nn.Linear) для создания наследованного класса с пропиской результата на выходе из слоя + изучение главных функций активаций и потерь с дальнейшим их применением к результату выхода из полносвязного слоя нейросети.
- [Autograd & optimization NN](https://github.com/Valyaevgeorgiy/ML-DL/blob/deep-learning/Autograd_optim_nn.ipynb) — автоматическое дифференцирование в полносвязных нейронных сетях при помощи PyTorch с дополнительными возможностями дополнения сетей встроенными в библиотеку алгоритмами оптимизации (torch.nn.optim) и изначального формирования перед обучением загрузчиков данных у входных датасетов с признаками (DataLoaders & Datasets) на примере решения задачи регрессии цен на алмазы.
- [CNN Images Classification](https://github.com/Valyaevgeorgiy/ML-DL/blob/deep-learning/Images_Class_CNN.ipynb) — изучение архитектуры возможных моделей и формирование свёрточных нейронных сетей (Convolutional Neural Networks) для решения задач классификации изображений предметов одежды, обезьян, кошек и собак, а также использование уже готовых предобученных сетей для решения поставленных ранее задач.
- [NLP Classification](https://github.com/Valyaevgeorgiy/ML-DL/blob/deep-learning/NLP_Classifications.ipynb) — изначальная предобработка текстовых данных (лемматизация, токенизация, стемминг) для последующего конструирования полносвязных нейронных сетей в рамках решения задач классификации фамилий по национальности и обзоров ресторанов в сфере обработки естественного языка (Natural Language Processing).

<hr>

### Machine Learning (ML)

- [NumPy](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/NumPy) — первоначальная работа с библиотекой NumPy в рамках работы с массивами входных данных.
- [Pandas](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Pandas) — изучение структур данных (DataFrame & Series) через библиотеку Pandas.
- [Data_analyze](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Data_analyze) — простой анализ данных в рамках закрепления пройденного материала.
- [Matplotlib & Seaborn](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Matplotlib) — визуализация данных через графики и диаграммы с применением библиотек Matplotlib & Seaborn.
- [Stochastic gradient descent](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Sgd) — построение моделей линейной парной регрессии, реализация метода градиентного спуска и визуализация кривых обучения.
- [Regression](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Regression) — построение модели множественной линейной регрессии.
- [Classification](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Classification) — изучение модели классификации и построение экземпляра модели на простом примере данных.
- [Images_classif](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Images_classif) — погружение в анализ лиц людей и построение модели классификации на изображениях лиц выборки данных из kaggle.
- [Text_classif](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Text_classif) — плотная работа с новостными текстовыми данными и построение модели классификации текстов новостей из выборки данных из sklearn.datasets.
- [Metrics_efficiency](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Metrics_efficiency) — оценка эффективности моделей бинарной классификации при помощи использования соответствующих метрик (sklearn.metrics => accuracy_score(), precision_score(), recall_score()) с последующим применением ROC-кривой и показателя AUC.
- [Learning_curves](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Learning_curves) — построение кривых обучения в течение анализа и обработки данных для моделей классификации с дополнительным учётом параметров регуляризации модели.
- [Preprocessing](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Preprocessing) — освоение способов предобработки данных для начала анализа датасета перед обучением модели.
- [EDA](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/EDA) — полноценная обработка данных с описательной статистикой перед стадией построения модели машинного обучения (модель классификации, которая предсказывает, кто забьёт первый мяч в финале Чемпионата Мира 2022 в Катаре). 
- [Clustering](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/Clustering) — изучение логики работы кластеризации в машинном обучении как модели обучения без учителя со всеми тонкими моментами на тренировочном датасете.
- [PCA](https://github.com/Valyaevgeorgiy/Machine_learning/tree/main/PCA) — знакомство с методом главных компонентов в анализе датасета и использовании понижения его размерности до ключевых категорий в целях реализации кластеризации.
 
