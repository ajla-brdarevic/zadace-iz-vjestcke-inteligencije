# Zadaće iz predmeta Vještačka inteligencija - PTF UNZE SI II Ciklus I Semestar 2024/25

## [1. zadaća: Simulirano kaljenje za generisanje rasporeda](https://github.com/ajla-brdarevic/zadace-iz-vjestcke-inteligencije/tree/main/1.%20zadaća)

Ova Python skripta koristi algoritam simuliranog kaljenja za generisanje rasporeda predavanja i vježbi, minimizirajući broj konflikata u vezi sa vremenskim slotovima i dostupnim sobama.

### Funkcionalnosti

- **Generisanje rasporeda**: Slučajni raspored predmeta, sala i slotova.
- **Računanje konflikata**: Broj konflikata kada se isti predmet dodijeli u isti vremenski slot i sobu.
- **Perturbacija rasporeda**: Promjena jednog predmeta u rasporedu.
- **Simulirano kaljenje**: Optimizacija rasporeda smanjenjem broja konflikata.

## [2. zadaća](https://github.com/ajla-brdarevic/zadace-iz-vjestcke-inteligencije/tree/main/2.%20zadaća)
### [Prvi zadatak](https://github.com/ajla-brdarevic/zadace-iz-vjestcke-inteligencije/blob/main/2.%20zadaća/zadatak_1.ipynb)
Svjetska Banka želi da donese odluku o tome da li je novopredloženi projekat isplativ za realizaciju:
- Na osnovu slučajeva iz prošlosti prikazani na slici 1 treba napraviti klasifikacioni model koristeći algoritam Naivnog Bajesa.
- Istu tabelu iskoristiti i primjeniti stablo odlučivanja.
  
U oba slučaja provjeriti koja će se donijeti odluka.

<img src="https://github.com/ajla-brdarevic/zadace-iz-vjestcke-inteligencije/blob/main/2.%20zadaća/slika1.png" alt="Slika 1" width="400">

### [Drugi zadatak](https://github.com/ajla-brdarevic/zadace-iz-vjestcke-inteligencije/blob/main/2.%20zadaća/zadatak_2.ipynb)
Suad je u dilemi. Treba da stigne do fakulteta na vježbe iz "Vještačke inteligencije", ali kako je saobraćaj u Sarajevu nepredvidiv, često mu se dogodi da kasni. Kako bi izbjegao kašnjenje, pokušaće da koristi znanje iz prošlosti da predvidi da li treba da krene ranije nego obično. Napisao je situacije iz prošlosti prikazane na slici 2.

<img src="https://github.com/ajla-brdarevic/zadace-iz-vjestcke-inteligencije/blob/main/2.%20zadaća/slika2.png" alt="Slika 2" width="400">

## [3. zadaća: Predviđanje težine ribe](https://github.com/ajla-brdarevic/zadace-iz-vjestcke-inteligencije/tree/main/3.%20zadaća)

Cilj je analizirati, razumjeti i donijeti zaključke o mogućnosti predviđanja težine ribe. Razviti model koji predviđa težinu na osnovu drugih parametara (nasumično podijeliti podatke na setove za obuku, validaciju i testiranje).

### Izrada zadatka

U ovom zadatku se koristi linearna regresija za modeliranje odnosa između karakteristika (ulaznih podataka) i ciljne varijable. Podaci se dijele na trening, validacijski i testni skup, a zatim se evaluira model pomoću metrike MSE (srednja kvadratna pogreška) i R^2 (koeficijent determinacije). Na kraju, analiziraju se koeficijenti modela kako bi se odredio značaj svake karakteristike u predviđanju ciljne varijable.

## [4. zadaća]
[Zadatak br. 1 - Twitter Sentiment]
Cilj je razviti model mašinskog učenja koji može predviđati sentiment na Twitteru koristeći dostupne skupove podataka za treniranje i testiranje.

[Zadatak br. 2 - Toxic Comments]
Cilj je pružiti rješenje za sljedeći zadatak na Kaggleu: https://www.kaggle.com/c/jigsaw-multilingual-toxic-comment-classification/overview
