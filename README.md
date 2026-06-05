# Polkuopas – v13

Tämä versio on tehty version 12 pohjalta.

Muutokset:
- Estehälytyslogiikkaa muutettu hiekkatie-, asfaltti- ja sisätilamoodeissa.
- Varsinainen estehälytys tarkastelee nyt vain lähialuetta eli kuvan alaosaa.
- Kauempana olevat kohteet voivat edelleen vaikuttaa vasen/oikea-reitinohjaukseen.
- Estehälytys annetaan vain, jos lähialueella vasen, keskimmäinen ja oikea lohko ovat kaikki poikki.
- Metsäpolkumoodin erillinen poikittaisen/viiston esteen logiikka säilytetty ennallaan.
- Näkyvän ohjauslaatikon aria-live poistettu, jotta VoiceOver ei lue pitkää laatikkosisältöä.
- VoiceOver-puheohjeet pidetty lyhyinä: vasemmalle, oikealle, este, suojatie, suojatie päättyy.
- Käyttömoodipainikkeiden emojit poistettu, jotta VoiceOver sanoo vain:
  - Metsäpolku
  - Hiekkatie
  - Asfaltti
  - Sisätila

Käyttöönotto:
1. Korvaa GitHub-repositoryn juuressa oleva `index.html` tällä tiedostolla.
2. Commitoi muutos.
3. Avaa GitHub Pages -osoite iPhonen Safarissa.
