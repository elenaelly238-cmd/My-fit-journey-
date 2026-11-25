# My Fit Journey – PWA

## Ce conține
- Plan săptămânal fără mic dejun (cafea dimineața, prânz, gustare, cină)
- Idei de rețete simple și meal prep de două ori pe săptămână
- Listă de cumpărături bifabilă
- Tracker de apă cu reset zilnic
- Plan de antrenamente și bifarea exercițiilor
- Istoric de greutate, talie și șolduri
- Salvare locală în browser și export JSON
- Manifest și service worker pentru instalare și utilizare offline

## Publicare
PWA trebuie servită prin HTTPS (sau localhost). Cel mai simplu:
1. Creează un cont pe GitHub și un repository nou, de exemplu `my-fit-journey`.
2. Încarcă toate fișierele din acest folder în repository.
3. În GitHub: Settings → Pages → Deploy from a branch → `main` / root → Save.
4. După publicare, deschide URL-ul HTTPS rezultat în Safari pe iPhone.
5. Apasă Share → Add to Home Screen → Add.

Alternativ, poți încărca folderul într-un proiect static pe Netlify sau Vercel.

## Date și confidențialitate
Datele sunt salvate local în browser prin localStorage. Nu există cont, backend sau sincronizare automată între iPhone și laptop. Folosește Exportă datele pentru backup. Pentru sincronizare multi-device este necesară o bază de date și autentificare.
