# relog-test-task-solution
 relog-test-task-solution

-разделил файл test0.json на 5 частей, потому что там файлы json записываются один за другим.

-использовал алгоритм кластеризации kmeans
-для предварительной обработки данных использовал:
 a) косинусовая расстояния между точками
 b) нормализация и стандартизация(провел пару экспериментов, но это не улучшило качество оценки)
 c) разложение матрицы pca(используется для уменьшения размера расстояния между точками, и для увеличения скорости обучения)
-Силуетный анализ

-folium визуализация точек

-результаты записал на папке answers/{имя датасета}_model_{количество класстеров}
