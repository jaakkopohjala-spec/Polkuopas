# Polkuopas - kehitysversio 10

Muutokset versioon 9 nähden:
- Metsäpolkumoodiin lisätty varovaisempi "polku löytyy / ei löydy" -portti.
- Jos metsäpolkua ei tunnisteta riittävän varmasti, sovellus ei anna vasen/oikea-ohjausääniä.
- Suojatien tunnistus on tiukempi:
  - vaaditaan vähintään kolme vaaleaa tai vaaleanharmaata viivaa
  - viivojen pitää olla erillisiä
  - viivojen pitää olla samansuuntaisia / rinnakkaisia
  - viivojen välistyksen pitää olla uskottava
  - havainto vahvistetaan useammassa peräkkäisessä analyysissä ennen ilmoitusta
- Esteentunnistus on varovaisempi:
  - tummuus yksin ei enää riitä esteeksi
  - metsäpolkumoodissa esteeksi hyväksytään ensisijaisesti polun poikki kulkeva pitkulainen kappale
  - sivukasvillisuuden aiheuttamia virhehälytyksiä on pyritty vähentämään
  - muissa moodeissa este vaatii kokoa, reunaa/tekstuuria ja ajallista vahvistusta
- Estehälytys aktivoituu vasta, kun sama este-ehdokas on havaittu useamman analyysiruudun ajan.

Käyttöönotto:
1. Korvaa GitHub-repositoryn juuressa oleva `index.html` tällä tiedostolla.
2. Commitoi muutos.
3. Avaa GitHub Pages -osoite iPhonen Safarissa.
