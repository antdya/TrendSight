№ Step 2. Продукт: $PRODUCT, неделя: $WEEK.

Получи содержимое файлов:
1. $REPO/projects/$PRODUCT/memory/signal_log.md
   (если файл есть — возьми последние 4–8 недель; если пустой — пропусти)
2. $REPO/projects/$PRODUCT/product_brief.md
3. $REPO/prompts/02_analyze.md
Используй raw_digest.md из Step 1 (он уже есть в контексте чата).

Выполни промт 02_analyze.md.
Выведи результат в Markdown.
Сохрани как: projects/$PRODUCT/digests/$WEEK/analysis.md
