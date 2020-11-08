

## Цель исследования: 
    Прогнозирование вероятности оттока пользователей для фитнес-центров 
	для каждого клиента в следующем месяце, 
	Сформировать с помощью кластеризации портреты пользователей	
## Данные
    Набор данных включает сведения о клиентах: пол, проживание или работа в районе, где находится фитнес-центр,
	участие в скидочных программах, тип приобретенного абонемента, факт оттока в текущем месяце и др.
## Используемые библиотеки

     Pandas	 
     seaborn    
     matplotlib.pyplot
     numpy
     from sklearn.model_selection import train_test_split
     from sklearn.linear_model import LogisticRegression
     from sklearn.ensemble import RandomForestClassifier
     from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score	
	 from sklearn.preprocessing import StandardScaler
     from scipy.cluster.hierarchy import dendrogram, linkage
	 from sklearn.cluster import KMeans
## Основные пункты

1. Исследовательский анализ данных 

    Выделены признаки посетителей кто ушёл (отток) и тех, кто остался (не попали в отток

2. Mодель прогнозирования оттока пользователей
    
	Рассмотрены две модели для предсказания оттока посетителей - логистеческая регрессия и случайный лес
	Для этих моделей рассчитаны метрики Accuracy, Precision, Recall

3. Kластеризация пользователей

    На основании алгоритма K-Means спрогнозированы кластеры клиентов.
	Описаны портреты посетителей.    

4. Общие выводы и базовые рекомендации по работе с клиентами

    
