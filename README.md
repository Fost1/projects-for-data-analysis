# Data analyst

## Описание:
В данном репозитории представлены проекты курса [Аналитик данных](https://practicum.yandex.ru/data-analyst/) (Яндекс.Практикум).

## Основные инструменты и навыки, полученные при обучении:
- Языки: Python, SQL
- Анализ данных: библиотеки Pandas, NumPy, SciPy, Statsmodels
- Визуализация: Matplotlib, Plotly, Seaborn
- Построение дашбордов: Tableau
- Метрики юнит-экономики, когортный анализ
- Работа с гипотезами
- А/В-тестирование

## Проекты:
| №| Название и ссылка | Навыки и инструменты| Задачи проекта  |Описание проекта| 
|-----------|-------------------|------------------------------------------------------------------|-----------------------------------|------------------------------------------------------------------------------|
|1.|[Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов](1 Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов/)|Pandas,Python|На реальных данных Яндекс.Музыки c помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга.|Сравнение Москвы и Петербурга окружено мифами: - Москва — мегаполис, подчинённый жёсткому ритму рабочей недели; - Петербург — город своеобразной культуры, непохожий на Москву. Некоторые мифы отражают действительность. Другие — пустые стереотипы. Бизнес должен отличать первые от вторых, чтобы принимать рациональные решения. На реальных данных Яндекс.Музыки вы проверите данные и сравните поведение пользователей двух столиц.|
|2.|[Исследование надёжности заёмщиков — анализ банковских данных](2 Исследование надёжности заёмщиков — анализ банковских данных/)|Pandas,Python,предобработка данных|На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок|На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три.|
|3.|[Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](3 Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости/)|Matplotlib,Pandas,Python,визуализация данных,исследовательский анализ данных,предобработка данных|Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир|На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания.|
|4.|[Определение выгодного тарифа для телеком компании](4 Определение выгодного тарифа для телеком компании/)|Matplotlib,NumPy,Pandas,Python,SciPy,описательная статистика,проверка статистических гипотез|На основе данных клиентов оператора сотовой связи проанализировать поведение клиентов и поиск оптимального тарифа|Проведен предварительный анализ использования тарифов на выборке клиентов, проанализировано поведение клиентов при использовании услуг оператора и рекомендованы оптимальные наборы услуг для пользователей. Проведена предобработка данных, их анализ. Проверены гипотезы о различии выручки абонентов разных тарифов и различии выручки абонентов из Москвы и других регионов.|
|5.|[Изучение закономерностей, определяющих успешность игр](5 Изучение закономерностей, определяющих успешность игр/)|Matplotlib,NumPy,Pandas,Python,исследовательский анализ данных,описательная статистика,предобработка данных,проверка статистических гипотез|Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры|Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок.|
|6.|[Исследование данных об инвестиции венчурных фондов в компании-стартапы](6 Базовый sql/)|SQL,PostgreSQL|Произвести различные выгрузки данных венчурных фондов с помощью SQL|Проект автоматически проверяется в тренажёре SQL. В самостоятельном проекте этого курса работа идёт с базой данных, которая хранит информацию о венчурных фондах и инвестициях в компании-стартапы. Эта база данных основана на датасете Startup Investments, опубликованном на популярной платформе для соревнований по исследованию данных Kaggle.|
|7.|[Анализ убытков приложения ProcrastinatePRO+](7 Анализ убытков приложения ProcrastinatePRO+/)|Matplotlib,Pandas,Python,Seaborn,когортный анализ,продуктовые метрики,юнит-экономика|Задача для маркетингового аналитика развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Ваша задача — разобраться в причинах и помочь компании выйти в плюс.|Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным.|
|8.|[Анализ сервиса вопросов и ответов о программировании](8 Продвинутый SQL/)|SQL,PostgreSQL|Произвести различные описательные и аналитические выгрузки данных с помощью SQL|С помощью Python и SQL подключаемся к базе данных, считаем и визуализируем ключевые метрики сервис-системы вопросов и ответов о программировании.|
|9.|[Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста](9 Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты AB теста/)|A/B-тестирование,Matplotlib,Pandas,Python,SciPy,проверка статистических гипотез|Используя данные интернет-магазина приоритезировать гипотезы, произвести оценку результатов A/B-тестирования различными методами|Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста.|
|10.|[Анализ пользовательского поведения в мобильном приложении](10 А А В тест - Анализ пользовательского поведения в мобильном приложении/)|A/B-тестирование,Matplotlib,Pandas,Plotly,Python,Seaborn,визуализация данных,проверка статистических гипотез,продуктовые метрики,событийная аналитика|На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования|В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой Выявлено, что новый шрифт значительно не повлияет на поведение пользователей.|
|11.|[Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](11 Исследования рынка общепита в Москве для принятия решения об открытии нового заведения/)|Pandas,Plotly,Python,Seaborn,визуализация данных|Исследование рынка общественного питания на основе открытых данных, подготовка презентации для инвесторов|Мною был исследован вопрос - будет ли успешным и популярным на долгое время кафе, в котором гостей обслуживают роботы-официанты. По результатам анализа подготовлена презентация для инвесторов с рекомендациями. В построении графиков я использовали библиотеки seaborn и plotly.|
|12.|[Дашборд для Яндекс.Дзена](https://public.tableau.com/views/dash_visits_16757012352930/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link) и [Презентация](https://drive.google.com/file/d/14qGXANUQN4ja_Qxt4_FdBmMjM-eMfRfx/view?usp=share_link)|PostgreSQL,Python,SQLAlchemy,Tableau,dash,построение дашбордов,продуктовые метрики|Используя данные Яндекс.Дзена построить дашборд с метриками взаимодействия пользователей с карточками статей|Работу над этим проектом я провел на удаленной машине в сервисе Yandex.Cloud. Мной был установлен PostgreSQL, развернута база данных. Затем я написал скрипт пайплайна, который позволил собирать данные за определенный временной период, и настроил его автономную работу через crontab. Для визуализации собранных данных я написал скрипт дашборда с несколькими фильтрами и также запустил его на удаленной машине. По результатам была подготовлена презентация с полученными графиками.|
|13.|[Выпускной проект](13 Выпускной проект/)|SQL PostgreSQL Python Pandas Scikit-learn Matplotlib Seaborn машинное обучение классификация кластеризация Tableau продуктовые метрики построение дашбордов A/B-тестирование проверка статистических гипотез|3 задачи: 1.Банки сегметация пользователей по потреблению и оттоку плюс создание презентации и дашборда 2.Оценка результатов A B-теста 3.SQL анализ сервиса для чтения книг по подписке|Анализируем заемщиков банка (результат оформляем в виде Презентации), проверяем результаты А/B тестирования и подтверждаем гипотезы, разрабатываем дашборд в Tableau Public. изучаем мобильное приложение посредством SQL-запросов.|
