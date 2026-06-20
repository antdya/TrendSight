# Step 3. Продукт: $PRODUCT, неделя: $WEEK.
Получи содержимое файла:

$REPO/prompts/03_brief.md Используй raw_digest.md и analysis.md из Steps 1–2 (они уже есть в контексте чата).
Выполни промт 03_brief.md. Выведи два результата:

Финальный бриф (структура из 03_brief.md) сохрани в Markdown в projects/$PRODUCT/digests/$WEEK/analysis.md (добавить в конец файла)

По формату signal_log.md Сохрани результат в Markdown в файл в projects/$PRODUCT/memory/signal_log.md: топ-5 сигналов + статус гипотез (добавить запись в начало, старые не удалять).

После выполенния промта выведи ссылку на результат в формате, указанном ниже. Обрати внимание, если пользователь не передавал значение $PRODUCT, неделя: $WEEK, то используй те, который ты определил и использовал в рамках сессии сам.

## Формат вывода результата:

Подготовка дайджеста завершена.

Подробнее  
1.  Аналитика: https://antdya.github.io/TrendSight/projects/$PRODUCT/$WEEK/analysis.md
2.  Сырые данные: https://antdya.github.io/TrendSight/projects/$PRODUCT/$WEEK/raw_digest.md
