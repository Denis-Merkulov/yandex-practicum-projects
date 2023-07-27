# Репозитарий выполненных проектов по программе "Аналитик данных"

Проекты были выполнены в ходе обучения в Яндекс.Практикуме, профессии "Аналитик данных"

| Название проекта | Описание | Используемые библиотеки |
| ---------------- | -------- | ----------------------- |
| [1. Исследование данных сервиса “Яндекс.Музыка” — сравнение пользователей двух городов](https://) | Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница) | `Python` `Pandas` |
| [2. Исследование надёжности заёмщиков — анализ банковских данных](https://) | Задача разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. На основе данных кредитного отдела банка исследовал влияние семейного положения и количества детей на факт погашения кредита в срок. Была получена информация о данных. Определены и обработаны пропуски. Заменены типы данных на соответствующие хранящимся данным. Удалены дубликаты. Категоризованы данные. Один датафрейм декомпозирован на три. |`предобработка данных` `Python` `Pandas` |
| [3. Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](https://) | На основе данных сервиса Яндекс.Недвижимость определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Проведена предобработка данных. Добавлены новые данные. Построены гистограммы, боксплоты, диаграммы рассеивания. |`Python` `Pandas` `Matplotlib` `исследовательский анализ данных` `визуализация данных` `предобработка данных`|
| [4. Исследование поведения пользователей сервиса аренды самокатов](https://) | Проведен предварительный анализ использования тарифов на выборке клиентов сервиса самокатов, проанализировано поведение клиентов при использовании услуг. Проведена предобработка данных, их анализ. Проверены статистические гипотезы на основе имеющихся данных. | `Python` `Pandas` `Matplotlib` `NumPy` `SciPy` `описательная статистика` `проверка статистических гипотез`|
| [5. Изучение закономерностей, определяющих успешность игр](https://) | Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок. |`Python` `Pandas` `NumPy` `Matplotlib` `предобработка данных` `исследовательский анализ данных` `описательная статистика` `проверка статистических гипотез`|
| [6. Исследование данных об инвестиции венчурных фондов в компании-стартапы](https://) | Проект автоматически проверяется в тренажёре SQL. В самостоятельном проекте этого курса работа идёт с базой данных, которая хранит информацию о венчурных фондах и инвестициях в компании-стартапы. Эта база данных основана на датасете Startup Investments, опубликованном на популярной платформе для соревнований по исследованию данных Kaggle. |`SQL` `PostgreSQL`|
| [7. Анализ убытков приложения ProcrastinatePRO+](https://) | Проведен анализ данных от ProcrastinatePRO+. Рассчитаны различные метрики, использован когортный анализ: LTV, CAC, Retention rate, DAU, WAU, MAU и т.д. Использованы уже написанные ранее функции расчёта метрик. Сделаны правильные выводы по полученным данным. |`Python` `Pandas` `Matplotlib` `когортный анализ` `юнит-экономика` `продуктовые метрики` `Seaborn`|
| [8. Анализ сервиса вопросов и ответов по программированию](https://) | Написаны все сложные SQL-запросы для подсчёта требуемых значений и метрик. | `SQL` `PostgreSQL` |
| [9. Проверка гипотез по увеличению выручки в интернет-магазине — оценить результаты A/B теста](https://) | Проведена приоритизация гипотез по фреймворкам ICE и RICE. Затем провел анализ результатов A/B-теста, построил графики кумулятивной выручки, среднего чека, конверсии по группам, а затем посчитал статистическую значимость различий конверсий и средних чеков по сырым и очищенным данным. На основании анализа мной было принято решение о нецелесообразности дальнейшего проведения теста. | `Python` `Pandas` `Matplotlib` `SciPy` `A/B-тестирование` `проверка статистических гипотез` |
| [10. Анализ пользовательского поведения в мобильном приложении](https://) | В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой Выявлено, что новый шрифт значительно не повлияет на поведение пользователей. | `A/B-тестирование` `Python` `Pandas` `Matplotlib` `Seaborn` `событийная аналитика` `продуктовые метрики` `Plotly` `проверка статистических гипотез` `визуализация данных` |
| [11. Исследования рынка общепита в Москве для принятия решения об открытии нового заведения](https://) | Подготовлено исследование рынка на основе открытых данных о заведениях общественного питания Москвы, визуализированы полученные данные. На основе данных выбрано место для открытия новой кофейни. В построении графиков я использованы библиотеки seaborn и plotly. | `Python` `Pandas` `Seaborn` `Plotly` `визуализация данных` |
| [12. Создание дашборда по пользовательским событиям для агрегатора новостей](https://) | Подготовлен интерактивный дашборд на основе данных о конференциях. Для создания дашбордов использован BI-инструмент Tableau. | `Tableau` `продуктовые метрики` `построение дашбордов` |
| [13. Выпускной проект](https://) | -- | `--` |


04. Определение выгодного тарифа для телеком компании	Вы аналитик компании «Мегалайн» — федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег	python pandas numpy matplotlib scipy seaborn
05. Изучение закономерностей, определяющих успешность игр	Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании	python pandas numpy matplotlib scipy seaborn datetime
06. Анализ бизнес-показателей приложения Procrastinate Pro+	Вы — маркетинговый аналитик развлекательного приложения Procrastinate Pro+. Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Ваша задача — разобраться в причинах и помочь компании выйти в плюс	python pandas numpy matplotlib scipy seaborn datetime продуктовые метрики
07. Проверка гипотез для увеличения выручки интернет-магазина. А:В тесты	Вы — аналитик крупного интернет-магазина. Вместе с отделом маркетинга вы подготовили список гипотез для увеличения выручки. Приоритизируйте гипотезы, запустите A/B-тест и проанализируйте результаты	python pandas numpy matplotlib scipy seaborn datetime warnings A/B тестирование
08. Анализ поведения пользователей в приложении по продаже продуктов питания	Получены данные о стартапе, который продаёт продукты питания. Нужно разобраться, как ведут себя пользователи мобильного приложения.	python pandas numpy matplotlib scipy seaborn plotly math
09. Анализ рынка общественного питания Москвы	Инвесторы из фонда «Shut Up and Take My Money» решили попробовать себя в новой области и открыть заведение общественного питания в Москве. Заказчики ещё не знают, что это будет за место: кафе, ресторан, пиццерия, паб или бар, — и какими будут расположение, меню и цены.	python pandas numpy matplotlib scipy seaborn plotly math re json Map, Choropleth
10. Анализ взаимодействия пользователей с карточками Яндекс.Дзен	Ответим на вопросы менеджеров, используя дашборд.	python pandas sqlalchemy matplotlib seaborn
11. Ритейл — Анализ программы лояльности	Финальный проект. После внедрения программы лояльности важно понять действительно ли она показывает ожидаемый рост среднего чека и количества продуктов в покупательской корзине. Результаты исследования будут говорить о результатах внедрения программы.	python pandas numpy seaborn matplotlib plotly.expres scipy
12. Проект по А:B-тестированию	Финальный проект. В распоряжении есть датасет с действиями пользователей, техническое задание и несколько вспомогательных датасетов.	python pandas numpy scipy matplotlib seaborn datetime plotly.express math
13. Проект по SQL	Финальный проект. Задача — проанализировать базу данных. В ней — информация о книгах, издательствах, авторах, а также пользовательские обзоры книг. Эти данные помогут сформулировать ценностное предложение для нового продукта.	python pandas sqlalchemy
