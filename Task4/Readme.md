
[Диаграмма Исикавы drawio](Исикава.drawio)

[Диаграмма Исикавы](Isikawa.png)

# Рекомендациям по решению выявленных проблем


## Люди
 - Excel-гуру -> Product Owners
 - Обучение микросервисным паттернам
 - Пилотные команды с ранним доступом
 - Геймификация перехода

## Данные
 - Инвентаризация всех Excel файлов
 - Создание единых каталогов данных 
 - Построение Data Lineage

## Инструменты
Этап 1 MVP: Базовые инструменты
 - Git + CI/CD (GitLab CI/GitHub Actions)
 - Docker + Kubernetes
 - API Gateway (Kong/APISIX)
 - Keycloak
 - BigID

Этап 2: Продвинутые
 - Service Mesh (Istio/Linkerd)
 - Мониторинг (Prometheus + Grafana)
 - Логирование (ELK/EFK)
 - Apache Airflow

## Окружение
 -  Поэтапная миграция (strangler fig pattern)
 -  Создание Center of Excellence
 -  Четкая коммуникация о выгодах
 -  Регулярные демо для стейкхолдеров