# Исследование надежности заемщиков

[ipynb](https://nbviewer.jupyter.org/github/AlexVarnik/data-analyst/blob/main/DA_002_data_preprocessing/DA_002_data_preprocessing.ipynb)


## Описание проекта

Кредитный отдел банка просит определить, влияют ли характеристики клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.

## Цель исследования:

Определить, как влияют на факт погашения кредита в срок следующие факторы:
- семейное положение;
- количество детей;
- уровень дохода;
- цель кредита. 

Результаты исследования будут учтены при построении модели кредитного скоринга.

## Выводы:

Факт погашения кредита в срок имеет зависимость от каждого из рассмотренных факторов:

1. *Семейное положение* - Заемщики, у которых нет детей, возвращают кредит в срок чаще, чем заёмщики с детьми;
2. *Количество детей* - Заёмщики в статусах `вдовец/вдова` и `в разводе` реже других допускают появление задолженности, а чаще других не возвращают кредит в срок `неженатые/незамужние` и `живущие в гражданском браке`;
3. *Уровень дохода* - Хуже возвращают кредиты клиенты со средними доходами 'C' от `50 001 до - 200 000` и с самыми низкими доходами 'E' от `0 до 30 000`, а лучше с категориями 'D' от `30001 до 50000` и 'B' от `200 001 – 1 000 000`;
4. *Цель кредита* - Наименьший процент задолженностей для кредитов на `недвижимость`, а наибольший для категорий `получение образование` и `операции с автомобилем`.