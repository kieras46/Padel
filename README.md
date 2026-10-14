# Paletka – wersja na iPhone'a bez Maca (PWA, offline)

Pliki: index.html, sw.js, manifest.webmanifest, icon-180.png, icon-512.png.
Czujniki ruchu w Safari działają tylko na stronie przez HTTPS, więc trzeba ją gdzieś wystawić (za darmo):

## Opcja A – GitHub Pages (z telefonu lub dowolnego komputera)
1. Załóż konto na github.com, utwórz nowe publiczne repozytorium (np. `paletka`).
2. "Add file" → "Upload files" → wrzuć wszystkie 5 plików → Commit.
3. Settings → Pages → Source: "Deploy from a branch", gałąź `main`, folder `/ (root)` → Save.
4. Po minucie gra jest pod adresem `https://TWOJ-LOGIN.github.io/paletka/`.

## Opcja B – Netlify Drop
Wejdź na app.netlify.com/drop, przeciągnij cały folder, dostaniesz adres https.

## Na iPhonie
1. Otwórz adres w Safari (z internetem).
2. Udostępnij → "Dodaj do ekranu początkowego".
3. Uruchom grę z ikony raz przy włączonym internecie (zapisze się w pamięci), potem działa bez sieci.
4. Przy pierwszym "Zaczynamy" Safari zapyta o dostęp do ruchu i orientacji – wybierz "Zezwól".
   Jeśli odmówisz: Ustawienia → Safari → Ruch i orientacja (lub usuń ikonę i dodaj ponownie).
