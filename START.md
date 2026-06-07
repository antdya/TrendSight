# TrendSight — Запуск сессии

> Вставьте этот блок первым сообщением в новый чат Perplexity. Затем поочерёдно вставляйте Step 1, Step 2, Step 3.

```
Я запускаю еженедельнюю аналитическую сессию для продукта TrendSight.

Переменные сессии:
PRODUCT = tourism-rf
WEEK = 2026-W24
REPO = https://raw.githubusercontent.com/antdya/TrendSight/main

Запомни эти значения. Они будут использоваться во всех последующих шагах без повторного указания.
Ответь: «Понял. Жду Step 1.»
```

---

## Step 1

```
Step 1. Продукт: $PRODUCT, неделя: $WEEK.

Получи содержимое двух файлов:
1. $REPO/projects/$PRODUCT/user_profile.md
2. $REPO/prompts/01_collect.md

Выполни промт 01_collect.md, используя параметры из user_profile.md.
Выведи результат в Markdown.
Сохрани как: projects/$PRODUCT/digests/$WEEK/raw_digest.md
```

## Step 2

```
Step 2. Продукт: $PRODUCT, неделя: $WEEK.

Получи содержимое файлов:
1. $REPO/projects/$PRODUCT/memory/signal_log.md
   (если файл есть — возьми последние 4–8 недель; если пустой — пропусти)
2. $REPO/projects/$PRODUCT/product_brief.md
3. $REPO/prompts/02_analyze.md
Используй raw_digest.md из Step 1 (он уже есть в контексте чата).

Выполни промт 02_analyze.md.
Выведи результат в Markdown.
Сохрани как: projects/$PRODUCT/digests/$WEEK/analysis.md
```

## Step 3

```
Step 3. Продукт: $PRODUCT, неделя: $WEEK.

Получи содержимое файла:
1. $REPO/prompts/03_brief.md
Используй raw_digest.md и analysis.md из Steps 1–2 (они уже есть в контексте чата).

Выполни промт 03_brief.md.
Выведи два результата:

1. Финальный бриф (структура из 03_brief.md)
   Сохрани как: projects/$PRODUCT/digests/$WEEK/analysis.md (добавить в конец файла)

2. Запись в signal_log (топ-5 сигналов + статус гипотез по формату signal_log.md)
   Сохрани как: projects/$PRODUCT/memory/signal_log.md (добавить запись в начало, старые не удалять)
```
