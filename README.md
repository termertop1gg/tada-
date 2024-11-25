#ВВЕДЕНИЕ	

В условиях современного рынка розничная торговля требует высокой эффективности управления процессами купли-продажи. Обувной магазин, имеющий филиалы в городе Иркутске, сталкивается с необходимостью оперативного учета товаров, поставок, продаж и сотрудников. Для этого требуется автоматизированная система хранения и обработки информации, способная обеспечить точный анализ продаж, управление ассортиментом и поддержку взаимодействия между различными подразделениями компании. Таким образом, создание специализированной базы данных является актуальным шагом для оптимизации бизнес-процессов и улучшения конкурентоспособности предприятия.
Объект исследования является информационная система «Обувной магазин».
Предмет: 1С:Предприятие 8.
Целью курсового проекта является разработка и внедрение базы данных «Обувной магазин» для обувного магазина, предназначенной для повышения оперативности и качества процесса отслеживания купленных и проданных товаров, а также для обеспечения удобного доступа к данным о товарах, поставщиках, продажах и сотрудниках.
Из цели вытекают следующие задачи:	
1 Провести анализ требований к системе управления данными обувного магазина;
2 Разработать концептуальную модель базы данных, отражающую структуру данных и взаимосвязь между ними.
3 Создать логическую модель базы данных с учетом всех функциональных требований;
4 Реализовать физическую модель базы данных в выбранной СУБД;
5 Разработать конфигурацию в учебной версии 1С:Предприятие 8.3;
6 Разработать интерфейс для пользователей системы (продавцов и финансового отдела);
7 Заполнить информационную систему данными;
8 Провести тестирование разработанной базы данных на предмет корректности функционирования и соответствия требованиям;
9 Подготовить документацию по эксплуатации и сопровождению разработанной системы;
Проект представляет собой новый подход к автоматизации процессов управления данными в обувном магазине, основанный на современных технологиях баз данных. Практическая значимость заключается в том, что созданная база данных позволит значительно улучшить контроль над запасами товаров, ускорить процессы анализа продаж и повысить эффективность работы персонала. Кроме того, использование автоматизированной системы сократит временные затраты на рутинные операции и минимизирует вероятность ошибок, связанных с человеческим фактором.
Практическая значимость информационной системы имеет большое значение, так как позволит повысить эффективность работы персонала, оптимизировать ведение документации, а также улучшить качество обслуживания клиентов. 
#1Теоретическая часть
##1.1Описание «1С:Предприятие»
«1С:Предприятие» – это универсальная платформа для автоматизации различных бизнес-процессов предприятий. Она представляет собой комплекс программных решений, разработанных компанией «1С», который позволяет автоматизировать учет, управление и анализ деятельности компании. Прикладные решения «1С» называются конфигурациями и интегрируются во все деловые процессы организаций вне зависимости от их масштаба и структуры. Система охватывает широкий спектр задач, включая бухгалтерский и налоговый учет, документооборот, управление персоналом, логистику, производство и многое другое.
Основные возможности платформы:
1)_Бухгалтерский и налоговый учёт: ведение учета всех финансовых операций, расчет налогов, формирование отчетности для государственных органов;_
2)_Управление производством: планирование производственных процессов, контроль запасов сырья и материалов, управление заказами и поставками;_
3)_Документооборот: автоматизация работы с документами, создание шаблонов документов, контроль их исполнения;_
4)_Складской учет: управление запасами товаров, контроль остатков, оптимизация складских операций;_
5)_CRM-система: управление взаимоотношениями с клиентами, отслеживание продаж, анализ клиентской базы;_
6)_Финансовое планирование и бюджетирование: составление бюджетов, прогнозирование доходов и расходов, анализ финансовой устойчивости компании;_
7)_Анализ и отчетность: генерация аналитических отчетов, мониторинг ключевых показателей эффективности бизнеса;_
8)_Интеграция с другими системами: возможность интеграции с различными внешними сервисами и приложениями через API;_
Конфигурируемость – главная отличительная черта и одновременно основное преимущество платформы. Благодаря гибкости разработчик может изменять прикладные решения, дополнять их и создавать новые версии под нужды компании. Все это осуществляется на базе единой платформы, которая не меняется вне зависимости от того, что происходит с конфигурациями внутри нее.
Преимущества использования «1С:Предприятия»:
-гибкость и масштабируемость: система легко адаптируется под нужды конкретного бизнеса, независимо от его размера и отрасли;
-простота внедрения и обучения: интуитивный интерфейс и наличие обучающих материалов делают систему доступной даже для пользователей без специальных технических знаний;
-широкая экосистема партнеров: большое количество сертифицированных специалистов и компаний-партнеров, готовых оказать поддержку при внедрении и эксплуатации системы.
Полная настраиваемость процессов в зависимости от направления бизнеса. Большой выбор подсистем, которые позволяют ускорить и стандартизировать работу системных администраторов и программистов. Каждое прикладное решение можно масштабировать в соответствии с рабочими задачами. Платформа позволяет вести отчетность в единой базе для нескольких организаций сразу [2].
В целом, «1С:Предприятие» является мощным инструментом для управления бизнесом, который помогает повысить эффективность работы компании, снизить затраты и улучшить качество принимаемых управленческих решений.
##1.2Общие требования к информационной системе
Информационная система (ИС) на базе платформы «1С:Предприятие» для обувного магазина должна соответствовать ряду требований, чтобы эффективно поддерживать все аспекты работы торговой точки. Вот основные из них:
1)_Управление товарными остатками:_
Требования: возможность ведения точного учета наличия обуви на складе; автоматическое обновление данных о наличии товара после каждой продажи;
2)_Управление закупками:_
Требования: ведение истории закупок, с указанием поставщиков, цен, сроков поставки и других параметров; формирование заказов поставщикам на основе анализа текущих остатков и прогнозируемых потребностей; контроль за выполнением условий договоров с поставщиками, включая сроки поставок и оплату;
3)_Финансовый учет:_
Требования: автоматический расчет прибыли и убытков на основании данных о продажах и затратах;
4)_Аналитика и отчетность:_
Требования: создание разнообразных отчетов по различным аспектам работы магазина; возможность анализа динамики продаж, популярности отдельных моделей обуви, сезонных колебаний спроса; прогнозирование будущих продаж на основе исторических данных;
5)_Безопасность и резервное копирование:_
Требования: ограничение прав доступа сотрудников к разным функциям системы в зависимости от их ролей и обязанностей;
##1.3Этапы проектирования автоматизированной информационной системы
	Проектирование автоматизированной информационной системы (АИС) для обувного магазина включает в себя несколько этапов, начиная от сбора требований до внедрения и тестирования системы. Вот подробное описание этих этапов.
		__Этап 1: Анализ требований. Цель – определить потребности бизнеса и функциональные требования к системе.__
			1)Сбор информации: провести интервью с ключевыми пользователями (продавцами, финансовым отделом), чтобы понять их текущие процессы и ожидания от новой системы;
			2)Анализ бизнес-процессов: изучить существующие процессы в магазине, такие как учет товаров, управление продажами, работа с поставщиками и сотрудниками;
			3)Определение функциональных требований: описать функции, которые должны выполнять система, включая учет товаров, анализ продаж, работу с поставщиками, сотрудников и др;
		__Этап 2: Проектирование. Цель – разработать архитектуру системы и создать необходимые модели.__
			1)Диаграмма вариантов использования (Use Case Diagram):
				-определяет взаимодействия между системой и её пользователями;
				-показывает сценарии использования системы, такие как добавление нового товара, оформление покупки, просмотр истории продаж и др.
			2)ERD-диаграмма (Entity Relationship Diagram): 
				-модель данных, показывающая связи между сущностями (таблицами) в базе данных;
				-отражает структуру базы данных, включая таблицы, поля и отношения между ними.
			3)Инфологическая модель (диаграмма Чена):
				-представляет концептуальную модель данных, отражающую сущность, атрибуты и взаимосвязи между объектами реального мира;
				-используется для описания логической структуры данных без привязки к конкретной реализации.
			4)Диаграмма деятельности (Activity Diagram): 
				-описывает последовательность действий и решений, выполняемых системой;
				-помогает визуализировать бизнес-процессы внутри магазина.
			5)Концепция пользовательского интерфейса:
				-определение основных экранов и функций, необходимых для разных типов пользователей.
		__Этап 3: Реализация. Цель – создание и настройка программного обеспечения согласно разработанным моделям.__
			-создание базы данных: реализация физической модели базы данных в выбранной СУБД;
			-разработка функционала: написание кода для выполнения всех требуемых операций, таких как добавление новых товаров, обработка продаж, создание отчетности и др.
		__Этап 4: Тестирование. Цель – выявление возможных ошибок:__
			-модульное тестирование: проверка отдельных компонентов системы на соответствие требованиям;
			-интеграционное тестирование: проверка взаимодействия различных модулей системы друг с другом;
			-функциональное тестирование: проверка выполнения всех заявленных функций системы;
			-тестирование безопасности: проверка защиты системы от несанкционированного доступа и утечек данных.
##1.4Организационная структура объекта автоматизации
	__Организационная структура обувного магазина включает следующие элементы:__
		1)Администрация:
			-директор/управляющий магазином;
			-бухгалтерия;
		2)Отдел продаж:
			-менеджеры по работе с клиентами;
			-продавцы-консультанты;
		3)	Складской отдел:
			-Заведующий складом;
			-Кладовщики;
		4)	Поставщики:
			-Поставщики брендовой обуви;
		5)	Покупатели:
			-Физические лица;
		6)	Информационные системы:
			-База данных «Розничная торговля»;
			-Программное обеспечение для управления продажами и складскими запасами;
		7)	Пользователи информационной системы:
			-Администраторы (директор, главный бухгалтер);
			-Финансовые специалисты (бухгалтера);
###1.4.1Характеристика предметной области
	__Предметная область данного проекта охватывает процессы, связанные с управлением розничными продажами обуви в двух филиалах обувного магазина в городе Иркутске. В рамках этой предметной области необходимо автоматизировать следующие аспекты:__
		1)	Управление ассортиментом товаров:
			-Информация о каждом товаре;
			-Категоризация товаров;
		2)	Работа с поставщиками:
			-Данные о поставщиках;
			-История поставок;
		3)	Процесс поставок:
			-Регистрация поставок;
			-Анализ поставок по различным критериям;
		4)	Процесс продаж:
			-Регистрация продаж;
			-Анализ продаж по различным критериям;
		5)	Управление персоналом:
			-Персонал магазина;
		6)	Отчеты и аналитика:
			-Формирование отчетности по продажам, по поставкам, остаткам товаров на складе;
###1.4.2Описание входных и выходных данных
	__Выходные данные:__
		-Отчёты по продажам:
		-Общий объем продаж за период.
		-Объем поставок за период
		-Объем продаж по каждому продавцу.
		-Остатки товаров на складах.
	Разрабатываемая система содержит в себе данные о товарах, поставщиках, поставках, продажах, персонале, а также формирует отчеты по продажам, поставкам и остаткам товаров на складе.
##1.5	Функциональная структура объекта автоматизации
	В процессе предпроектного обследования и анализа материалов обследования изучается функциональная структура объекта автоматизации – состав обеспечивающих и функциональных подсистем, состоящих из комплексов задач, отдельных задач и процедур управления. Задачи и их комплексы функционально и информационно взаимосвязаны друг с другом. Решение задач организуется на системных принципах в составе АИС с единым информационным, математическим, программным н другими видами обеспечения [5].
		1)_Управление товарами:_
			-Хранение информации о товарах: код товара, наименование, количество, цена, код поставщика;
			-Обновление остатков товаров после каждой продажи;
		2)_Работа с поставщиками:_
			-Ведение списка поставщиков: код поставщика, название, адрес, контактные данные;
			-Управление поставками: учет поступлений товаров от разных поставщиков;
			-Анализ поставок: сколько товаров было получено от каждого поставщика, какие поставки ожидаются;
		3)_Учет продаж:_
			-Регистрация продаж: код продажи, код товара, дата продажи, количество проданных единиц, розничная цена, сотрудник-продавец;
			-Формирование отчетов по продажам: анализ выручки, популярных товаров, наиболее активных продавцов;
			-Учет возвратов и обменов товаров;
		4)_Анализ продаж:_
			-Подсистема аналитики: создание различных отчетов (ежедневных, ежемесячных, годовых), позволяющих оценить динамику продаж, популярность отдельных товаров, эффективность работы сотрудников;
			-Прогнозирование спроса на основе исторических данных;
		5)_Администрирование сотрудников:_
			-Информация о сотрудниках: код сотрудника, ФИО, должность, СКС;
			-Назначение прав доступа сотрудникам (например, доступ к данным о продажах или поставщиках);
			-Отчеты по эффективности работы сотрудников;
		6)_Безопасность и права доступа:_
			-Настройка уровней доступа для пользователей системы (продавцов, менеджеров, администраторов);
			-Логирование действий пользователей для обеспечения безопасности и контроля;
			-Каждая функциональная подсистема взаимосвязана друг с другом и выполняет определенные задачи для обеспечения эффективной автоматизации бизнес-процессов в обувном магазине.
	__Диаграммы и модели__
		1)Диаграмма вариантов использования;
		2)Диаграмма последовательности;
		3)Диаграмма деятельности организации;
		4)Инфологическая модель (диаграмма Чена);
		5)ERD-диаграмма физической модели БД;
		6)Диаграмма IDEF0;
		7)Диаграмма IDEF1X;
	__Конфигурация в 1С__
		1)_Конфигурация 1C:_
			-Создание базы данных и интерфейсов для работы с данными в системе 1C;
		2)_Отчетность:_
			-Разработка отчетности, включающей отчеты по продажам, по поставкам, остаткам товаров;
		3)_Персональные интерфейсы для разных типов пользователей:_
			-Интерфейсы для продавцов, бухгалтеров и администраторов, каждый со своим набором функций и прав доступа;	
	__Детализация функциональных модулей:__
		1)_Модуль управления товарами:_
			-Добавление/редактирование информации о товаре ;
			-Учет остатков товаров;
		2)_Модуль работы с поставщиками:_
			-Ведение списка поставщиков;
			-История поставок;
		3)_Модуль продаж:_
			-Регистрация продаж ;
			-История продаж;
			-Аналитика продаж;
		4)_Модуль сотрудников:_
			-Учет персонала;
			-Назначение ролей и доступов;
			-Контроль за выполнением задач сотрудниками;
		5)_Административные функции:_
			-Настройка прав доступа;
			-Резервное копирование данных;
			-Мониторинг производительности системы;
		6)_Отчеты и аналитические инструменты:_
			-Генерация отчетов по продажам;
			-Сравнение объемов продаж по филиалам;
			-Прогнозирование спроса на основе исторических данных;
	__Пользовательские интерфейсы:__
			-Интерфейс продавца: регистрация продаж, просмотр остатков, поиск товаров по характеристикам;
			-Бухгалтера: формирование финансовых отчетов, управление платежами, контроль за доходностью;
			-Администратора: настройка системы, управление пользователями, мониторинг безопасности;
