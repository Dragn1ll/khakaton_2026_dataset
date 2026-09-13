# Казань: очищенные датасеты и тестовые материалы

Подготовлено 13 сентября 2026 года.

**434 записей, 408 разных точек, 179 точек с изображениями.** Для остальных фото не подтверждены и imageUrl=null.

## Девять датасетов в Markdown

- [museum.md](datasets_md/museum.md) — 46 записей.
- [history.md](datasets_md/history.md) — 166 записей.
- [religion_architecture.md](datasets_md/religion_architecture.md) — 48 записей.
- [theatre.md](datasets_md/theatre.md) — 20 записей.
- [art.md](datasets_md/art.md) — 57 записей.
- [literature.md](datasets_md/literature.md) — 50 записей.
- [walks_parks.md](datasets_md/walks_parks.md) — 32 записей.
- [viewpoint.md](datasets_md/viewpoint.md) — 4 записей.
- [tatar_food.md](datasets_md/tatar_food.md) — 11 записей.

В datasets_json лежат те же очищенные данные для импорта. Исходные JSON сохранены в родительской папке outputs.

## Иконки категорий

[Предпросмотр девяти иконок](icons_preview.html). SVG находятся в папке icons. Иконок отдельных мест нет. Все иконки созданы для этого пакета; можно использовать и изменять.

iconPath и categoryIconPath — пути относительно корня этого пакета. categoryIconUrl=null: файлы не опубликованы. После размещения на вашем сервере заполните абсолютный HTTPS URL для контракта API. Изображения также представлены ссылками, а не скачанными файлами.

## Проверки и обучение

- [Один успешный и десять негативных API-кейсов](api_tests/API_TEST_PLAN.md).
- [Postman-коллекция](api_tests/tourist_api.postman_collection.json).
- [42 примера оценки LLM и рекомендации](llm_evaluation/LLM_BENCHMARK.md).
- [JSONL для оценки](llm_evaluation/prompt_benchmark.jsonl).

## Качество и источники

- [Отчёт и ограничения проверки](audit/AUDIT_REPORT.md).
- [Исключённые точки](audit/REMOVED_POINTS.md).
- [Места без изображения](audit/MISSING_IMAGES.md).

LLM-набор предназначен для оценки и содержит ожидаемые безопасные ответы. Не включайте сырые атакующие строки в обучение без ролей, правильных ответов и редакционной проверки. API-тесты не запускались: требуется адрес окружения.
