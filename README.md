# Привет, я начиающий специалист в Анализе данных
В поисках компании с большим аналитическим отделом, работа в котором позволит мне применить получнные знания.
Год изучаю Python и SQL, научился строить Dash-борды в Tableau. 

Данные проекты выполнялись в рамках обучения в Яндекс.Практикуме по направлению "Аналитик данных". Поскольку это учебные проекты, то задания в первую очередь были направлены на выявление знаний и умений. Так что какие-то части кода могут показаться избыточными или не имеющими прямого отношения к целям исследования. Если проекты не открываются на github, можно их открыть с помощью https://nbviewer.jupyter.org

01. **Cравнение пользователей двух городов**  
   *Задача*: С помощью библиотеки Pandas и её возможностей проверить данные и сравнить поведение и предпочтения пользователей двух столиц — Москвы и Санкт-Петербурга.  
   *Инструменты*: Python в Jupyter Notebook, библиотека pandas.
   *Выводы*: В ходе исследования было усановленно:
   День недели по-разному влияет на активность пользователей в Москве и Петербурге.
Музыкальные предпочтения не сильно меняются в течение недели — будь то Москва или Петербург. Небольшие различия заметны в начале недели, по понедельникам:Таким образом, вторая гипотеза подтвердилась лишь отчасти. Этот результат мог оказаться иным, если бы не пропуски в данных.
Во вкусах пользователей Москвы и Петербурга больше общего, чем различий. Вопреки ожиданиям, предпочтения жанров в Петербурге напоминают московские.Третья гипотеза не подтвердилась. Если различия в предпочтениях и существуют, на основной массе пользователей они незаметны.

02. **Исследование надёжности заёмщиков**  
   *Задача*: На основе статистики о платёжеспособности клиентов исследовать влияет ли семейное положение и количество детей клиента на факт возврата кредита в срок
   *Инструменты*: Python в Jupyter Notebook, библиотека pandas.
   *Выводы*: Опираясь на данные были выявлены зависимости надежности заемщиков разных групп и категорий. На основании исследования можно заключить что статистика возвратов кредита в срок не имеет линейной зависимости ни у одной из категорий, тем не менее некоторые из групп можно назвать более надежными и предпочтительными для кредитования.
Лучшая статистика возвратов в срок у бездетных заемщиков. Так же надежными можно назвать овдовевших и разведенных. Предпочтительными целями для выдачи кредита следует считать кредиты на недвижимость и кредиты взятые на свадьбу.
Наименее надежные заемщики чаще встречаются среди имеющих 2х и более детей и со статусом не женат/не замужем. Проблемы с возвратом в срок наблюдается среди автокредитов и кредитов на образование.

03. **Анализ рынка недвижимости**  
   *Задача*: Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир
   *Инструменты*: Python в Jupyter Notebook, библиотеки Matplotlib,Pandas.
   *Выводы*: В сухом остатке в большинстве случаев покупки жилья люди выбирают 1-2 комнатные квартиры в высотной новостройке по периметру города Санкт-Петребург, с средней стоимостью в 100 т.р. за кв.метр. и высотой потолков 2,75. Таким образом можно сделать вывод о том, что количество таких домов и соответственно предложений будет расти в след за ценой в отличии от цен на жильё расположенного по центру исторического района города в невысоких домах из старого фонда.

04. **Исследование поведения пользователей**  
   *Задача*: Проверить гипотезы сервиса аренды самокатов, чтобы помочь вырастить бизнес. 
   *Инструменты*: Python в Jupyter Notebook, библиотеки Matplotlib, NumPy, Pandas, Python, SciPy
   *Выводы*:Проведен предварительный анализ использования тарифов на выборке клиентов сервиса самокатов, проанализировано поведение клиентов при использовании услуг. Проведена предобработка данных, их анализ. Проверены статистические гипотезы на основе имеющихся данных.

05. **Изучение закономерностей, определяющих успешность игр.Сборный проект**  
   *Задача*: Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры
   *Инструменты*: Python в Jupyter Notebook, библиотеки Matplotlib, NumPy, Pandas
   *Выводы*:Выявлены параметры, определяющие успешность игры в разных регионах мира. На основании этого подготовлен отчет для магазина компьютерных игр для планирования рекламных кампаний. Проведена предобработка данных, анализ. Выбран актуальный период для анализа. Составлены портреты пользователей каждого региона. Проверены гипотезы: средние пользовательские рейтинги платформ Xbox One и PC одинаковые; средние пользовательские рейтинги жанров Action и Sports разные. При анализе использовал критерий Стьюдента для независимых выборок.

07. **Анализ бизнес показателей**  
   *Задача*:Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Моя задача как для маркетингового аналитика развлекательного приложения Procrastinate Pro+ — разобраться в причинах и помочь компании выйти в плюс.
   *Инструменты*: Python в Jupyter Notebook, библиотеки Matplotlib, Pandas, Seaborn
   *Выводы*: Больше всего платящих пользователей приносят каналы FaceBoom за ним TipTop. Доля платящих пользователей выше всего у FaceBoom и AdNonSense. На TipTop потратили половину от всех денег на маркетинг, на FaceBoom треть.При этом расходы на канал TipTop увеличивались с каждым месяцем. САС для TipTop составляет 2.8 а для FaceBoom 1.1 что сильно повлияло на общий ROI. Пользователи из каналов TipTop, FaceBoom, AdNonSense не окупаются к концу 2 недели, удержание пользователей у FaceBoom и AdNonSense самое низкое. . Именно по каналу TipTop и FaceBoom привлекались пользователи из США, т.к. цена за привлечение одного пользователя у них возрастает схожим образом.
Отделу маркетинга стоит обратить внимание на каналы YRabbit, MediaTornado, LeapBob в виду самой меньшей стоимости привлечения за одного клиента.Так же стоит обратить внимание на канал AdNonSence, его пользователи имеют высокий LTV а значит потенциально принесут большую прибыль Стоит найти каналы которые могут привлечь пользователей из Европейских стран а так же пользователей PC и Android из за высокого ROI.


09. **Принятие решений в бизнесе**  
   *Задача*:  Приоритизировать гипотезы, запустить A/B-тест и проанализировать результаты.
   *Инструменты*: Python в Jupyter Notebook, библиотеки Matplotlib, Pandas, SciPy.
   *Выводы*:Был проведен тест на корректность предоставленных данных (A/A тест) Выборка данных имеет корректный размер, проблему подглядывания в результате сравнения групп во время проведения теста мы исключаем. Было обнаружено 58 пользователей с некорректным разделением по группам
Посчитали статистическую значимость различий в среднем чеке заказа между группами по «очищенным» и "сырым" данным:
По сырым данным нет статистически значимого различия по среднему чеку между группами. после удаления аномалий статистически значимого различия не наблюдается.
Следовательно в группе В, количество заказов на посетителя увеличилось, а средний чек остался прежним. Это приведет к росту выручки кампании.Тест следует остановить и признать успешным.

10. **Анализ пользовательского поведения в мобильном приложении**  
   *Задача*: На основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования
   *Инструменты*: Python в Jupyter Notebook, библиотеки Matplotlib, Pandas, Plotly, Seaborn
   *Выводы*: В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой Выявлено, что новый шрифт значительно не повлияет на поведение пользователей.

11. **Исследования рынка общепита в Москве для принятия решения об открытии нового заведения**  
   *Задача*: Исследование рынка общественного питания на основе открытых данных, подготовка презентации.
   *Инструменты*: Python в Jupyter Notebook, библиотеки Pandas, numpy, seaborn, json, matplotlib,plotly,folium
   *Выводы*: Подготовлено исследование рынка на основе открытых данных о заведениях общественного питания Москвы, визуализированы полученные данные. На основе данных выбрано место для открытия новой кофейни


12. **Анализ оттока клиентов банка**  
   *Задача*: В «Метанпромбанк» провести анализ оттока клиентов и сегментирование пользователей банка. Сегментация покажет, как клиенты пользуются услугами банка.
   *Инструменты*: Python в Jupyter Notebook, библиотеки Pandas, numpy, seaborn, matplotlib, scipy, statsmodels, phik
   *Выводы*: Проведена декомпозиция исследования отточности клиентов банка «Метанпромбанк», общая отточность по банку равна 18,2% На основе EDA выделены значения признаков оказывающих наибольшее влияние на отток клиентов Методом проверки статистических гипотез было проверено что оценочный доход клиента влияет на отток Клиенты с более высоким баллом кредитного скоринга имеют меньшую вероятность оттока Клиенты с кредитной картой имеют меньшую вероятность оттока Выделены признаки отточных сегментов с отточностью минимум в два раза превышающей общую по банку
