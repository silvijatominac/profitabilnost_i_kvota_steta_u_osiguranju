## 📊 Godišnji izvještaj analize profitabilnosti
### *Profitabilnost linije proizvoda "Auto-odgovornost" u portfelju osiguravajućeg društva za 2025. godinu*

---

### 🎯 Poslovni problem
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
- **Prosječan trošak štete**

---

### 📈 2. Poslovna analitika
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

## 🔍 Zaključak odrađene analize

Na temelju analize identificirana su tri kritična segmenta:

1. **Regija Dalmacija (kvota štete: ~127%):** Regija Dalmacija ima najviše gubitaka zbog visoke frekvencije šteta u turističkoj sezoni, pogotovo kada tome pridodamo dobnu skupinu mladih koja statistički izaziva najskuplje i najčešće štete zbog manjka iskustva mladih vozača i veće sklonosti riziku.
2. **Kanal Brokeri (kvota štete: ~101%):** Zbog visokih provizija i tendencije prema rizičnijim klijentima, ovaj kanal zahtjeva stroži underwriting.
3. **Mladi vozači (kvota štete: ~180%):** Skupina s najvećim rizikom. Dokazana je nužnost dobne segmentacije pri određivanju cijena premija.

---

## 💡 Poslovne preporuke
* **Korekcija cijena:** Uvođenje regionalnih doplataka za Dalmaciju i malusa za mlade vozače.
* **Optimizacija kanala:** Revizija ugovora s brokerima i uvođenje bonusa temeljenih na profitabilnosti, umjesto samo na volumenu prodaje.
* **Dinamičko izvještavanje:** Automatiziranje priloženog izvještaja za mjesečno praćenje trendova kako bi se reagiralo prije kritičnih razdoblja.

---

## 📂 Dokumentacija
* [PDF Izvještaj](Izvjestaj_profitabilnost.pdf) - Detaljan tehnički dokument
* [Excel Tablice](Izvjestaj_profitabilnost.xlsx) - Strukturirani podaci
* [Jupyter Notebook](analiza_osiguranja.ipynb) - Cijeli proces obrade podataka
