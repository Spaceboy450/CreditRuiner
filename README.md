# Модель кредитного скоринга

Проект представляет собой модель кредитного скоринга, что определяет вероятность выдачи кредита по введенным данным. Разрабатывался в рамках учебной дисциплины "Алгоритмизация и программирование" на 1 курсе НИУ ВШЭ.

Используемый алгоритм машинного обучения - [Random Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html), применены принципы кросс-валидации.

**F1-score 0.85**

Далее модель была интегрирована в [веб-сервис](https://github.com/variaxxx/credit-ruiner.git), что являлся одним из продуктов курсовой работы