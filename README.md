# Ranya Tajmer 💛

Jednostavan, jednokratan sajt koji:
- broji koliko je vremena provedeno u Njemačkoj (od 18.8.2026 13:40 do izlaska iz zemlje 27.8.2026 20:40)
- odbrojava do povratka u Mostar (28.8.2026 02:30)
- ispod tajmera prikazuje trenutnu lokaciju prema unesenom rasporedu putovanja
- mijenja pozadinu prema dobu dana u Njemačkoj (zora / dan / veče / noć)
- ima prekidač za svijetlu i tamnu temu (gornji desni ugao)

## Fajlovi
- `index.html` — struktura stranice
- `style.css` — stil, teme, pozadina
- `script.js` — tajmeri, raspored putovanja, logika teme

## Kako uploadati na GitHub Pages

1. Napravi novi repozitorij na GitHub-u (npr. `ranya-tajmer`).
2. Uploaduj sva tri fajla (`index.html`, `style.css`, `script.js`) u root repozitorija (Add file → Upload files).
3. Idi u **Settings → Pages**.
4. Pod "Branch" izaberi `main` i folder `/ (root)`, pa klikni **Save**.
5. Za par minuta sajt će biti dostupan na:
   `https://tvoj-username.github.io/ranya-tajmer/`

## Napomena o rasporedu

Ako se raspored putovanja promijeni, otvori `script.js` i izmijeni `schedule` niz na vrhu fajla — svaki red predstavlja jedan segment (lokacija ili putovanje) sa tačnim vremenom početka i kraja.
