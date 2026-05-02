# profitabilnost_i_kvota_steta_u_osiguranju
Ovaj Python projekt sadrži izračun profitabilnosti i kvota šteta u osigurateljnoj industriji koristeći izmišljene podatke

## 📊 Mjesečni izvještaj analize profitabilnosti
### *Profitabilnost i kvota šteta u osiguranju*

---

### 🎯 Poslovni problem
Uprava osiguravajućeg društva primijetila je **pad profitabilnosti** u segmentu **auto-odgovornosti**.

**Cilj analize** je:
- identificirati regije i skupine klijenata s najvećim gubicima  
- automatizirati mjesečno slanje izvještaja (PDF / Excel) menadžmentu.

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
- *Kako izgleda profitabilnost po regijama?*

---

### ⚙️ 3. Automatizacija izvještaja
Proces izvještavanja potrebno je automatizirati tako da:

- svi izračuni i grafovi budu zapisani u Excel datoteku
- iz Excela se automatski generira PDF izvještaj
- Excel i PDF budu svaki mjesec automatski poslani na definirane mail adrese
