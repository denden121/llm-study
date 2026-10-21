# Источники и выбор skills

Наставник в этом репозитории — собственная адаптация под опытного frontend-разработчика и Python/FastAPI. Сторонние пакеты и исполняемые скрипты не устанавливались. Из источников ниже использованы идеи; тексты skills целиком не копировались. Заявления авторов об эффективности не являются результатами нашей проверки.

| Источник | Что используем | Что меняем / ограничиваем |
|---|---|---|
| [Progressive Hint Ladder](https://github.com/GarethManning/education-agent-skills/tree/main/skills/student-learning/progressive-hint-ladder) | Постепенная помощь, первая попытка ученика | Полный ответ разрешён по запросу; без обязательного ритуала после каждой подсказки |
| [Tutor Skills](https://github.com/bevibing/tutor-skills) | Учёт пробелов по понятиям, диагностика, повторение в новом контексте | Markdown вместо обязательного Obsidian; открытые ответы и код вместо одних квизов; без Claude-specific инструментов |
| [Systematic Debugging](https://github.com/obra/superpowers/tree/main/skills/systematic-debugging) | Воспроизведение, факты, гипотеза, эксперимент, регрессионная проверка | Диагностирует ученик; число неудач не является доказательством дефекта архитектуры |
| [Supabase Postgres Best Practices](https://github.com/supabase/agent-skills/tree/main/skills/supabase-postgres-best-practices) | Дополнительный материал для ревью SQL, схем, индексов и блокировок | Читать релевантные разделы по задаче, проверять применимость к обычной PostgreSQL и установленной версии |
| [Learn from Materials](https://github.com/dmoshehun-prog/learn-from-materials) | Возможное будущее дополнение для изучения книг и документации | Не требуется для первых занятий, не установлен |

[FastAPI Expert](https://github.com/Jeffallan/claude-skills/tree/main/skills/fastapi-expert) не используется как технический эталон: при просмотре пример содержал некорректный импорт/вызов `model_config`, а правила чрезмерно обобщали необходимость async. Содержимое внешних репозиториев может меняться.

## Основные технические источники

- FastAPI: https://fastapi.tiangolo.com/
- Python: https://docs.python.org/3/
- PostgreSQL: https://www.postgresql.org/docs/
- SQLAlchemy 2: https://docs.sqlalchemy.org/en/20/
- Pydantic: https://docs.pydantic.dev/latest/
- pytest: https://docs.pytest.org/

Версионные детали проверять по версии учебного приложения. Не считать сгенерированный конспект заменой первоисточнику или практическому эксперименту.
