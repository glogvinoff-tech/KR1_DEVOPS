git add ide_notes.md
git commit -m "docs: add IDE vs CLI notes"
git push origin main
```markdown
# Git в VS Code: заметки

## Удобно в VS Code

1. **Визуальный diff** — сразу видно, что добавлено, а что удалено. Не нужно читать `git diff` в терминале.
2. **Редактор конфликтов** — кнопки «Accept Current / Incoming / Both» вместо ручного удаления маркеров `<<<<<<<`.
3. **GitLens** — показывает автора и дату каждой строки прямо в редакторе (визуальный `git blame`).

## Удобнее в терминале

1. **Интерактивный rebase** (`git rebase -i`, squash) — в CLI быстрее и понятнее, плюс работает на удалённом сервере по SSH, где IDE нет.
```