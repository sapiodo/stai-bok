---
description: Изучение одной концепции BoK по 5-слойной структуре Learning Object
---

Запусти skill `study-concept` (см. `.claude/skills/study-concept/SKILL.md`).

Аргумент: `$ARGUMENTS` — slug концепта или специальная команда:
- `<slug>` — режим deep-study (по умолчанию)
- `quick <slug>` — режим quick-recall (слои 1, 2, 5)
- `compare <slug-1> <slug-2>` — сравнение двух концептов

Если аргумент пустой или slug не распознан — покажи список доступных концептов из `concepts/_index.md` и попроси выбрать.

Найди карточку `concepts/{NN}-{slug}.md` и веди студента по 5 слоям с диалоговыми точками С1-С4.
