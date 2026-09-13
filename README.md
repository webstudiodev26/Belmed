# Stomatološka ordinacija Belmed

Statičan sajt. Nema build koraka, nema zavisnosti — otvara se direktno u pregledaču.

## Sadržaj

- `index.html` — cela strana (HTML, stilovi i logika)
- `support.js` — runtime koji strana koristi
- `image-slot.js` — komponenta za slike
- `slike/` — 10 fotografija (hero, ordinacija, 7 usluga)
- `.nojekyll` — da GitHub Pages ne preskoči fajlove
- `robots.txt`

## Hostovanje na GitHub Pages

1. Napravi novi repozitorijum na GitHub-u.
2. Prevuci sav sadržaj ove fascikle u repozitorijum (fajlovi moraju biti u korenu, ne u podfascikli).
3. Settings → Pages → Source: `Deploy from a branch`, Branch: `main`, folder: `/ (root)`.
4. Sajt je za minut dostupan na `https://<korisnicko-ime>.github.io/<repo>/`.

Lokalno testiranje: otvori `index.html` dvoklikom, ili pokreni `python3 -m http.server` u ovoj fascikli.

## Pre objave zameni izmišljene podatke

Ime ordinacije, adresa, telefon, ocena pacijenata (4,9/5 i 127 mišljenja) i radno vreme (pon–pet 09–19, sub 09–14) su probni podaci.

Forma za zakazivanje bez servera otvara SMS ka broju u `index.html`. Za slanje na email, upiši adresu servisa (npr. Formspree) u polje `bookingEndpoint`.
