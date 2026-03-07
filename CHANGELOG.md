# Журнал изменений

Все заметные изменения в этом проекте будут задокументированы в этом файле.

Формат основан на [Keep a Changelog](https://keepachangelog.com/ru/1.0.0/),
и этот проект придерживается [Semantic Versioning](https://semver.org/lang/ru/).

## [1.0.0] - 2026-03-08

### Добавлено

- Первый релиз библиотеки сбора метрик Prometheus для OneScript.
- Реестр коллекторов (CollectorRegistry), типы метрик: Counter, Gauge, Histogram, Summary.
- Vec-варианты с лейблами (СчетчикВектор, ИндикаторВектор, ГистограммаВектор, РезюмеВектор).
- Сериализация в Prometheus Text Format; фасад модуль Prometheus для единой точки входа.
- Низкоуровневые модули: PrometheusMetrics, PrometheusVec, PrometheusRegistry, PrometheusTextFormat.
