## 📑 Godišnji izvještaj analize profitabilnosti
### *Profitabilnost linije proizvoda "Auto-odgovornost" u portfelju osiguravajućeg društva za 2025. godinu*

---

### ⚠️ Poslovni problem
Uprava osiguravajućeg društva primijetila je **pad profitabilnosti** u segmentu **auto-odgovornosti**.

**Cilj analize** je:
- identificirati regije i skupine klijenata s najvećim gubicima
- izraditi izvještaj s kompletnim izračunom ključnih pokazatelja
- izvući zaključke i napisati prijedloge za daljnje korake

---

### 🧮 1. Izračun ključnih KPI-eva
Analiza se temelji na sljedećim pokazateljima:

- **Kvota šteta**
- **Frekvencija šteta**
- **Tehnički rezultat**

---

### 🔍 2. Poslovna analitika
Odgovori koje izvještaj treba pružiti:

- *Koji prodajni kanal donosi klijente s najvišom kvotom šteta?*
- *Postoji li korelacija između dobi vozača i visine isplaćenih šteta?*
- *Kako izgleda profitabilnost po regijama i kanalima?*

---

### ⚙️ 3. Generirati izvještaj
Proces izvještavanja potrebno je pripremiti na način da:

- Python skripta pripremi, izračuna i preoblikuje sve podatke potrebne za izvještavanje
- sve tablice s izračunima budu zapisane u Excel i PDF datoteke
- PDF datoteka sadrži zaključak i prijedlog rješenja poslovnog problema

---

## ▦ Tablični prikaz ključnih pokazatelja
<img width="1228" height="765" alt="image" src="https://github.com/user-attachments/assets/f1955060-f1f8-4c69-9a18-044ff9879d72" />

---

## 📊 Grafički prikaz ključnih pokazatelja
<img width="1295" height="734" alt="image" src="https://github.com/user-attachments/assets/b2f85e9e-d241-44ad-bd2d-ebb7b4bd8698" />

---

## 📌 Zaključak odrađene analize

Na temelju analize identificirana su tri kritična segmenta:

1. **Regija Dalmacija (kvota štete: ~127%):** Regija Dalmacija ima najviše gubitaka zbog visoke frekvencije šteta u turističkoj sezoni, pogotovo kada tome pridodamo dobnu skupinu mladih koja statistički izaziva najskuplje i najčešće štete zbog manjka iskustva mladih vozača i veće sklonosti riziku.
2. **Kanal Brokeri (kvota štete: ~101%):** Zbog visokih provizija i tendencije prema rizičnijim klijentima, ovaj kanal zahtjeva stroži underwriting.
3. **Mladi vozači (kvota štete: ~180%):** Skupina s najvećim rizikom. Dokazana je nužnost dobne segmentacije pri određivanju cijena premija.

---

## 📝 Zaključak o profitabilnosti portfelja

### 1. Ukupna ocjena: Stabilna, ali osjetljiva profitabilnost
Na razini cijelog portfelja (10.000 polica), ostvarena je ukupna kvota šteta od približno 78%. U industriji osiguranja ovo se smatra pozitivnim, ali umjerenim rezultatom. Iako je tehnički rezultat pozitivan, važno je napomenuti da preostalih 22% marže mora pokriti hladni pogon (plaće, najam, IT), marketing i provizije posrednika. Portfelj je profitabilan, ali nema velikog prostora za nepredviđene katastrofalne događaje.
### 2. Regija Zagreb: Motor rasta i stup stabilnosti
**Volumen i marža:** Regija Zagreb je najzaslužniji faktor za ukupnu dobit. Zahvaljujući najvećem broju polica i 10% višoj premiji, Zagreb generira tehnički rezultat koji je višestruko veći od svih ostalih regija zajedno.  
**Subvencioniranje rizika:** Dobit ostvarena u regiji Zagreb direktno pokriva gubitke nastale u Dalmaciji i kod rizičnih skupina mladih vozača. Bez stabilnosti zagrebačkog portfelja, društvo bi poslovalo s gubitkom.
### 3. Ključni kanali:
Dok kanal Brokera posluje neprofitabilno (101%), Interna prodajna mreža (IPM) i Web su kanali koji osiguravaju najkvalitetniji ulaz klijenata. IPM pokazuje najbolje rezultate jer vlastiti agenti bolje poznaju klijente i pažljivije vrše procjenu rizika pri samom ugovaranju.
### 4. Finalna poruka:
Poslovanje je jako u Zagrebu, ali ranjivo u ostalim regijama. Strategija za iduću godinu trebala bi biti usmjerena na očuvanje dominantne pozicije u Zagrebu uz istovremeno uvođenje strožih "malusa" za kritične segmente (Dalmacija ljeti, mladi vozači) kako bi se smanjio odlijev profita.

---

## 💡 Poslovne preporuke
* **Korekcija cijena:** Uvođenje regionalnih doplataka za Dalmaciju i malusa za mlade vozače.
* **Optimizacija kanala:** Revizija ugovora s brokerima i uvođenje bonusa temeljenih na profitabilnosti, umjesto samo na volumenu prodaje.
* **Dinamičko izvještavanje:** Automatiziranje priloženog izvještaja za mjesečno praćenje trendova kako bi se reagiralo prije kritičnih razdoblja.

---

## 📂 Dokumentacija
* 📑 [Pregledaj PDF izvještaj](Izvjestaj_profitabilnost.pdf) - Detaljan tehnički dokument
* 📊 [Preuzmi Excel tablice](Izvjestaj_profitabilnost.xlsx) - Strukturirani podaci
* 🐍 [Pogledaj Python kod (Jupyter Notebook)](Profitabilnost_auto_odgovornosti_u_osiguranju.ipynb) - Cijeli proces obrade podataka
