Суть проекта — отследить влияние условий жизни учащихся в возрасте от 15 до 22 лет на их успеваемость по математике, чтобы на ранней стадии выявлять студентов, находящихся в группе риска.

Сделать это можно с помощью модели, которая предсказывала бы результаты госэкзамена по математике для каждого ученика школы. Чтобы определиться с параметрами будущей модели, нужно провести разведывательный анализ данных и составить отчёт по его результатам.

Исходный датасет - stud_math.csv. В файле 30 колонок и 395 строк. Кол-во цифровых признаков - 13, нечисловых - 17 Целевой признак - score - оценка по экзамену по математике.

Практически в каждом столбце встречаются пропущенные значения.

Этапы работы:

- Отдельно рассмотрены цифровые и номинативные переменные;

- Устранены выбросы и пустые значения;

- Построена матрица корреляций для числовых признаков;

- При помощи метода boxplot и статистичсеких методов проведен анализ влияния номинативных признаков на целевую переменную;

- В результате анализа для дальнейшего построения модели оставлено 9 признаков;

- Номинанативные признаки перекодированы в числовой формат
