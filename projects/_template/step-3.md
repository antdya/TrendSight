# Step 3 — Бриф + обновление memory

> Скопируйте всё содержимое блока ниже и вставьте в Perplexity (в тот же чат, сразу после Step 2).

---

```
Продукт: {product-name}

Получи содержимое файла:
1. https://raw.githubusercontent.com/antdya/TrendSight/main/prompts/03_brief.md
Используй raw_digest.md и analysis.md из Steps 1–2 (они уже есть в контексте чата).

Выполни промт 03_brief.md.

Выведи два результата в формате Markdown:

## 1. Финальный бриф
(вся структура из промта 03_brief.md)
Сохрани как: projects/{product-name}/digests/YYYY-WNN/analysis.md (добавить в конец файла)

## 2. Запись в signal_log
(топ-5 сигналов + статус гипотез по формату из signal_log.md)
Сохрани как: projects/{product-name}/memory/signal_log.md (добавить новую запись в начало файла, старые записи не удалять)
```
