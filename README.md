## Исследование приливов Ирландии

### Общие сведения
Этот проект представляет собой исследование приливных процессов вокруг Ирландии с целью разработки комплексных решений для устойчивого развития и защиты береговых территорий, а также эффективного использования приливной энергии.

### Цель проекта
Цель данного исследования состоит в анализе приливных явлений и их влияния на береговые регионы Ирландии. Проект направлен на следующие задачи:


### Главные задачи проекта
1. **Анализ характера приливов:**
Исследовать амплитуду приливов (максимальные и минимальные значения) на каждой станции.
2. **Зависимость от географического положения:**
Выяснить, существует ли разница в приливах на разных сторонах острова.
3. **Тенденций максимальной высоты приливной волны с течением времени:**
Проанализировать данные за весь период и определить, есть ли общая тенденция к усилению или ослаблению приливов в течение года.

### Проблемы, которые поможет решить анализ
1. **Моделирование приливных процессов:**
Анализ данных позволит создать математические модели приливных волн, что поможет понять и прогнозировать их характеристики с высокой точностью.  
2. **Выявление географического фактора влияющего на приливы:**
Исследование данных позволит определить влияет ли географическое положение на аплитуду приливных волн. Амплитуда приливных волн может указывать на потенциально выгодные места для установки приливных электростанций.
4. **Разработка систем управления ресурсами и защиты береговой линии:**
Знание о высотах максимальных приливных волн позволяет разрабатывать эффективные системы защиты береговой линии от наводнений
5. **Понимание климатических изменений:**
Анализ долгосрочных данных о приливах может помочь в выявлении трендов, связанных с климатическими изменениями, и предсказании их воздействия на береговые регионы.

### Описание признаков
Данные представляют собой информацию о приливных явлениях вокруг Ирландии. Всего имеется 33 приливные станции, с которых собраны измерения приливных волн.

- **time:** Временная метка, указывающая на дату и время в формате UTC.
- **longitude:** Долгота местоположения приливной станции, измеряется в градусах на восток от Гринвичского меридиана (0 градусов долготы).
- **latitude:** Широта местоположения приливной станции, измеряется в градусах на север от экватора (0 градусов широты).
- **stationID:** Идентификатор приливной станции, где проводятся наблюдения или измерения.
- **Water_Level:** Измерение уровня воды в метрах.
- **Water_Level_ODM:** Значение уровня воды с учетом относительной высоты над уровнем моря (ODM - Ordnance Datum), таким образом, это значение может быть отрицательным или положительным, в зависимости от того, выше или ниже уровня моря находится местоположение.

Данные охватывают период с 1 января 2017 года по 1 января 2020 года, и объем данных по каждой приливной станции разнится в зависимости от выбранного интервала измерения и может быть как 157,681 записи, так и 262,801 записи, в зависимости от частоты замеров приливов.

### Ноутбук
Вы можете просмотреть ноутбук с помощью сервиса nbviewer: [Просмотреть ноутбук](https://nbviewer.org/github/PaulSpirin/Tide_Analysis/blob/main/Tide.ipynb)


### Установка библиотек
Код для устанвоки актуальных библиотек проекта:
`pip install -r requirements.txt`

### Источник данных
Данный набор данных был получен с ресурса [data.gov.ie](https://data.gov.ie), предоставляющего информацию о приливных данных, которые были сгенерированы на основе измеренных значениях, полученных через Ирландскую Национальную Сеть Гидрографических Датчиков.

**Источник данных:** [Приливные данные Морского института Ирландии](https://data.gov.ie/dataset/marine-institute-tide-prediction?package_type=dataset)

**Дата публикации:** 2018-09-05

**Дата последнего обновления:** 2021-05-17

**Соответствие набора данных стандартам:** См. соответствующие спецификации на ресурсе

**Правовые ограничения:** Creative Commons Attribution 4.0

**Язык данных:** Английский

**Географическое охват в формате GeoJSON:** {"type":"Polygon","coordinates":[[[-5.27233, 48.180187833],[-5.27233, 56.7], [-16.09085, 56.7], [-16.09085, 48.180187833], [-5.27233, 48.180187833]]]}

**Информация о происхождении данных:** Данные предоставлены Морским институтом.

### Автор
Автор проекта: Pavel Spirin  
Свяжитесь со мной по адресу agro.spirin@gmail.com для дополнительной информации или вопросов.
