# Step 3. Продукт: $PRODUCT, неделя: $WEEK.
Получи содержимое файла:

$REPO/prompts/03_brief.md Используй raw_digest.md и analysis.md из Steps 1–2 (они уже есть в контексте чата).
Выполни промт 03_brief.md. Выведи два результата:

Финальный бриф (структура из 03_brief.md) сохрани в Markdown в projects/$PRODUCT/digests/$WEEK/analysis.md (добавить в конец файла)

По формату signal_log.md Сохрани результат в Markdown в файл в projects/$PRODUCT/memory/signal_log.md: топ-5 сигналов + статус гипотез (добавить запись в начало, старые не удалять).