# Repository of educational projects

Здесь собраны учебные проекты по продуктовой и маркетинг-аналитике, выполенные мной и прошедшие ревью в курсе "Аналитик данных" Яндекс.Практикума

## Описание проектов

| Название проекта | Описание | Результаты | Используемые библиотеки | 
| :---------------------- | :---------------------- | :---------------------- | :---------------------- |
|[Проверка гипотез по увеличению выручки в интернет-магазине, оценка результатов A/B теста](https://github.com/altovivan/Analytics_project/tree/master/yandex_praktikum_projects/AB_test)|Данные были предоставленны одим крупным интернет-магазином. Они содержали информацию о выдвинутых гипотезах (охват, влияние, уверенность, ресуры) и данные с результатами проведенного А/В-теста.| Приоритезация гипотез дала понимание на какие из них стоит обратить внимание и взять в работу. Результатом анализа А/В-теста стала фиксация статистически значимого различия между группами по исследуемым параметрам в пользу тестовой группы, т.е. есть основания "раскатывать" тестируемые изменения.| *pandas*, *matplotlib.pyplot*, *datetime*, *numpy*, *skipy*, *skipy.stat*|
|[Анализ убытков приложения ProcrastinatePRO+](https://github.com/altovivan/Analytics_project/tree/master/yandex_praktikum_projects/Analysis_of_bussines_indicators)|Несмотря на огромные вложения в рекламу, последние несколько месяцев компания терпит убытки. Задача маркетингового аналитика — разобраться в причинах и помочь компании выйти в плюс. Для этого был проведен когортный анализ и анализ по таким метрикам как: LTV, CAC, Retention rate, DAU, WAU, MAU.| Исследуя полученные значения метрик были определены причины убыточности приложения и даны рекомендации отделу маркетинга с указанием убыточных и оптимальных каналов привлечения, а также проблемных регионов, для которых надо скорректировать рекламные бюджеты.|*pandas*, *seaborn*, *datetime*, *timedelta*, *matplotlib*, *numpy*, *statistics*|
|[Изучение закономерностей, определяющих успешность игр](https://github.com/altovivan/Analytics_project/tree/master/yandex_praktikum_projects/Analytics_for_game_dev)| Используя исторические данные о продажах компьютерных игр, оценки пользователей и экспертов, жанры и платформы, выявить закономерности, определяющие успешность игры. |Были определены параметры, делающие игру успешной (популярной, покупаемой и т.д.). Были составлены портреты пользователей по регионам и определены их предпочтения по жанрам, платформам. А также проанализированы рейтинги игр и их влияние на продажи по регионам и доли продаж по регионам. На основании анализа были даны рекомендации по подготовке и реализации рекламных компаний на следующий отчетный период.|*pandas*, *seaborn*, *datetime*, *timedelta*, *matplotlib.pyplot*, *numpy*, *skipy*|
|[Продажа квартир в Санкт-Петербурге — анализ рынка недвижимости](https://github.com/altovivan/Analytics_project/tree/master/yandex_praktikum_projects/Realty_SPB)| 
Используя данные сервиса Яндекс.Недвижимость, определить рыночную стоимость объектов недвижимости и типичные параметры квартир. | Была определена рыночная стоимость объектов недвижимости разного типа, типичные параметры квартир, в зависимости от удаленности от центра. Выявленны параметры и корреляция между ними и стоимостью объекта недвижимости. Полученные результаты переданы заказчику и могут быть использованы для построения автоматизированной системы, с помощью которой, можно отслеживать различного рода аномалии и мошенническую деятельность в объявлениях по недвижимости.|*pandas*, *seaborn*, *datetime*, *random*, *requests*, *urllib*, *json*, *geopy*.|
