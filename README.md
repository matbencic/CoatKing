# Coat King

Landing stranica za salon za njegu pasa Coat King (Samobor), izrađena po uzoru na Instagram profil [@coatking.hr](https://www.instagram.com/coatking.hr/).

## Struktura

```
index.html         glavna stranica (sve sekcije, stilovi i skripta su unutar jedne datoteke)
images/             logo (ck-full.jpg, ck-icon.jpg)
```

## Logo i ilustracije

Logo se nalazi u `images/ck-full.jpg` (puni logotip s natpisom) i `images/ck-icon.jpg` (samo ikona, korištena u zaglavlju, footeru i "O nama" sekciji). Ilustracije pasmina u sekciji "Dvorski štićenici" ručno su nacrtane (SVG kod izravno u `index.html`) u stilu loga — ako ih kasnije želite zamijeniti stvarnim fotografijama pasa, samo javite.

## Uređivanje teksta

Sav tekst (usluge, opis, kontakt podaci, adresa, telefon, radno vrijeme itd.) nalazi se izravno u `index.html` i može se mijenjati po želji — trenutni tekstovi su spremni za objavu, ne radi se o placeholderima.

## Pregled prije objave

Otvorite `index.html` izravno u pregledniku, ili pokrenite lokalni server iz ovog foldera, npr.:

```
python3 -m http.server
```

pa otvorite `http://localhost:8000`.

## Objava na webu (opcionalno)

Stranica je statična (samo HTML + slike), pa je možete hostati bilo gdje — npr. na GitHub Pagesu, kao i LorenaPhotos. Za vlastitu domenu dodajte `CNAME` datoteku s nazivom domene (npr. `www.coatking.hr`) u ovaj folder.
