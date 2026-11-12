# Времена португальского глагола (PT-PT)

Наглядные конспекты шести времён европейского португальского для русскоязычных:
Pretérito Perfeito Simples, Pretérito Imperfeito, Pretérito Perfeito Composto,
Presente do Indicativo, Presente Contínuo и Futuro Próximo.

Сайт: https://selihovkin.github.io/ptpt-tempos/

## Как устроено

```
index.html          главная: все времена на одной шкале
pps/ pi/ ppc/       листы-конспекты, по папке на время
presente/ continuo/ futuro-proximo/
assets/style.css    все стили
404.html            страница «не найдено»
```

Это обычные HTML-страницы, собирать ничего не нужно. При каждом изменении в ветке `main`
сайт публикуется заново (`.github/workflows/deploy.yml`), ход публикации виден на вкладке **Actions**.

У каждой страницы есть переключатель «Кратко / Подробно». Выбор запоминается в браузере читателя.

Пока только светлая тема; тёмную добавим позже.
