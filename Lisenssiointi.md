
<img src="repo_transparent_100.png" alt="logo" style="float: right;">

# Ohjeita lisenssointiin
---
__Kun aloitat uuden ohjelmistoprojektin, herää monia kysymyksiä, alkaen tavoitteista ja välivaiheista aina toteutusyksityiskohtiin saakka. Yksi kriittinen yksityiskohta jää usein huomiotta, lisenssiehdot.__

__Selkeästi ja tarkasti (eksplisiittisesti) määritetty lisenssi__, antaa käyttäjillesi luvan käyttää, muokata ja jakaa työtäsi, on tärkeä osa reprodusoitavan tieteen prosessia. Ilman eksplisiittistä lisenssiä, joka kuvaa, *miten työtäsi saa käyttää*, saatat tahattomasti rajoittaa työsi vaikutusta, koska tekijänoikeus ja siihen liittyvät lait rajoittavat, miten muut voivat käyttää sitä.

Vaikka lisenssit voivat vaikuttaa monimutkaisilta oikeudellisilta asiakirjoilta, onneksi useat avoimen lähdekoodin lisenssit ovat sekä yhteisön laajalti käyttämiä että helppotajuisia.


>__Reprodusoitava tiede (Reproducible Science)__ viittaa siihen, että tieteellinen tutkimus on toistettavissa ja varmistettavissa. 
> Lisenssin nimenomainen määrittely (eksplisiittisyys) on  keskeinen osa tätä prosessia, 
> koska se mahdollistaa työn laillisen käytön, muokkaamisen ja jakamisen. Ilman selkeää lisenssiä reprodusoitavuus heikkenee, 
> koska muut eivät voi vapaasti hyödyntää tai tarkistaa työtä.


#### Lisenssit kahteen luokkaan

* [__Permissive__](https://en.wikipedia.org/wiki/Permissive_software_licence): ei aseta rajoituksia koodin käytölle johdannaisissa, mukaan lukien kaupallistaminen. Usein vaatii vain viittauksen.

* [__Copyleft__](https://en.wikipedia.org/wiki/Copyleft): Vaatii, että johdannaiset, tehdyt muutokset, ovat myös avoimen lähdekoodin lisenssin alaisia.

On myös tärkeää muistaa, että eri lisenssit eivät välttämättä ole yhteensopivia keskenään. Esimerkiksi, jos käytät "copyleft"-lisenssillä lisensoitua koodikantaa kehittääksesi omaa koodikantaasi, et välttämättä voi käyttää sallivaa lisenssiä. Katso alla lisää keskustelua tästä aiheesta.

**Avoimen lähdekoodin lisenssin käyttö ei sulje pois kaksoislisensointia, 
koodi voidaan jaakaa erilaisten lisenssien alaisena eri osapuolille (Esim. Ei kaupallinen - kaupallinen käyttö).**

Toisen lisenssin myöntäminen vaatii yleensä kaikkien tekijöiden hyväksynnän, joten se voi olla monimutkainen asia (katso alla Lisenssin muuttaminen).

#### Reproducible Research -standardi

Teoksessa [The Legal Framework for Reproducible Scientific Research](https://ieeexplore.ieee.org/document/4720221/) (PDF saatavilla [täältä](https://web.stanford.edu/~vcs/papers/Legal-STODDEN2009.pdf)), Victoria Stodden esittelee [Reproducible Research -standardin](https://web.stanford.edu/~vcs/talks/VictoriaStoddenCommuniaJune2009-2.pdf), joukon suosituksia varmistaakseen, että laskennalliseen tutkimustuotteeseen liittyvä koko tutkimuskokoelma julkaistaan tavalla, joka takaaa maksimaalisen hyödyn tutkimusyhteisölle samalla kun tekijät saavat ansaitsemansa tunnustuksen työstään.

Erityisesti tutkimuskokoelma sisältää heterogeenisia komponentteja, kuten koodia, dokumentaatiota, dataa, liittyviä mauscripts "käsikirjoituksia/luonnoksia" ja auciliariary material "apumateriaalia", joille sopivat eri lisenssit.

Vaikka ohjelmistolisenssit, kuten [MIT-lisenssi](http://choosealicense.com/licenses/mit/), sopivat kuvaamaan, miten koodia voidaan käyttää, muokata ja jakaa uudelleen, se ei ole järkevää soveltaa dokumentaatioon tai dataan, koska nämä eivät ole koodia.

#### Suositukset

Reproducible Research -standardin oikeudellisia ohjeita noudattaen, suositeltava on käyttää Permissive Licenses sallivia lisenssejä.

* [MIT-lisenssiä](http://choosealicense.com/licenses/mit/) tai
* [3-Clause BSD -lisenssiä](https://opensource.org/licenses/BSD-3-Clause) koodille, ja
* [Creative Commons By Attribution (CC-BY) 4.0 -lisenssiä](https://creativecommons.org/licenses/by/4.0/) 


#### Muut resurssit (Resources)

On tärkeää päättää itse, mitkä ovat prioriteettisi ja mitä resursseja sinulla on käytettävissä lisenssien hallintaan. Alla tarjoamme lyhyen yleiskatsauksen useista hyödyllisistä lisenssivaihtoehdoista tieteelliselle ohjelmistolle.

Löydät yleiskatsauksen erilaisista ohjelmistolisensseistä, jotka on suunnattu ohjelmistokehittäjille tästä [artikkelista](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002598).

Vertailtaessa erilaisia lisenssejä, voidaan käyttä erilaisia lähteitä, kuten tätä [vertailutaulukkoa](http://choosealicense.com/appendix/).

#### Open Source Initiative (OSI)
Sitä pidetään laajalti luotettavana "avoimen lähdekoodin" määrittelijänä, löytyy [täältä](https://opensource.org/). Tätä määritelmää avoimen lähdekoodin lisensseistä käyttävät monet rahoittajat (esim. [NSF](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1565146)). Sitä käytetään esimerkiksi määrittelemään, mitkä lisenssit ovat sallittuja apurahan ehdoissa.

---
### Permissive Licenses (sallivat lisenssit)

Permissive Licenses:it asettavat hyvin vähän vaatimuksia johdannaisten kehittäjille (derivative work) tai käyttäjille.

#### MIT-lisenssi

Yksi suosituimmista sallivista lisensseistä on [MIT-lisenssi](http://choosealicense.com/licenses/mit/). 
Kuten alta näkee, tämä lisenssi myöntää käyttäjille ja kehittäjille luvan tehdä mitä haluavat, 
ja vapauttaa kehittäjät vastuusta takuuväitteistä.

Jatkokehittäjien tarvitsee vain sisällyttää tämä ilmoitus. Tämä voi olla ihanteellinen akateemisille aloille, koska 
se mahdollistaa uusien ideoiden laajan käytön ja samalla varmistaa, että asianmukaiset henkilöt saavat tunnustuksen työstään.

__MIT-lisenssi on muodoltaan yksinkertainen:__  
(suomennettu ainoastaan tämän dokumentin käyttöön)

```
MIT License
Copyright (c) [vuosi] [koko nimi]

Tämän ohjelman ja siihen liittyvien dokumenttien kopioiden käyttö, kopiointi, 
muokkaaminen, yhdistäminen, julkaiseminen, jakaminen, alilisensointi ja/tai myynti 
on sallittua ilman maksua kenelle tahansa***, joka saa kopion tästä ohjelmasta, 
seuraavin ehdoin:

Edellä mainittu tekijänoikeusilmoitus ja tämä käyttölupa on sisällytettävä 
kaikkiin kopioihin tai merkittäviin osiin ohjelmasta.

OHJELMA TARJOTAAN "SELLAISENA KUIN SE ON", ILMAN MINKÄÄNLAISTA TAKUUTA, 
NIMENOMAISESTI ILMAISTUA TAI EPÄSUORAAN, MUKAAN LUKIEN MUTTA EI RAJOITTUENTA KAUPPAKELPOISUUTEEN, 
SOVELTUVUUTEEN TIETTYYN TARKOITUKSEEN JA TEKNISESTÄ RIITTEISTÄ. 
MISSÄÄN TAPAUKSESSA TEKIJÄT TAI TEKIJÄNOIKEUDEN OMISTAJAT EIVÄT OLE VASTUUSSA MISSÄÄN VAATIMUKSESSA, 
VAHINGOSSA TAI MUUSSA VASTUUSSA, JOKA JOHTUU OHJELMAN KÄYTTÖSTÄ TAI OHJELMAN KÄYTTÖKYVYTTÖMYYDESTÄ 
TAI MUISTA TOIMENPITEISTÄ OHJELMAN YMPÄRILLÄ.
```

**Alkuperäinen lisenssi notaatio**
```
MIT License
Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```


#### Alilisensointi

**Alilisensointi** (engl. sublicensing) tarkoittaa tilannetta, jossa alkuperäinen lisenssinhaltija (esim. ohjelmistonsa kehittäjä) 
antaa toiselle osapuolelle (esim. käyttäjälle tai yritykselle) oikeuden myöntää lisenssejä edelleen kolmansille osapuolille. 
Tämä tarkoittaa, että alkuperäisen lisenssin saaja voi itse toimia lisenssinantajana ja antaa oikeuksia käyttää, muokata tai 
jakaa lisensoitua tuotetta (esim. ohjelmistoa) muille.

>__Esimerkki:__
>- Jos yritys A ostaa ohjelmistolisenssin yritykseltä B ja tämä lisenssi sallii **alilisensoinnin**, 
yritys A voi myöntää kolmansille osapuolille (esim. asiakkailleen) oikeuden käyttää samaa ohjelmistoa.

__Alilisensoinnin ehdot__
- Alkuperäinen lisenssi määrittelee, sallitaanko alilisensointi. 
Esimerkiksi jotkut avoimen lähdekoodin lisenssit (kuten GPL) eivät yleensä salli alilisensointia, 
kun taas toiset (kuten MIT-lisenssi) sallivat sen.
- Alilisensointi ei voi antaa enemmän oikeuksia kuin alkuperäinen lisenssi myöntää.

__Käyttötarkoitukset__
- **Kaupallinen käyttö:** Yritys voi alilisensoida ohjelmistonsa asiakkailleen.
- **Jakaminen:** Alkuperäinen lisenssinhaltija voi antaa toiselle osapuolelle oikeuden jakaa tuotetta eteenpäin tietyin ehdoin.
Alilisensointi on yleinen käytäntö esimerkiksi ohjelmistoteollisuudessa, 
ja se mahdollistaa joustavamman lisenssien hallinnan ja jakelun.
---
#### Mihin lisenssien käsite *"merkittäviin osiin ohjelmasta"* viittaa?

Lauseessa **"merkittäviin osiin ohjelmasta"** viitataan ohjelman osiin, jotka ovat riittävän suuria tai oleellisia, jotta ne vaikuttavat ohjelman kokonaisuuteen. Tämä ilmaisu on tarkoituksella joustava, ja sen tarkka merkitys riippuu kontekstista sekä lainsäädännöstä. 

>__Ohjelman osat, jotka ovat riittävän suuria__
>- Esimerkiksi kokonaisia moduuleja, luokkia tai funktioita, jotka muodostavat merkittävän osan ohjelman toiminnallisuudesta.
>- Ei välttämättä sisällä pieniä koodinpätkiä tai yksittäisiä rivejä, jotka eivät ole merkittäviä kokonaisuuden kannalta.

>__Ohjelman osat, jotka ovat oleellisia__
>- Osat, jotka ovat keskeisiä ohjelman toiminnan kannalta. 
>
>Esimerkiksi:
>- Algoritmit, jotka ratkaisevat ohjelman keskeisiä tehtäviä.
>- Käyttöliittymän komponentit, jotka ovat näkyvissä loppukäyttäjälle.
>- Tiedonhallintajärjestelmät tai tietokantayhteydet.

>__Ohjelman osat, jotka ovat riittävän alkuperäisiä__
>- Jos otat osan ohjelmasta ja se sisältää alkuperäistä koodia, joka on suojattu tekijänoikeuksilla, se voi olla "merkittävä osa".
>- Ei välttämättä sisällä geneerisiä tai yleisesti käytettyjä koodinpätkiä, jotka eivät ole uniikkeja.

>Esimerkki 1: Moduuli tai kirjasto
- Jos otat käyttöön kokonaisen moduulin tai kirjaston alkuperäisestä ohjelmasta, se on todennäköisesti "merkittävä osa".

- Esimerkki: Käytät alkuperäisen ohjelman grafiikkamotuulia omassa projektissasi.

>Esimerkki 2: Pieni koodinpätkä
- Jos otat käyttöön yhden funktion tai muutaman rivin koodia, se ei välttämättä ole "merkittävä osa". *Esimerkki:* Kopioit yhden apufunktion, joka laskee kahden luvun summan.

>Esimerkki 3: Käyttöliittymäkomponentti
- Jos otat käyttöön alkuperäisen ohjelman käyttöliittymän osan (esim. painikkeen tai valikon), se voi olla "merkittävä osa".
- *Esimerkki:* Käytät alkuperäisen ohjelman navigointipalkkia omassa sovelluksessasi.

---

### Apache-lisenssi 2.0

Tämä lisenssi on hieman vähemmän salliva kuin edellä mainittu MIT-lisenssi. Muun muassa [Apache-lisenssi 2.0](https://www.apache.org/licenses/LICENSE-2.0) edellyttää, 
että johdannaisissa - jatkokehityksessä kerrotaan tehdyt muutokset (vaikka lähdekoodin paljastaminen ei ole pakollista). 

Tärkeää on, että Apache-lisenssi tarjoaa myös eksplisiittisen patenttilisenssin käyttäjille ja kehittäjille. Tämä estää 
johdannaisten kehittäjiä haastamasta patenttirikkomuksesta. Koska lisenssi on melko pitkä, emme ole toistaneet sitä tässä.

[Apache-lisenssi](https://www.apache.org/licenses/)

### BSD-lisenssi (3-lauseke, uusi)

BSD-lisenssi on toinen joukko sallivia lisenssejä, joissa on pieniä eroja. Uusi lisenssi sisältää eksplisiittisen lausekkeen, että ohjelman tekijöiden nimiä ei saa käyttää johdannaisten mainostamiseen ilman lupaa: Ei tekijänoikeuden omistajan nimeä eikä sen osallistujien nimiä saa käyttää johdannaisten tuotteiden mainostamiseen tai markkinoimiseen ilman erillistä kirjallista lupaa.

>Tämä on hyödyllinen ominaisuus niille, jotka ovat huolissaan siitä, että johdannaisten tekijät saattavat viitata projektin osallistujiin ja vahingoittaa heidän mainettaan samalla.

BSD-lisenssi on muuten samankaltainen kuin MIT-lisenssi, [lisensii löytyy täältä](http://choosealicense.com/licenses/bsd-3-clause/).

**Huom:** On myös muita BSD-lisenssejä, joita ei käsitellä tässä. Lisätietoja löytyy tästä [vertailutaulukosta](http://choosealicense.com/appendix/).

[BSD-lisenssi tästä linkistä (3-clause, new)](http://choosealicense.com/licenses/bsd-3-clause/)

### Copyleft-lisenssit

Vaikka sallivat lisenssit helpottavat koodin laajaa käyttöä, mukaan lukien käyttö suljetun lähdekoodin johdannaisissa, joskus katsotaan sopivaksi kannustaa lisää avoimen lähdekoodin kehitystä. Niin sanotut ["copyleft"](https://en.wikipedia.org/wiki/Copyleft) -lisenssit tarjoavat juuri tämän: ne käyttävät tekijänoikeuden käsitettä vaatimaan, että johdannaisten kehittäjät myös tekevät johdannaisesta avoimen lähdekoodin alaisia.

Vaikka lisää avoimen lähdekoodin kehityksen edistäminen onkin hyvä tavoite, on tärkeää huomata, että monet "copyleft"-lisenssit voivat myös karkottaa kaupallisten ohjelmistotoimittajien luottamusta ohjelmaasi sen vuoksi, miten se saattaa vaikuttaa heidän ohjelmistoonsa. Tämän vuoksi näiden lisenssien valitseminen voi joissakin tapauksissa kaventaa käyttäjäkuntaasi tai tehdä kaupallisista toimittajista haluttomampia yhteistyöhön.

### GPL

**Ehkä tunnetuin copyleft-lisensseistä on GPL eli GNU General Public License**. Se asettaa vahvat ehdot johdannaisten kehittäjille. Johdannaiset eivät ainoastaan tarvitse olla avoimen lähdekoodin lisenssin alaisia, vaan niiden on myös käytettävä yhteensopivaa lisenssiä, mikä antaa sille "viruksenomaisen" ominaisuuden, "copyleft" -periaatteet säilyvä. 

>**Joten miksi valitsisit tämän lisenssin?**
>
>Jos haluat varmistaa, että johdannaiset jotka perustuvat työhösi ovat myös vapaasti saatavilla muille kehittäjille, tämä voi olla sopiva lisenssi.

[Lisenssi löytyy sivulta, GNU Public License (GPL) 3.0](http://choosealicense.com/licenses/gpl-3.0/)

### LGPL

Kun kirjoitat kirjastoa, johon pääasiassa päästään käsiksi rajapinnan kautta (eikä muut voi sitä suoraan muokata), LGPL ("Lesser GNU GPL") voi olla houkutteleva lisenssi. Vaikka tämä asettaa samat rajoitukset muutosten kautta johdetuille töille, linkittäminen ja koodin käyttö LGPL-lisenssillä julkaistuna on vapautettu tästä vaatimuksesta. Tämä on usein hyödyllinen kompromissi niille, jotka kirjoittavat rajapintoja, joita käytetään niiden tarkoitetulla tavalla. 

[Lisätietoa löytyy sivulta, Lesser GNU Public License (LGPL) 3.0](http://choosealicense.com/licenses/lgpl-3.0/)

### AGPL

Vaikka GPL ja LGPL on tarkoitettu varmistamaan, että koodin käyttäjät pääsevät käsiksi sen sisäisiin osiin, entä koodi, jota käyttäjät eivät koskaan saa? Koodi toimitetaan palveluna internetin kautta, jolloin käyttäjät eivät koskaan näe yhtäkään koodiriviä. 

AGPL (GNU Affero General Public License) on tarkoitettu tätä tapausta varten. Se edellyttää, että jopa verkko-ohjelmointirajapinnan kautta näkyvät johdannaiset tehdään avoimen lähdekoodin lisenssin alaisiksi.

[Lisätietoa löytyy sivulta, GNU Affero General Public License (AGPL)](http://choosealicense.com/licenses/agpl-3.0/)

### Lisenssin muuttaminen

#### Kaksoislisensointi

- __Mitä jos pidät GPL:n ideasta, mutta sinulla on myös kaupallisia kumppaneita, jotka ovat kiinnostuneita koodistasi, mutta eivät GPL:stä?__

- __Tai entä jos tieteelliset yhteistyökumppanisi ovat kirjoittaneet yhteensopimatonta koodia?__

On tärkeää muistaa, että kehittäjänä voit uudelleenlisensoida koodin ryhmälle ilman näitä rajoituksia. Tieteellisenä esimerkkinä Folding@Home-projekti jakaa binäärimuodossa muokatun version [GROMACS](http://gromacs.org)-ohjelmistosta, joka sisältää kryptografisen koodin estämään tulosten vääristelyä tai muuttamista lahjoittajien koneilla; Folding@Home [sai erityislisenssin](https://foldingathome.stanford.edu/support/faq/opensource/) GROMACS-kehittäjiltä tätä tarkoitusta varten, vaikka GROMACS oli tuolloin GPL-lisenssin alainen ohjelmistopaketti (ja nyt LGPL-lisenssin alainen).

#### Lisenssin vaihtaminen

Joskus projektin edetessä kehittäjät saattavat päättää, että alkuperäinen lisenssi ei enää ole sopiva. Lisenssi voidaan vaihtaa kaikkien tekijänoikeudenhaltijoiden suostumuksella. [Wikipedia](https://en.wikipedia.org/wiki/Software_relicensing)

#### Tiimin saaminen mukaan

Monien kehittäjien projektissa lisenssin muuttaminen tai ohjelmiston uudelleenlisensointi voi olla haastavaa.

Ratkaisuja:

* Sallivat lisenssit kuten MIT sallivat kenentahansa käyttää koodia haluamallaan tavalla
* Jos käytät copyleft-lisenssiä, mutta haluat esimerkiksi tarjota myös kaupallisen lisenssin, kehittäjien allekirjoittama _osallistujasopimus_ voi määrittää, milloin ja miten nämä muutokset voivat tapahtua.

#### Osallistujasopimus (Contributor Agreement)

Yleensä tarvitaan kaikkien tekijöiden suostumus uusien lisenssien myöntämiseen. Osallistujasopimuksen käyttäminen voi auttaa varmistamaan, että lisälisenssien myöntäminen koodille on helppoa tarvittaessa.

OSI:n usein kysytyistä kysymyksistä:
> Monet avoimen lähdekoodin projektit hyväksyvät korjauksia (koodi- tai dokumentaatiomuutoksia) vain henkilöiltä, jotka ovat toimittaneet laillisen asiakirjan, joka tunnetaan nimellä osallistujasopimus. Osallistujasopimukset eivät ole avoimen lähdekoodin lisenssejä — ne ovat tapa, jolla osallistuja kertoo projektille, että sillä on oikeus jakaa uudet muutokset projektin nykyisen avoimen lähdekoodin lisenssin mukaisesti. (Jotkut osallistujasopimukset sallivat myös projektin jakaa muutokset muiden avoimen lähdekoodin lisenssien mukaisesti, mikä mahdollistaa projektin lisenssin vaihtamisen tulevaisuudessa, ja jotkut sopimukset jopa sallivat projektin jakaa muutokset minkä tahansa projektin haluaman lisenssin mukaisesti.) [Lähde](https://opensource.org/faq#contributor-agreements)

### Lisenssien yhteensopivuus

Tieteessä meidän on pystyttävä hyödyntämään toistemme panoksia voidaksemme käyttää tieteellisen tiedon kokonaisuutta täysin. Emme todellakaan halua lisenssikysymysten häiritsevän tätä tuottavuutta. Yleisesti ottaen sallivat lisenssit eivät ole merkittävä huolenaihe johdannaisten yhteensopivuuden kannalta.

Copyleft-lisenssit voivat kuitenkin aiheuttaa ongelmia; lisätietoja GPL-tyyppisten lisenssien yhteensopivuudesta löytyy [tältä sivulta](https://www.gnu.org/licenses/license-list.en.html).

---
>*This is a finnish translation of the original text, the translation was not professionally done. Please note that this translation may contain inaccuracies.*

---
[**Orginal Documentation:** *GihHub: Software Development Best Practices for Computational Chemistry*](https://www.gnu.org/licenses/license-list.en.html)

**Credits to Contributors**: *John D. Chodera, Patrick B. Grinaway, Andrea Rizzi, Gregory Ross, Levi N. Naden,  Arien ("Bas") S. Rustenburg , E. A. Rosenzweig*

---
>This document was originally published under the license.
>- *This documentation resource is licensed under the Creative Commons Attribution 4.0 License.*
>
> You are free to:
>>- Share — copy and redistribute the material in any medium or format
>>- Adapt — remix, transform, and build upon the >material for any purpose, even commercially.
>>
>>The licensor cannot revoke these freedoms as long as you follow the license terms.
>>
>>You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
>
>*[See the full terms of the license here: Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)*
