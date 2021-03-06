# YaPP11

## Churn probability forecast for fitness center

## ПРОГНОЗИРОВАНИЕ ВЕРОЯТНОСТИ ОТТОКА ПОЛЬЗОВАТЕЛЕЙ ДЛЯ ФИТНЕС - ЦЕНТРОВ

**Задача:** на основании предоставленных данных:

* составить ПРОГНОЗ вероятности оттока (на уровне следующего месяца) для каждого клиента
* сформировать типичные ПОРТРЕТЫ клиентов: выделить несколько наиболее ярких групп и охарактеризовать их основные свойства
* проанализировать основные ПРИЗНАКИ, наиболее сильно влияющие на отток
* сформулировать основные ВЫВОДЫ и разработать РЕКОМЕНДАЦИИ по повышению качества работы с клиентами:
>
> выделить целевые группы клиентов
> 
> предложить меры по снижению оттока
> 
> определить другие особенности взаимодействия с клиентами

Предобработка данных, исследовательский анализ данных, визуализация данных, классификация, кластеризация, машинное обучение

**Язык:** Python

**Библиотеки:** Pandas, Matplotlib, Seaborn, Scikit-learn

**Выводы и рекомендации по работе с клиентами:**

Проведенный анализ информации по признакам в том числе с применением методов машинного обучения и кластеризации в разрезе всех данных, а также в разрезе выявленных кластеров позволяет сформировать для реализации задачи снижения оттока 2 основных портрета клиентов сети фитнес - центров: КЛИЕНТ В ЗОНЕ РИСКА и ЛОЯЛЬНЫЙ КЛИЕНТ.

**ПОРТРЕТ КЛИЕНТА В ЗОНЕ РИСКА:** женщина или мужчина в возрасте 27 лет, пришедший в фитнес-центр впервые (предварительная коммуникация отсутствовала), купивший месячный абонемент, посетивший центр 1 раз, не покупающий дополнительные услуги (или в минимальном объеме), не посещяющий групповые занятия, живущий на удалении от фитнес-центра, не участвующий в партнерской программе и не пришедший по программе "приведи друга".

**ПОРТРЕТ ЛОЯЛЬНОГО КЛИЕНТА:** мужчина или женщина в возрасте 30 лет, на протяжении 5 месяцев находящися в коммуникационном поле фитнес-центра, купивший полугодовой или годовой абонемент, посещяющий центр 2 раза в месяц, покупающий дополнительные услуги на суммы от 158 рублей, посещающий групповые занятия, живущий рядом с центром, участвующий в партнерской программе и пришедший по программе "приведи друга".

Причины оттока могут быть связаны как с отсутствием мотивации у клиентов, так и с внутренними проблемами центра, как напрмер, чистота, исправность оборудования, внимательность персонала, достаточность шафчиков в пиковые часы и т.д.... В качестве рекомендаций для стратегии взаимодействия с клиентами и их удержания предлагается следующий ряд мер по выявлению клиентов в зоне риска и их целенаправленному движению по клиентскому пути от портрета Клиента в зоне риска до портрета Лояльного Клиента:

**РАБОТА С ПРИЧИНАМИ**

в первую очередь настойчиво рекомендуется составить анкету и организовать регулярные опросы клиентов, попавших в отток по результатам прошедшего месяца; цель - выяснить основные причины, разработать по ним план действий и реализовать его

**ПРОАКТИВНОСТЬ И СВОЕВРЕМЕННОЕ ВЫЯВЛЕНИЕ**

* разработать и внедрить автоматизированный отчет на базе CRM, который позволит выявлять клиентов, посетивших центр не более 1 раза за последние 30 дней от даты отчета;
* включать данных клиентов в обязательную коммуникацию - делать рассылки, например, с новостями фитнес-центра

**РАБОТА С ПРЕДЛОЖЕНИЕМ**

* сделать рыночный срез и провести ревизию привлекательности текущего предложения по полугодовым и годовым абонементам;при необходимости произвести коррекцию
* проработать варант 3-х месячного абонемента, который психологически не будет вызывать ощущения жесткой привязки к центру, не будет требовать полугодовых инвестиций, но уже будет работать на привыкание клиента и продвинет его по пути повышения лояльности
* разработать и внедрить (если меется, провести ревизию) программу лояльности, предлагающую определенный бонус за каждые следующие 3 месяца (или пол года) занятий в центре

**РАБОТА С ПРОДУКТОМ**

* провести ревизию дополнительных услуг и групповых занятий;
* провести анализ рынка и опрос клиентов на предмет их удовлетворенности как набором самих услуг и занятий, так и качеством

**ПРОДВИЖЕНИЕ ДЛЯ ЦЕЛЕВОЙ АУДИТОРИИ**

* таргетировать рекламу на жителей района по принципу геолокации, в котором расположен фитнес - центр
* с периодичностью 1 раз в квартал производить проверку организаций, расположенных в ареоле фитнес - центра, для выявления новых, не зайдествованных в партнерской программе
* организовать среди клиентов кампанию "расскажи о нас соседям" в соцсетях, в рамках которой клиент размещает позитивный отзыв о клубе на своей страничке со ссылкой на фитнес - центр; самые активные участники кампании получают в подарок бесплатное групповое занятие (если занятия платные), либо другую услугу фитнес - центра
* повысить для клиентов ценность предложения "приведи друга"

Все перечисленные выше меры в случае реализации плодотворно повлияют не только на клиентов в зоне риска, но и на лояльных клиентов, что будет работать на задачу снижения оттока.
