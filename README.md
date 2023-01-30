# This is my Roadmap to become a DataScientist.

- Data Scientist (DS) - специалист по данным. Анализирует, очищает, меняет и систематизирует данные. Строит гипотезы и проверяет их. Работает с данными для получения ответов на вопросы.
- Data engineer (DE) - тот, кто создает, тестирует и поддерживает инфраструктуры. Такие как БД и масштабируемые системы обработки данных. Создают пайплайны для запуска в промышленную эксплуатацию работу DS. Являются связующим звеном всех участников команды.

## Skills i need to learn

### Programming (Python/Go/R). I learn Python.
- Структуры данных (типы данных, списки словари, наборы, кортежи), функции записи, логика, поток управления, алгоритм поиска и сортировки, ООП и работа с внешними библиотеками;
- SQL: запросы к БД с использованием объединений, агрегатов и подзапросов;
- Комфортное использование UNIX-консоли, контроль версий в Git и использование GitHyb/GitLab;
- System Design - умение строить масштабируемые системы.

#### Ссылки на возможные курсы:
##### Python
- www.learnpython.org
- www.kaggle.com/learn/python
- www.coursera.org/specializations/python
- www.codeacademy.com/learn/learn-python-3
- pymbook.readthedocs.io
##### SQL
- www.coursera.org/learn/sql-for-data-science
- www.codeacademy.com/learn/learn-sql
- www.khanacademy.org/computing/computer-programming/sql
- www.edx.org/course/modeling-and-theory
- www.udemy.com/course/introduction-to-databases-and-sql-querying

##### Console
- www.codeacademy.com/learn/learn-the-command-line
- www.udacity.com/course/linux-command-line-basics--ud595
- www.datacamp.com/courses/introduction-to-shell-for-data-science

##### System design
- www.github.com/checkcheckzz/system-design-interview

### Data collection and preparation (Numpy, Pandas, Dask, Spark)
- Значительная часть работы DS сосредоточена на поиске подходящих данные, которые могут помочь решить проблему. 
Часто приходится собирать данные из разных законных источников - парсинга(если позволяет веб-сайт), API-интерфейсов, БД и общедоступных репозиториев;
- Когда данные собраны, часто обнаруживается, что их необходимо чистить, преобразовать, интерпретировать и т.д;
- Работа с выбросами и пропущенными значениями.

#### Ссылки на возможные курсы:
- https://stepik.org/course/120014/syllabus Numpy+Pandas
- www.kaggle.com/learn/pandas
- www.kaggle.com/learn/data-cleaning
- www.coursera.org/learn/python-data-analysis
- www.coursera.org/learn/data-cleaning
- www.datacamp.com/courses/cleaning-data-in-python
- www.codeacademy.com/learn/practical-data-cleaning

### Data analysis
- Анализ данных, получение новой информации из данных;
- Интерпретация данных и последующая передача ее в простых терминах и визуализациях;
- Основная сложность в том, что существует огромный "Зоопарк" инструментов для анализа и визуализации. Начинать надо с простых инструментов:
- seaborn;
- bokeh;
- plotly.
Полезно смотреть примеры визуализаций конкурсов на kaggle.

#### Ссылки на возможные курсы:
- www.coursera.org/learn/data-analysis-with-python
- www.kaggle.com/learn/data-visualization
- www.edx.org/learn/data-analysis
- online-learning.harvard.edu/course/data-science-wrangling
- online-learning.harvard.edu/course/data-science-visualization
- www.coursera.org/learn/python-for-data-visualization

### Math and Statistic
Математика необходима для понимания того, как работают методы машинного обучения. Например методы машинного обучения используют матрицы для хранения и обработки данных. А матрицы, линейные уровнения и векторные пространства это и есть линейная алгебра. 
Мат статистика помогает правильно выбирать распределения и устанавливать зависимость между переменными. Проведение правильного A/B тестирования не возможно без понимания что такое статистическая значимость.

Практически все собеседования в основном сосредоточены на описательной и логической статистике.
Типы статистического анализа:
- Descriptive Type of Statistical Analysis - Получение сводки данных таким образом, чтобы из нее можно было интерпретировать значимую информацию;
- Inferential Type of Statistical Analysis - используется для обобщения совокупности с использованием выборок;
- Prescriptive Analysis - идея состоит в том, чтобы дать совет, который направлен на поиск оптимальныъ рекомендаций для процесса принятия решений;
- Predictive Analysis - используется для прогнозирования будущего события;
- Causal Analysis - помогает определить, почему вещи такие, какие они есть.
- Exploratory Data Analysis - фокусируется на выявлении закономерностей в данных и выявлении неизвестных закономерностей;
- Maechanistic Analysis - выявление внутренних взаимосвязей в данных.

#### Ссылки на возможные курсы:
- www.freecodecamp.org/news/free-statistics-course
- learn.datacamp.com/courses/statistical-thinking-in-python-part-1
- www.udacity.com/course/intro-to-inferential-statistics--ud201
- www.freecodecamp.org/news/statistics-for-data-science
- www.um.edu.ar/math/montgomery.pdf
- www.statsoft.com/Textbook
- www.udacity.com/course/statistics--st095

#### Полезные ссылки, которые я нахожу по мере изучаниея:
- http://matrixmultiplication.xyz/ - визуализация сложения матриц

### Machine Learning
Машинное обучение - подраздел ИИ, изучающий методы анализа данных, который ползволяет аналитической системе самостоятельно обучаться посредством решения множества схожих задач.

Есть три основных типа обучения(естественно их больше, но сконцентрироваться для начала стоит на этих):
- supervised learning - проблемы регрессии и классификации;
- unsupervised learning - кластеризация и уменьшение размерности;
- reinforcement learning - помогает создавать системы самовознаграждения(self-rewarding).

#### Обучение с учителем - наиболее распространенный тип задач, к нему относятся:
##### Classification
- Naive Bayes
- Logistic Regression
- Artifical neural networks (ANNs)
- Decision Trees
- K-Nearest Neighbors
- Support Vector Machines
- Bagging Trees - Random Forests
- Boosted Trees - Catboost, Adaboost, GBM, XGBoost and Light GBM

##### Regression
- Linear Regression, Lasso Regression and Ridge Regression
- Decision Trees
- K-Nearest Neighbors
- Ensemble Techniques

#### Обучение без учителя
- Кластеризация - поиск не пересекающихся подмножеств данных(кластеров). Техника на основе разделения (K-means) и иерархическая кластеризация (Agglomerative and Divisive Clustering). Основная цель - понимание данных, путем выявления кластерных структур, сжатие данных(когда не хватает мощностей или есть ограничения по времени). Можно скоращать выборку оставляя только часть типичных представителей кластеров. Еще одна цель - выявление новизны. Когда объект невозможно присоединить ни к одному кластеру.
- Уменьшение размерности - Principal Component Analysis, Factor Analysis and Singular Vector Decomposition. Применяется для снижения трудоемкости работы с данными и требования к ресурсам.

#### Ссылки на возможные курсы:
- mlcourse.ai
- www.coursera.org/specializations/machine-learning-data-analysis (не работает, надо поискать)
- www.coursera.org/learn/python-for-data-science (не работает, надо поискать)
- www.coursera.org/specializations/data-science-python
- www.coursera.org/learn/machine-learning
- www.kaggle.com/learn/intro-to-machine-learning

### Общие рекомендации
- ods.ai - сообзество. объединяющее всех исследователей, инженеров и разработчиков в области Data Science  и смежных областях (45к участников)
- Участвовать в разнообразных соревнованиях: kaggle, drivendata, boosters
- Участвовать в хакатонах.
