# Задача
Спрогнозировать коэффициент восстановления золота из золотосодержащей руды

Цель: подготовить прототип модели, которая предскажет коэффициент восстановления золота из золотосодержащей руды. Модель поможет оптимизировать производство, чтобы не запускать предприятие с убыточными характеристиками.

# Выводы
В результате обучения моделей (дерево решений, случайный лес, линейная регрессия) была найдена лучшая модель - это модель случайный лес.

С помощью построенных гистрограмм было выявлено: 

    - Ошибка тестовой выборки равна = 8.767918440927875

    - Ошибка константной выборки равна = 8.934254264147132

    - Лучшим результатом тренировочной модели стало:

Финальный sMAPE RandomForest = -7.683258154242512 Финальный sMAPE DecisionTree = -7.900912012795125

# Стек технологий
Matplotlib, NumPy, Pandas, Python, Sklearn

# Статус проекта
Завершен
