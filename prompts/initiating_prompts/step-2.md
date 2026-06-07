# Step 2. Продукт: $PRODUCT, неделя: $WEEK.

Получи содержимое файлов:

$REPO/projects/$PRODUCT/memory/signal_log.md (если файл есть — возьми последние 4–8 недель; если пустой — пропусти)
$REPO/projects/$PRODUCT/product_brief.md
$REPO/prompts/02_analyze.md Используй raw_digest.md из Step 1 (он уже есть в контексте чата).
Выполни промт 02_analyze.md. Сохрани результат в Markdown в файл: projects/$PRODUCT/digests/$WEEK/analysis.md
