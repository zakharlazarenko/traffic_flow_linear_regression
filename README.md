# Traffic Prediction Dataset

*Датасет и описание взяты с kaggle.com*

## Описание данных
Данные представляют собой ценный ресурс для изучения дорожных условий, собранный с помощью компьютерной модели зрения. Модель обнаруживает четыре типа транспортных средств:
- Легковые автомобили (CarCount)
- Мотоциклы (BikeCount)
- Автобусы (BusCount)
- Грузовики (TruckCount)

Структура данных (CSV):
- Временные метки: время (час), дата, день недели
- Количество ТС каждого типа за 15-минутный интервал
- Столбец "Total" — общее количество всех ТС за 15 минут
- Класс трафика (1-Heavy, 2-High, 3-Normal, 4-Low)

Частота обновления: каждые 15 минут (данные за 1 месяц).

## Применение данных
1. **Транспортное планирование**:
   - Анализ загруженности дорог
   - Оптимизация светофоров и полос движения
2. **Городская инфраструктура**:
   - Выявление проблемных участков
   - Планирование дорожных работ
3. **Исследования**:
   - Изучение корреляции с внешними факторами (погода, события)
   - Анализ поведения трафика по времени/дням недели

## Цель проекта
Разработка модели прогнозирования транспортного потока (количество ТС/час) на основе:
- Временных признаков (время суток, день недели)
- Контекстных данных (погодные условия, праздники)
- Исторических показателей загруженности

Метрики оценки: MAE, RMSE, R²
