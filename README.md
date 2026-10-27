# Příprava na gymnázium (CZ/MN)

Statická webová aplikace: matematika + český jazyk, lekce, testy s časovačem. Bez build kroku – stačí otevřít `index.html`.

```
index.html      – kostra stránky
css/styles.css  – všechny styly
js/app.js       – logika, generátory úloh, lekce, testy
```

## Spuštění
Otevři `index.html` v prohlížeči (nebo `python3 -m http.server`).

## Nasazení na GitHub Pages
1. Nahraj složku do repozitáře (větev `main`).
2. Settings → Pages → Source: **GitHub Actions**.
3. Po každém `git push` se web nasadí sám (`.github/workflows/pages.yml`).

## Obsah a autorská práva
Úlohy jsou původní (generované). Oficiální testy CERMAT do repozitáře nekopíruj – odkazuj na ně.
