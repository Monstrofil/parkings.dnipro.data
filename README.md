# Информация о парковках в г. Днепр

ВНИМАНИЕ! Список составлен на волонтерских основаниях на основе открытых данных и решений горсовета. 
КП Горавтопарк не поддерживает список в данном репозитории.

## Источники данных
* Портал открытых данных: [данные об операторах по состоянию на сентябрь 2019](https://opendata.dniprorada.gov.ua/dataset/%D0%B4%D0%B0%D0%BD%D1%96-%D0%BF%D1%80%D0%BE-%D0%BF%D0%B0%D1%80%D0%BA%D1%83%D0%B2%D0%B0%D0%BD%D0%BD%D1%8F-%D1%83-%D1%82%D0%BE%D0%BC%D1%83-%D1%87%D0%B8%D1%81%D0%BB%D1%96-%D0%BF%D1%80%D0%BE-%D1%80%D0%BE%D0%B7%D0%BC%D1%96%D1%89%D0%B5%D0%BD%D0%BD%D1%8F-%D0%BC%D0%B0%D0%B9%D0%B4%D0%B0%D0%BD%D1%87%D0%B8%D0%BA%D1%96%D0%B2-%D1%97%D1%85-%D0%BE%D0%BF%D0%B5%D1%80%D0%B0%D1%82%D0%BE%D1%80%D1%96%D0%B2-%D0%BE%D0%B1%D0%BB%D0%B0%D0%B4%D0%BD%D0%B0%D0%BD%D0%BD%D1%8F-%D1%82%D0%B0), [координаты парковок по состоянию на 2018г](https://opendata.dniprorada.gov.ua/dataset/%D0%BF%D0%B5%D1%80%D0%B5%D0%BB%D1%96%D0%BA-%D1%81%D0%BF%D0%B5%D1%86%D1%96%D0%B0%D0%BB%D1%8C%D0%BD%D0%B8%D1%85-%D0%B7%D0%B5%D0%BC%D0%B5%D0%BB%D1%8C%D0%BD%D0%B8%D1%85-%D0%B4%D1%96%D0%BB%D1%8F%D0%BD%D0%BE%D0%BA-%D0%B2%D1%96%D0%B4%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D1%85-%D0%B4%D0%BB%D1%8F-%D0%BE%D1%80%D0%B3%D0%B0%D0%BD%D1%96%D0%B7%D0%B0%D1%86%D1%96%D1%97-%D1%82%D0%B0-%D0%BF%D1%80%D0%BE%D0%B2%D0%B0%D0%B4%D0%B6%D0%B5%D0%BD%D0%BD%D1%8F-%D0%B4%D1%96%D1%8F%D0%BB%D1%8C%D0%BD%D0%BE%D1%81%D1%82%D1%96).
* [Решения горсовета](https://dniprorada.gov.ua/uk/page/poshuk-prijnyatih-dokumentiv-dniprovskoi-miskoi-radi)

## Описание данных
### parkings_dnipro.csv
Файл csv с разделителем ",", utf-8.
Поля:
* address - примерное местоположение относительно известных почтовых адресов;
* working_hours - время работы, TODO: сделать machine-readable
* operator - оператор парковки;
* area - площадь, посчитана как 11,5 * places для всех парковок;
* places - количество паркомест;
* location_type - расположение парковки по мнению горсовета;
* type - тип парковки: служебные, отведенные, специально оборудованные;
* latitude
* longitude
* verified - проверены ли координаты площадки;
* uuid - уникальный идентификатор парковки, не меняется.

## Контакты
По любым вопросам и предложением обращайтесь на public@parkingdp.online либо в issues.
