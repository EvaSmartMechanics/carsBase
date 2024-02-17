# https://cars-base.ru
# Бесплатная база данных автомобилей в JSON, CSV формате
**cars.json** - база данных марок и моделей легковых автомобилей  
**cars.csv** - версия в формате таблицы 

**Данные:**
- ID_MARK
- Марка
- Марка кириллица
- Популярная марка
- Страна
- MODEL_ID
- Модель
- Модель кириллица
- Класс
- Год от
- Год до


_База обновляется!_
## База 1. Расширенная база легковых автомобилей CSV, XLSX, MySQL, JSON
Также имеется база автомобилей (https://auto.ru/catalog/cars/) содержащая следующие поля:
- id
- Марка
- Модель
- Название поколения
- Год начала производства
- Год окончания производства
- Тип кузова

еще 50 характеристик и 158 опций (если есть комплектация)

Все подробности: **https://cars-base.ru**

## База 2. Расширенная база CSV, JSON коммерческого транспорта и мототехники
**!!!ТОЛЬКО!!!** **Марка и Модель** без характеристик  

Пример CSV:
```
Категория,Марка,Модель
Лёгкие коммерческие,Citroen,Berlingo
Лёгкие коммерческие,Citroen,C25
Лёгкие коммерческие,Citroen,Jumper
Лёгкие коммерческие,Citroen,Jumpy
Лёгкие коммерческие,Fiat Professional,242-serie
Лёгкие коммерческие,Fiat Professional,Doblo
Лёгкие коммерческие,Fiat Professional,Ducato
...
```
Пример JSON:
```json
{
  "Лёгкие коммерческие": {
    "Citroen": [
      "Berlingo",
      "C25",
      "Jumper",
      "Jumpy"
    ],
    "Fiat Professional": [
      "242-serie",
      "Doblo",
      "Ducato",
      ...
```
**Для получения полной базы свяжитесь со мной** в **[Telegram](https://t.me/gulpsun9)**
с пометкой "**Коммерческий и мото транспорт**"

Источник данных:  
https://auto.ru/lcv/all/  
https://auto.ru/motorcycle/all/
