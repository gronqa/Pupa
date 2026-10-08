# Pupa

Jednostronicowa strona-niespodzianka. Mobile first.

## Uruchomienie lokalnie

```
python3 -m http.server 4173
```

Potem `http://localhost:4173`.

## Zawartość

- `index.html` — cała strona (HTML + CSS + JS w jednym pliku, zero zależności)
- `img/` — zdjęcia przygotowane pod web: zmniejszone, przekonwertowane do sRGB,
  **z usuniętymi metadanymi EXIF** (oryginały z iPhone'a zawierały współrzędne GPS)

Oryginały leżą w `_oryginaly/` i są celowo wykluczone z repozytorium przez `.gitignore`.
Nie wrzucaj ich tutaj — mają w metadanych lokalizacje.

## Uwagi techniczne

- licznik dni liczy od `2026-03-13` w czasie lokalnym przeglądarki
- animacje wyłączają się przy `prefers-reduced-motion`
- `<meta name="robots" content="noindex">` — strona nie trafi do wyszukiwarki
