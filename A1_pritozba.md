# Pritožba zaradi nedelovanja 4G/5G internetne povezave A1

> **Jezik / Language:** [English version](A1_pritozba_en.md)

**A1 od ponedeljka, 7. 9. 2026, ni sposoben zagotoviti osnovne internetne povezave.**

Že več dni sem **popolnoma brez uporabnega dostopa do interneta**, čeprav sem od bazne postaje oddaljen le približno **200 metrov**.

## Tehnično stanje

Uporabljam modem **ZTE888B**. Modem in lokalna oprema delujeta normalno, vendar modem trenutno vzpostavi zgolj **3G povezavo**.

Na modemu **utripa modra lučka `Network`**, kar pomeni, da je modem povezan oziroma registriran v **3G omrežju**. Povezava **4G/LTE oziroma 5G se ne vzpostavi**.

To je pomembna tehnična podrobnost, saj:

* modem deluje,
* SIM-kartica je vstavljena in zaznana,
* modem se lahko poveže v mobilno omrežje,
* vzpostavljena je **3G povezava**,
* vendar **4G/LTE in 5G povezava ne delujeta**,
* zato je dostop do interneta neuporaben oziroma ga praktično ni.

Glede na navedeno je zelo malo verjetno, da bi bila težava v moji lokalni opremi. **Modem očitno deluje in komunikacija z mobilnim omrežjem je mogoča, vendar omrežje ne zagotovi pričakovane 4G/5G povezave.**

Še posebej problematično je, da sem od bazne postaje oddaljen le približno **200 metrov**, zato bi pričakoval normalno razpoložljivost 4G/5G signala, če je ta na tej lokaciji zagotovljena.

### Preizkušeni postopki

Po navodilih podpore sem večkrat izvedel vse običajne postopke:

* izklop modema,
* čakanje,
* ponovni vklop,
* reset modema,
* odstranitev in ponovna namestitev SIM-kartice.

**Nobeden od teh postopkov ni odpravil težave.**

Ker modem po vseh teh postopkih še vedno deluje na **3G**, 4G/LTE in 5G pa se ne vzpostavita, ponavljanje osnovnih postopkov na uporabniški strani nima več smisla. Potrebna je **dejanska diagnostika mobilnega omrežja, bazne postaje oziroma konfiguracije storitve**.

---

## Zahteva za tehnično diagnostiko na strani A1

Glede na opisano stanje prosim, da se težava obravnava kot **omrežna oziroma radijska napaka** in ne več kot težava uporabniške opreme.

Prosil bi za preverjanje naslednjih tehničnih parametrov:

### 1. Registracija naprave v omrežje

Preverite, ali je SIM oziroma naročniški profil pravilno registriran in avtoriziran za:

* **4G/LTE (E-UTRAN)**,
* **5G NR**,
* ustrezni APN za podatkovni promet,
* uporabo podatkovnega prometa na moji lokaciji.

Posebej prosim za preverjanje, ali je na strani omrežja kakršna koli omejitev, blokada ali napačna konfiguracija, zaradi katere naprava ostane na 3G.

### 2. LTE/5G pokritost in stanje celice

Prosím za preverjanje konkretne bazne postaje oziroma celice, na katero se moja naprava poskuša povezati.

Preveriti je treba predvsem:

* ali je **LTE sektor/celica aktivna**,
* ali je **5G NR celica aktivna**,
* ali je prišlo do izpada posameznega sektorja,
* ali je bazna postaja v degradiranem načinu,
* ali je na bazni postaji zaznana napaka,
* ali so bili v zadnjih dneh izvedeni posegi, nadgradnje ali spremembe konfiguracije,
* ali je zaradi okvare oziroma vzdrževanja promet preusmerjen oziroma omejen na 3G.

### 3. Radio dostop in izbira tehnologije

Ker naprava brez težav zazna in uporablja 3G, vendar se **LTE/5G ne vzpostavi**, prosim za preverjanje postopka izbire tehnologije oziroma **cell selection / cell reselection**.

Zanimajo me predvsem:

* ali naprava na lokaciji sploh prejme LTE/5G broadcast informacije,
* ali je LTE/5G celica za mojo SIM oziroma naročniški profil dovoljena,
* ali omrežje napravo pri registraciji zavrne,
* ali obstaja težava pri prehodu oziroma registraciji iz 3G v LTE,
* ali je konfiguracija omrežja na tej lokaciji pravilna.

### 4. Preverjanje radijskih parametrov

Če je mogoče, prosim za preverjanje oziroma posredovanje izmerjenih radijskih parametrov za mojo lokacijo:

* **RSRP**,
* **RSRQ**,
* **SINR**,
* uporabljeni **LTE band/frekvenčni pas**,
* uporabljena celica oziroma **Cell ID / eNB ID**,
* pri 5G pa tudi ustrezni **NR band** in podatki o NR celici.

Ker je naprava približno **200 m od bazne postaje**, bi bilo smiselno preveriti, ali so radijski parametri na LTE/5G sektorju normalni oziroma ali obstaja kakšna anomalija v radijskem delu omrežja.

### 5. Preverjanje naročniškega profila

Prosím tudi za preverjanje, ali je na mojem naročniškem profilu pravilno omogočena uporaba:

> **LTE / 4G + 5G podatkovnega dostopa**

Če je naročniški profil pravilno konfiguriran, prosim za preverjanje, zakaj se naprava kljub temu registrira samo v 3G.

### 6. Preverjanje napak v omrežju

Prosil bi za preverjanje omrežnih logov za mojo SIM/napravo oziroma poskusov registracije v LTE/5G.

Če so bili poskusi registracije zavrnjeni, bi bilo koristno preveriti konkretni razlog oziroma **reject cause**, saj bi ta lahko neposredno pokazal, ali gre za:

* zavrnitev registracije,
* težavo z naročniškim profilom,
* težavo z avtorizacijo,
* napačno konfiguracijo celice,
* težavo z jedrnim omrežjem,
* ali radijsko težavo.

---

## Pomembno

Prosím, da se ta prijava **ne zaključi z navodili za ponovni zagon, reset modema ali odstranitev SIM-kartice**, saj so bili ti postopki že večkrat izvedeni brez kakršnega koli učinka.

Dejstvo, da:

1. modem deluje,
2. SIM-kartica je zaznana,
3. naprava se registrira v mobilno omrežje,
4. 3G povezava se vzpostavi,
5. 4G/LTE in 5G pa se ne vzpostavita,

je dovolj močan indikator, da je treba težavo obravnavati na **omrežni/radijski oziroma naročniški konfiguracijski ravni**.

---

## Odnos podpore

Še bolj problematičen od same tehnične napake je **odnos podpore uporabnikom**.

Vsakič, ko pokličem, moram ponovno razlagati **celotno zgodbo od začetka**, kot da predhodni klici in prijave sploh ne bi obstajali oziroma da se težava ne bi ustrezno evidentirala.

Vedno znova dobim ista, že večkrat preizkušena in dokazano neučinkovita navodila. Kljub temu da sem jih že večkrat izvedel in jasno povedal, da niso pomagala, se postopek vedno začne znova.

## Obljubljen klic tehnične službe

Obljubljen mi je bil tudi **klic tehnične službe**, vendar se ta nikoli ni zgodil.

Po več dneh popolne nedostopnosti, ponavljajočih se klicih in odsotnosti kakršne koli konkretne tehnične obravnave lahko zaključim le:

> **Takšno neprofesionalno ravnanje je nesprejemljivo.**

Od operaterja, ki uporabniku **zaračunava polno ceno storitve**, pričakujem vsaj:

* osnovno komunikacijo,
* ustrezno evidentiranje in spremljanje prijavljene težave,
* tehnično diagnostiko na strani omrežja,
* preverjanje bazne postaje in pripadajočih celic,
* spoštovanje dogovorov in obljubljenih povratnih klicev,
* ter predvsem **dejansko odpravo težave**.

## Povzetek

| Parameter                        | Stanje                              |
| -------------------------------- | ----------------------------------- |
| Modem                            | **ZTE888B – deluje**                |
| SIM-kartica                      | **zaznana**                         |
| 3G                               | **deluje / vzpostavljena povezava** |
| 4G/LTE                           | **ne deluje**                       |
| 5G                               | **ne deluje**                       |
| Lokalna oprema                   | **brez očitnih težav**              |
| Oddaljenost od bazne postaje     | **~200 m**                          |
| Internetni dostop                | **nedelujoč / neuporaben**          |
| Ponastavitve in osnovni postopki | **večkrat izvedeni brez rezultata** |
| Povratni klic tehnične službe    | **ni bil izveden**                  |
| Zahtevana obravnava              | **omrežna/radijska diagnostika**    |

**Težava zato ni več vprašanje uporabniških nastavitev ali ponovnega zagona modema. Potrebna je tehnična obravnava na strani A1 in preverjanje, zakaj je na lokaciji mogoče vzpostaviti 3G povezavo, medtem ko 4G/LTE in 5G ne delujeta.**

Prosím za **konkretno tehnično preverjanje in pisni odgovor**, kaj je bilo preverjeno, kje je bila ugotovljena napaka ter kdaj bo storitev ponovno normalno delovala.
