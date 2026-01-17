# Sovellusten-h-kk-ys
## h0
Nopea ohjelma joka kysyy nimeä ja tervehtii, käännettynä binääriksi.

LÄHDEKOODI:
```python
nimi=str(input("Kerro nimesi"))
print("Hello",nimi)
```

Ohjelma binäärinä binary viewer lisäosassa.
![Ohjelma binääriä](Python_binääri.JPG)

## h1 Kotiverkon ISMS soveltamisala
Osa kotiverkon laitteista kuuluu soveltamisalaan, koska niitä käytetään koulutehtävien tekoon. Muut laitteet ovat kohdeympäristön ulkopuolella, koska ne eivät ole oleellisia tehtävien kannalta. Osa tarpeellisista resursseista ovat täysin hallintani ulkopuolella ja rajaan ne siksi ulos. Muutamat resurssit ovat osittain vaikutukseni alaisia tai olen niiden käytöstä vastuussa ja siksi ne osittain kuuluvat soveltamisalaan.
Verkkoyhteys muodostuu puhelimesta, jolla jaetaan hotspot Wi-Fi yhteys muille laitteille. Laitteita verkossa: HP EliteBook 840 G2 (Ubuntu desktop virtuaalikone pyörii tällä koneella), HP Pavilion (Out of scope, koska sitä ei käytetä koulutehtäviin), PlayStation 4(Out of scope, koska sitä ei käytetä koulutehtäviin). 
Rajapintoja ovat Telia verkontarjoaja, OneDrive pilvitallenustila, GitHub tallenustila ja staattisen websivun isännöinti, Moodle kurssin verkkoalusta, Laksu tehtävien palautus verkkoalusta, Citrix koulun etätyöpöytä, Visual studio code koodieditori.

![Verkkokaavio](Soveltamisala doodle.JPG)

Todisteet: 
Wi-Fi = Kuvankaappaus verkkoyhteyden ominaisuuksista. Laitteiden tiedot listattuna. Kuvakaappaus virtuaalikoneesta. Linkki GitHub repoon, kuvakaappaus OneDrive asetuksista.

<table>
    <tr>
        <td>Sidosryhmät</td>
        <td>Tarve / Vaatimus / Odotus</td>
        <td>ISO 27001 vaatimusalue</td>
        <td>Evidence</td>
    </tr>
    <tr>
        <td>Minä</td>
        <td>Tärkeiden tiedostojen ja järjestelmien suojaus sekä saatavuus. Tehtävien jatkuvuus. Confidentiality, Integrity, Availability</td>
        <td>ISO 27001 kokonaisuudessaan</td>
        <td>Soveltamisalan määrittäminen Tietoturva tavoitteiden ja toimien suunnitelma sekä toimeenpano. Auditointi ja dokumentaatio</td>
    </tr>
    <tr>
        <td>Operaattori</td>
        <td>Verkkoyhteyden sopimuksenmukainen käyttö. Security, Compliance</td>
        <td>Operation 8.1 toiminnan suunnittelu ja ohjaus.</td>
        <td>Toiminnan auditointi ja seurannan dokumentointi</td>
    </tr>
    <tr>
        <td>Viranomainen</td>
        <td>Lainsäädännön noudattaminen Henkilötietojen käsittely asianmukaisella tavalla. Privacy, Compliance</td>
        <td>Operation 8.1 &amp; Performance evaluation 9.1  Seuranta, mittaus, analysointi ja arviointi.</td>
        <td>Toiminnan auditointi ja seurannan dokumentointi</td>
    </tr>
</table>

Tehtävässä käytetty SFS-EN ISO/IEC 27001:2023 Tietoturvallisuus, kyberturvallisuus ja tietosuoja. Tietoturvallisuuden hallintajärjestelmät. Vaatimukset. Suomen Standardisoimisliitto SFS ry

