FORMA PO MERI · sajt za hosting

HOSTING NA GITHUB PAGES
1. Napravite novi repozitorijum na github.com (npr. "formapomeri").
2. Add file → Upload files → prevucite SAV sadržaj ovog foldera
   (index.html mora biti u root-u repozitorijuma, ne u podfolderu). Commit.
3. Settings → Pages → Source: "Deploy from a branch", Branch: main, folder: / (root) → Save.
4. Za minut-dva sajt je na https://KORISNIK.github.io/formapomeri/
5. Sopstveni domen (npr. formapomeri.rs): Settings → Pages → Custom domain,
   pa kod registra domena dodajte DNS zapise koje GitHub prikaže. Uključite "Enforce HTTPS".
Fajl .nojekyll je namerno tu (GitHub tada servira fajlove bez obrade).

Na drugom hostingu sadržaj foldera ide u root domena (npr. public_html):
  index.html, support.js, images/, favicon.svg, robots.txt, sitemap.xml

Pre objave:
1. Kontakt forma: napravite formu na formspree.io i u index.html zamenite
   VAS_FORMSPREE_ID svojim ID-jem (action="https://formspree.io/f/...").
2. Domen: ako domen nije formapomeri.rs, zamenite ga u index.html
   (canonical, og:url, og:image, JSON-LD), robots.txt i sitemap.xml.
3. Link "politika privatnosti" trenutno vodi na "#".
4. Posle objave: dodajte sajt u Google Search Console i pošaljite sitemap.xml.

Spoljni servisi: Google Fonts (Jost), Lenis (glatki skrol, unpkg), Google mapa.
