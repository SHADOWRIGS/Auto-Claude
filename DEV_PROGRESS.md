# DEV_PROGRESS — Auto-Claude

> Живой чек-лист автономного цикла. Проект: мульти-агентный фреймворк автономного кодинга (Python backend + Electron frontend).

## ✅ Done
- 2026-11-11: Заведён трекинг-чек-лист, ветка `ccr-e9692c67-uk3jai`. Есть implementation_plan.json.

## ⏳ Remaining (roadmap)
- [ ] i18n: все пользовательские строки фронта через react-i18next (en + fr), никаких хардкодов.
- [ ] Кроссплатформенность: платформенные проверки — через platform-модули, не `process.platform` вразнос.
- [ ] Тесты backend: `apps/backend/.venv/bin/pytest tests/ -v`.
- [ ] Разобрать TODO/FIXME (21 файл).
- [ ] Все AI-вызовы — только через Claude Agent SDK (core/client.create_client), не напрямую Anthropic API.

## 🧭 Decisions made
- Строго следуем CLAUDE.md: SDK вместо прямого API, i18n-ключи, platform-абстракция.

## ⚠️ Flagged for review — проверь
- (пока нет)
