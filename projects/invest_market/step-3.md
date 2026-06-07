# Step 3. Продукт: $PRODUCT, неделя: $WEEK.

Получи содержимое файла:
1. $REPO/prompts/03_brief.md
Используй raw_digest.md и analysis.md из Steps 1–2 (они уже есть в контексте чата).

Выполни промт 03_brief.md.
Выведи два результата:

1. Финальный бриф (структура из 03_brief.md)
   Сохрани как: projects/$PRODUCT/digests/$WEEK/analysis.md (добавить в конец файла)

2. Запись в signal_log (топ-5 сигналов + статус гипотез по формату signal_log.md)
   Сохрани как: projects/$PRODUCT/memory/signal_log.md (добавить запись в начало, старые не удалять)
