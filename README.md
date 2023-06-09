# Список проектов

## Аналитика данных в игровой индустрии

### Описание проекта:

    Перед нами исторические данные до 2016 о продажах игр,оценках пользователей и экспертов, информация о жанрах и платформах. Мы планируем кампанию на 2017 и перед нами стоит основная задача выработать принцип работы с такими данными, чтобы впоследствии прогнозировать продажи на любой выбранный нами год.
  
### Цель проекта:

    1. Выявить какие факторы определяют потенциально популярный продукт на рынке игровой индустрии в целом и в каждом из исследуемых регионов по отдельности;
    2. Сформировать прогноз на 2017 год на основании этих параметров.

   ### Результаты проекта:
   

   - Активная фаза развития платформы длится около 3-4 лет, после чего неминуемо идёт спад в популярности, поэтому для прогноза на 2017 год мы выбрали данные за 2012-2016 года. Именно платформы, появившиеся в это время будут иметь пик популярности в 2017 году, соответственно производители игр, предполагая это, будут выпускать игры преимущественно для этих платформ;
   - Оценки пользователей практически не оказывают никакого влияния на объемы продаж игр;
   - Оценки критиков имеют слабое влияние на продажи игр;
   - Для создания качественного прогноза нам нужно исследовать предпочтения в жанрах в рамках конкретного региона, от этого будет зависеть выбор и платформы для игр. В особенности это касается региона Япония, где топ-5 игр, а соответственно и топ-5 популярных платформ достаточно сильно отличается от остального мира;
   - При создании датасета было потеряно достаточно существенное количество данных по причине того, что формат оценки игр в разных регионах может отличаться. Чтобы получить более полную картину нужно соотносить системы оценки разных рейтинговых ассоциаций и приводить к некой единой градации оценок в рамках одного датасета. То же касается и оценок пользователей и критиков, можно предположить, что в рамках отдельного региона использовалась другая система оценки из-за чего мы и потеряли данные об этом;
   - Мы подтвердили гипотезу о том, что средние пользовательские оценки платформ PC и Xbox One равны с вероятностью в 55%;
   - Гипотеза о различии в пользовательских оценках жанров Sports и Action также была подтверждена, с вероятностью получить равные средние значения на генеральных выборках равной нулю;
   - Потенциально популярным продуктом в 2017 году во всех странах за исключением Японии предположительно будут игры в жанре Action и Shooter и в меньшей степени Sports, Role-Playing, Racing и Misc. Для Японии список популярных жанров игр уверенно возглавляет Role-Playing и Action. В меньшей востребованы жанры Misc, Simulation и Fighting;
   - Что касается выбора платформ, то в первую очередь стоит обратить внимание на PS4 и Xbox One. На графике распределения количества выпускаемых игр по годам мы наблюдали заметный рост в популярности. Однако не стоит принебрегать и играми на платформе PC, которая достаточно уверенно держится уже более 10 лет на рынке игровой индустрии и, хоть ее популярность и значительно снизилась, но всё же есть ярые противники консолей предпочитающие PC любой другой платформе;
   - При выборе потенциально популярной платформы также стоит обратить внимание на особенности формирования спроса в конкретном регионе. С большой вероятностью можно утверждать, что в Японии из трех самых востребованных платформ(PS4, Xbox One и PC) вероятнее всего отдадут предпочтение PS4. В Северной Америке мнения разделятся между Xbox One и PS4 в пользу Xbox One. В Европе и остальном мире отдадут предпочтение преимущественно PS4, но будут также и желающие купить игры для Xbox One.
    
   ### Статус проекта:

      Завершен
      
   ### Используемые инструменты и техники:
   
      -

---

## Исследование надежности заемщиков

### Описание проекта: 

   Перед нами статистика о платёжеспособности клиентов. Результаты данного исследования можно использовать при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.
  
### Цель проекта:

   1. Выяснить как влияет количество детей клиента на факт погашения кредита в срок;
   2. Установить влияет ли пол клиента на факт погашения кредита в срок;
   3. Установить три самые популярные цели кредитов среди клиентов старше 30 лет.

### Результаты проекта:

- Самыми надежными заемщиками являются клиенты не имеющие детей. С увеличением количества детей возрастает вероятность невозврата кредита в срок;
- Рассматривая группы разбитые по семейному статусу, можно прийти к выводу о том, что самыми надежными плательщиками являются клиенты категории "вдовец / вдова";
- Менее надежными, но тем не менее с относительно небольшим процентом невозврата в срок являются категории "В разводе" и "Женат / Замужем";
- Чаще остальных просрочили выплату по кредиту заемщики состоящие в гражданском браке и клиенты категории "Не женат / не замужем";
- Если рассматривать заемщиков, разбивая их на группы по ежемесячному доходу,то можно прийти к выводу, что самыми ненадежными клиентами являются те, чей доход не превышает 30 тыс.рублей, а также те, чей доход составляет от 50 до 200 тыс.руб;
- Наименьший процент невыплаты в срок имеют клиенты с уровнем дохода от 30 до 50 тыс.руб;
- На втором и третьем местах по надежности идут заемщики с доходом от 200 тыс.руб. до 1 млн.руб и с доходом более 1 млн.рублей;
- Клиенты берущие кредит на операции с недвижимостью и проведение свадьбы чаще всего выплачивают кредит в срок;
- Самыми ненадежными заемщиками оказались те, которые взяли кредиты на получение образования и операции с автомобилем.

### Статус проекта:

      Завершен
      
### Используемые инструменты и техники:

      -


