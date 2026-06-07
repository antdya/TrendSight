# Step 2 — Анализ трендов

> Скопируйте всё содержимое блока ниже и вставьте в Perplexity (в тот же чат, сразу после Step 1).

---

```
Продукт: {product-name}

Получи содержимое файлов:
1. https://raw.githubusercontent.com/antdya/TrendSight/main/projects/{product-name}/memory/signal_log.md
   (если файл есть — возьми последние 4–8 недель; если пустой — пропусти)
2. https://raw.githubusercontent.com/antdya/TrendSight/main/projects/{product-name}/product_brief.md
3. https://raw.githubusercontent.com/antdya/TrendSight/main/prompts/02_analyze.md
А также используй raw_digest.md из Step 1 (он уже есть в контексте чата).

Выполни промт 02_analyze.md.

Выведи результат в формате Markdown.
Сохрани как: projects/{product-name}/digests/YYYY-WNN/analysis.md
```
