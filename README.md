# Aurora Étterem & Panzió – weboldal

Az aurora.co.hu oldal forrása. Egyetlen statikus oldal (`index.html`) a képekkel (`img/`) és a saját tárhelyről betöltött betűtípusokkal (`fonts/`).

- A szerkeszthető tartalom (elérhetőségek, szállás, heti menü, étlap) az `index.html` `SITE` és `MENU` blokkjában van.
- Tárhely: GitHub Pages, a `main` ágról. Minden új commit után 1–2 percen belül élesben van; build lépés nincs, kreditkorlát nincs.
- `CNAME`: a saját domain (aurora.co.hu). `.nojekyll`: a fájlok változtatás nélkül kerülnek ki.
- `404.html`: a régi oldal nyelvi címeit (/hu/, /de/, /en/, /cz/) a főoldalra irányítja a megfelelő nyelven, a `/kerdoiv` címet a kérdőívre.
- Foglalási űrlapok: Web3Forms, e-mailben érkeznek. A kulcs a `SITE.booking.web3formsKey` helyen van.
- `netlify.toml`: a korábbi Netlify-tárhely beállításai; GitHub Pages-en nincs hatása.
