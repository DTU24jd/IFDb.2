# IFDB - TV Serije

Aplikacija za pregled i pretraživanje TV serija, glumaca i epizoda s mogućnošću spremanja omiljenih serija po korisničkom računu. Izgrađena je u Next.js-u i koristi TVmaze API.

##  Ključne funkcionalnosti

- Početna lista serija
- Dinamičke rute za detalje serije, glumca i epizode
- Dodavanje i brisanje favorita (privremeno u cookie)
- Stranica `/favorites` za pregled omiljenih serija
- Prikaz 404 stranice za nepostojeće rute
- Deploy na Vercel 

##  Upute za lokalno pokretanje

1. Klonirajte repozitorij:
   ```bash
   git clone <URL_VAŠEG_REPOZITORIJA>
   cd IFDB2-main
   ```

2. Instalirajte ovisnosti:
   ```bash
   npm install
   ```

3. Pokrenite razvojni server:
   ```bash
   npm run dev
   ```
   Aplikacija će biti dostupna na [http://localhost:3000](http://localhost:3000)


##  Build & Deploy

Za produkcijski build pokrenite:
```bash
npm run build
```

Za lokalno testiranje produkcijskog builda:
```bash
npm start
```

Deploy preporučujemo putem [Vercel](https://vercel.com/).

 **Link na produkcijsku verziju (Vercel):** [DODATI NAKNADNO]

##  Poznate greške / TODO

- Favoriti se trenutno spremaju u cookie i nisu trajno vezani uz korisnički račun
- Podržana je samo prijava putem Google računa
- Sučelje nije u potpunosti prilagođeno mobilnim uređajima

---

## Bilješka autora

Ovaj projekt razvijen je kao dio tečaja **Junior Dev** u organizaciji **Digitalna Dalmacija**. Cilj je bio savladati rad s API-ima, autentifikaciju korisnika te moderne alate poput Next.js-a, Tailwind CSS-a i NextAuth-a.

Projekt je edukativne prirode i trenutno je u aktivnom razvoju.
#   I F D b . 2  
 #   I F D b . 2  
 #   I F D b . 2  
 #   I F D b . 5  
 