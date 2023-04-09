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

##### Python practice
- https://metanit.com/python/
- https://acmp.ru/index.asp?main=tasks&str=%20&page=0&id_type=4
- https://codeforces.com/
- https://www.hackerrank.com/domains/python
- https://www.codewars.com/
- https://leetcode.com/

##### SQL
- https://stepik.org/course/63054/syllabus
- https://stepik.org/course/99786/syllabus
- www.coursera.org/learn/sql-for-data-science
- www.codeacademy.com/learn/learn-sql
- www.khanacademy.org/computing/computer-programming/sql
- www.edx.org/course/modeling-and-theory
- www.udemy.com/course/introduction-to-databases-and-sql-querying

##### SQL practice
- https://www.codewars.com/
- https://leetcode.com/
- https://www.sql-ex.ru/
- https://sqlzoo.net/wiki/SQL_Tutorial

##### Console
- www.codeacademy.com/learn/learn-the-command-line
- www.udacity.com/course/linux-command-line-basics--ud595
- www.datacamp.com/courses/introduction-to-shell-for-data-science

##### System design
- www.github.com/checkcheckzz/system-design-interview

### Data collection and preparation (Numpy, Pandas, Dask, Spark)
- Значительная часть работы DS сосредоточена на поиске подходящих данных, которые могут помочь решить проблему. 
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
- https://github.com/rogovich/2020_CPK_Python_for_Data_Analysis-4
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

#### План по изучению Математики:
##### Функции и их свойства
- Пределы функций
- Теория множеств
- Логарифмы
- Производные
- Интегралы
- Векторы (расстояния, свойства)
##### Статистика
- Статистические распределения
- Доверительные интервалы
- Медиана
- Мода
- Квантили
- Ср. квадратичное отклонение
##### Линейная алегбра
- Векторы
- Матрицы
- Операции с матрицами
- Линейные преобразования
- Линейная зависимость/независимость
- Скалярные произведения
##### Математический анализ
- Производные сложной функции
- Градиенты
- Экстремумы и их свойства
- Градиентный спуск
##### Теория вероятностей
- Расчет математического ожидания
- Расчет условной вероятности
- Формула полной вероятности
- Формула расстановок и сочетаний
- Формула Байеса
##### Теория Графов

#### Ссылки на возможные курсы:
- http://mathprofi.ru/ - Отличный сайт для изучения математики
- www.freecodecamp.org/news/free-statistics-course
- learn.datacamp.com/courses/statistical-thinking-in-python-part-1
- www.udacity.com/course/intro-to-inferential-statistics--ud201
- www.freecodecamp.org/news/statistics-for-data-science
- www.um.edu.ar/math/montgomery.pdf
- www.statsoft.com/Textbook
- www.udacity.com/course/statistics--st095

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
- https://stepik.org/course/135002/syllabus
- https://github.com/Yorko/mlcourse.ai
- https://www.youtube.com/watch?v=CPlYV_DryEo&list=PLVlY_7IJCMJeRfZ68eVfEcu-UcN9BbwiX ML.ai_EnglishEdition)
- https://www.youtube.com/watch?v=OAy96yiWohk&list=PLVlY_7IJCMJdgcCtQfzj5j8OVB_Y0GJCl&index=1 (ML.ai_RussianEdition)
- www.coursera.org/specializations/machine-learning-data-analysis (не работает, надо поискать)
- www.coursera.org/learn/python-for-data-science (не работает, надо поискать)
- www.coursera.org/specializations/data-science-python
- www.coursera.org/learn/machine-learning
- www.kaggle.com/learn/intro-to-machine-learning
- https://www.coursera.org/learn/machine-learning/home/week/1

##### Лекции ML
- https://youtu.be/ZpYj02xMImc
- https://www.youtube.com/watch?v=SZkrxWhI5qM&list=PLJOzdkh8T5krxc4HsHbB8g8f0hu7973fK&index=2
- https://www.youtube.com/watch?v=BPcicsBuRdc&list=PL-_cKNuVAYAWXoVzVEDCT-usTEBHUf4AF&index=1&t=0s

### Общие рекомендации
- ods.ai - сообoество. объединяющее всех исследователей, инженеров и разработчиков в области Data Science  и смежных областях (45к участников)
- Участвовать в разнообразных соревнованиях: kaggle, drivendata, boosters
- Участвовать в хакатонах.

#### Полезные ссылки, которые я нахожу по мере изучения:
- http://matrixmultiplication.xyz/ - визуализация сложения матриц
- https://www.stratascratch.com/
- https://www.javatpoint.com/
- https://habr.com/ru/articles/708752/ - Математика для DS и ML за 8 месяцев. Подробный план обучения

### English Language
Как говорится, английский язык и есть язык программирования, так как на нем информации значительно больше и она полезнее.

#### Статьи по теме
- https://tefl-tesol-certificate.com/blog/plan-samostoyatelnogo-izucheniya-anglijskogo-yazyka
- https://tefl-tesol-certificate.com/blog/izuchenie-anglijskogo-s-nulya-dlya-vzroslyh-nevozmozhno-mif-ili-realnost

##### Elementary - А1
Когда вы получили небольшую порцию первичных знаний и имеете небольшое представление о грамматических правилах английского языка, 
самое время двигаться дальше. На данном этапе, который в классификации уровней CEFR обозначен как A1, вы познакомитесь с лексикой 
и грамматикой необходимыми для поддержания диалога на повседневную тему: о погоде, животных, планах, работе, одежде, доме и праздниках.

- Вам потребуется около 200 часов для того, чтобы обрести базовый словарный запас и научиться им пользоваться.
- Основной учебник: New English File 3rd edition. В нем собраны основные темы и лексика, с которой вам предстоит работать.
- Научиться отличать настоящее от будущего пользуясь специальными вспомогательными глаголами.
- YouTube канал для тренировки аудирования и чтения. https://www.youtube.com/@lotsofenglishtexts8195
- Включайте уже знакомые озвученные тексты и старайтесь записывать услышанное. Например с канал из предыдущего пункта.

##### Pre-Intermediate - А2
Уровень A2 подразумевает повторение пройденного, но с добавлением языковых нюансов. Поэтому так важно заполнить пробелы, которые будут 
всплывать во время изучения. И если вам покажется, что вы проходите одни и те же темы, не сомневайтесь, это необходимо для беглости языка. 
На данном этапе ваш словарный запас состоит из 1000-1500 слов, поэтому вам нетрудно рассказать о себе, своих предпочтениях, а также 
логично высказать свое мнение на привычные темы. Здесь добавляются новые грамматические правила и согласование времен, а также вводные 
слова и выражения для красоты речи. На этом уровне люди начинают смотреть сериалы и понимать песни на слух.

- Постоянно работайте над пополнением словарного запаса. Рекомендуем подписаться на любимых актеров и певцов в социальных сетях, чтобы ежедневно сталкиваться с чтением и новой лексикой. Особый акцент стоит поставить на аудирование. Сейчас вы привыкаете слушать неадаптированные рассказы.
- https://listenaminute.com/index.html - Сервис для прокачки навыка понимания на слух. Здесь собраны задания по типу: вставить пропущенные слова, расположить их в правильном порядке, составить слова из букв. То есть все, что необходимо, чтобы лучше понимать уже знакомые темы без субтитров.
- https://lingoclip.com/?ref=https%3A%2F%2Flyricstraining.com%2Fplay%2Fred-hot-chili-peppers%2Fblack-summer%2FHYNA9pBCaY - это приложение добавит веселья и музыки в ваши задания по listening. Вы сможете понимать песни на слух параллельно работая над словарным запасом.
- https://tefl-tesol-certificate.com/blog/uroven-anglijskogo-a2-pre-intermediate-predporogovyj - Статья о необходимых знаниях на уровне A2.

##### Intermediate - B1
Уровень знания B1 предполагает просмотр фильмов и чтение книг на английском. Адаптированные тексты и рассказы остались в прошлом. 
Теперь предстоит получать настоящее удовольствие от процесса обучения. В план по изучению английского на среднем уровне рекомендуется включить:
- Прочтение в оригинале "How to win friends and influence people" by Dale Carnegie.
- Полезной практикой станет посещение разговорных клубов, где у вас будет возможность улучшить навыки говорения. Основная задача - уделить внимание speaking.
- Важно погрузиться в языковую среду, чтобы по максимуму обеспечить себе различный контекст. И если нет возможности ехать за границу, то можно найти друга по переписке из другой страны и устраивать еженедельные созвоны, чтобы поддерживать разговорную практику.
- Обязательно расширяйте словарный запас с помощью крылатых выражений и фразовых глаголов. Лучшим решением будет ежедневный listening. Слушайте и смотрите интервью с любимыми celebrities, повторяйте интересные выражения за ними. Чтобы лучше понимать к чему вы в итоге придете, ознакомьтесь с нашей статьей на эту тему. https://tefl-tesol-certificate.com/blog/all-about-b1-intermediate

##### Upper-Intermediate - B2

##### Advanced - C1

##### Proficiency - C2



