# A1 Slovenija – Tehnična pritožba / Technical Complaint

Dokumentacija tehnične pritožbe zoper operaterja A1 Slovenija zaradi nedelovanja 4G/LTE in 5G mobilnega internetnega dostopa.

Documentation of a technical complaint against telecom operator A1 Slovenia regarding persistent 4G/LTE and 5G mobile broadband service outage.

---

## 📄 Različice dokumenta / Document Versions

* 🇸🇮 **Slovenska različica:** [A1_pritozba.md](A1_pritozba.md)  
  *Podrobna pritožba s tehničnimi zahtevami za omrežno diagnostiko in pregled postopkov podpore.*
* 🇬🇧 **English Version:** [A1_pritozba_en.md](A1_pritozba_en.md)  
  *Detailed technical complaint with network diagnostic checklist and support escalation points.*

---

## 📌 Kratek povzetek / Quick Summary

| Parameter | Stanje / Status | Opis / Description |
| :--- | :--- | :--- |
| **Operater / Provider** | A1 Slovenija | Mobilni internet / Mobile Broadband |
| **Modem** | ZTE888B | Deluje brezhibno / Operates normally |
| **SIM kartica / SIM Card** | Zaznana / Detected | Prepoznana v modemu / Recognized in modem |
| **3G povezava** | **Vzpostavljena / Active** | Povezava v 3G deluje / 3G connection works |
| **4G / LTE** | ❌ **Nedelujoče / Down** | Povezava se ne vzpostavi / Fails to attach |
| **5G NR** | ❌ **Nedelujoče / Down** | Povezava se ne vzpostavi / Fails to attach |
| **Oddaljenost / Distance** | ~200 m | Od bazne postaje / From serving base station |
| **Internetni dostop** | **Neuporaben / Unusable** | Praktično brez dostopa / Minimal-to-no throughput |
| **Zahteva / Requirement** | Tehnična diagnostika (RAN/NOC) | Omrežno preverjanje bazne postaje in naročniškega profila |

---

## 🎯 Namen / Purpose

Ta dokumentacija je pripravljena kot strukturirana tehnična eskalacija za omrežno ekipo (NOC / RAN) operaterja A1:

1. **Izključitev lokalnih napak:** Potrjeno je, da modem in SIM delujeta (3G deluje, lokalne ponastavitve večkrat izvedene).
2. **Tehnična diagnostika:** Zahteva za preverjanje bazne postaje (LTE/5G celice), radijskih parametrov (RSRP, RSRQ, SINR) in zavrnitvenih kod ob poskusu registracije (`reject cause`).
3. **Eskalacija podpore:** Pritožba glede obravnave s strani klicnega centra in neizvedenega obljubljenega klica tehnične službe.
