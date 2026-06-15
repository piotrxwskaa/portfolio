# Folder: images/

Umieść tutaj wszystkie zdjęcia używane na stronie.

## Lista plików do dodania

| Nazwa pliku        | Opis                                          | Format / rozmiar min.     |
|--------------------|-----------------------------------------------|---------------------------|
| hero.jpg           | Zdjęcie główne (sekcja Hero) — pionowe        | JPG, 800×1200 px          |
| about.jpg          | Zdjęcie w sekcji "About me" — pionowe         | JPG, 720×960 px           |
| thumb-01.jpg       | Miniatura wideo 1 — Product demonstration     | JPG, 720×1280 px (9:16)   |
| thumb-02.jpg       | Miniatura wideo 2 — Voice-over                | JPG, 720×1280 px (9:16)   |
| thumb-03.jpg       — Miniatura wideo 3 — Testimonial            | JPG, 720×1280 px (9:16)   |
| thumb-04.jpg       | Miniatura wideo 4 — Unboxing                  | JPG, 720×1280 px (9:16)   |
| thumb-05.jpg       | Miniatura wideo 5 — Lifestyle video           | JPG, 720×1280 px (9:16)   |
| thumb-06.jpg       | Miniatura wideo 6 — Aesthetic product shots   | JPG, 720×1280 px (9:16)   |
| brand-01.png       | Logo marki 1 (przezroczyste tło)              | PNG, ~300×100 px           |
| brand-02.png       | Logo marki 2                                  | PNG, ~300×100 px           |
| brand-03.png       | Logo marki 3                                  | PNG, ~300×100 px           |
| brand-04.png       | Logo marki 4                                  | PNG, ~300×100 px           |
| brand-05.png       | Logo marki 5                                  | PNG, ~300×100 px           |
| brand-06.png       | Logo marki 6                                  | PNG, ~300×100 px           |

## Jak podpiąć zdjęcia w kodzie

Otwórz `index.html` i znajdź komentarz `<!-- PLACEHOLDER: Replace with... -->`.
Przykład dla sekcji hero:

```html
<!-- Usuń cały .hero-ph div i wklej: -->
<img src="images/hero.jpg" alt="Monika – UGC Creator">
```

Przykład dla miniatur wideo:
```html
<!-- Usuń .ph-box div wewnątrz .vid-thumb i wklej: -->
<img src="images/thumb-01.jpg" alt="Product demonstration">
```

Przykład dla logotypów marek:
```html
<!-- Zamień zawartość .brand-logo div na: -->
<div class="brand-logo"><img src="images/brand-01.png" alt="Nazwa marki"></div>
```
