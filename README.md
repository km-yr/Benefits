# Benefity Pracownicze — KM Poland

Prosty przewodnik po benefitach dla nowych pracowników. Czysta strona HTML, bez żadnych zależności.

## Struktura

```
index.html        ← cała strona (treści benefitów są na dole pliku, w tablicy `benefits`)
assets/baner.jpg  ← zdjęcie w nagłówku (1920 × 400 px)
assets/logo.png   ← białe logo
```

## Publikacja na GitHub Pages

1. Wgraj zawartość tego folderu do repozytorium (np. `km-assets`) — `index.html` musi leżeć w głównym katalogu.
2. W repozytorium wejdź w **Settings → Pages**.
3. W sekcji **Build and deployment** wybierz **Source: Deploy from a branch**, branch **main**, folder **/ (root)** → **Save**.
4. Po ok. minucie strona będzie dostępna pod adresem:
   `https://<twoja-nazwa-uzytkownika>.github.io/<nazwa-repozytorium>/`

## Edycja treści

Otwórz `index.html`, znajdź tablicę `const benefits = [ ... ]` i zmieniaj pola danego benefitu.
Jeśli `link` to `"#"`, przycisk z linkiem jest ukryty.
