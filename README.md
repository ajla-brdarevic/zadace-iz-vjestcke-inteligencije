# Zadaće iz predmeta Vještačka inteligencija - PTF UNZE SI II Ciklus I Semestar 2024/25

## Simulirano kaljenje za generisanje rasporeda [kreiranje_rasporeda_sa_algoritmom_simuliranog_kaljenja.ipynb](kreiranje_rasporeda_sa_algoritmom_simuliranog_kaljenja.ipynb)

Ova Python skripta koristi algoritam simuliranog kaljenja za generisanje rasporeda predavanja i vježbi, minimizirajući broj konflikata u vezi sa vremenskim slotovima i dostupnim sobama.

### Funkcionalnosti

- **Generisanje rasporeda**: Slučajni raspored predmeta, sala i slotova.
- **Računanje konflikata**: Broj konflikata kada se isti predmet dodijeli u isti vremenski slot i sobu.
- **Perturbacija rasporeda**: Promjena jednog predmeta u rasporedu.
- **Simulirano kaljenje**: Optimizacija rasporeda smanjenjem broja konflikata.

### Korištenje

1. Klonirajte ovaj repozitorij.
2. Instalirajte zavisnosti:
    ```bash
    pip install numpy matplotlib
    ```
3. Pokrenite skriptu:
    ```bash
    python naziv_skripte.py
    ```
4. Rezultati i grafikon konvergencije bit će prikazani.
