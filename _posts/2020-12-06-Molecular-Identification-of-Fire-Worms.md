## 📖 Project Overview  
This repository documents the molecular identification of fire worms (*Hermodice carunculata* and *Eurythoe complanata*) using DNA extraction, PCR amplification, gel electrophoresis, and sequencing.  
The goal is to:  
- Establish reliable gDNA extraction protocols for polychaetes.  
- Test Folmer and Geller COI primers for amplification efficiency.  
- Sequence PCR products and confirm species identity via BLAST analysis.  
- Provide reproducible lab notes and results for future reference.  

---

## 🧪 Sample Preparation  
- **Extraction date:** 27.1.25  
- **Kit used:** Quick DNA/RNA Miniprep Plus Kit (Zymo Research)  
- **Storage:** Worms stored at -20 °C in EtOH  
- **Steps:**  
  - Washed in 1X PBS several times  
  - Homogenized in 800 µl DNA/RNA shield  
  - 300 µl extracted immediately, 500 µl stored at -20 °C  
  - Added 0.25 mm glass beads, vortexed 1 min at 2000 rpm  
  - Proteinase K digestion (30 µl buffer + 15 µl enzyme, 30 min RT)  
  - Centrifuged, supernatant transferred, lysis and wash steps performed  
  - DNA eluted in 100 µl DNase/RNase‑free water (55 °C incubation, 5 min)  

---

## 📊 NanoDrop Results  

| Sample          | Date     | Conc. (ng/µl) | 260/280 | 260/230 |
|-----------------|----------|---------------|---------|---------|
| J1              | 12/6/23  | 98.3          | 1.91    | 2.05    |
| J18             | 28/5/23  | 32.3          | 1.98    | 1.64    |
| J16             | 12/6/23  | 162.4         | 1.93    | 2.10    |
| Small worms     | 7/10/24  | 128.7         | 1.96    | 2.28    |
| J15             | 14/1/25  | 162.4         | 1.93    | 2.40    |
| 1‑02            | 14/1/25  | 95.0          | 1.97    | 1.96    |

---

## 🧬 DNA Template Dilutions  

| Sample          | Dilution | Final Conc. (ng/µl) |
|-----------------|----------|----------------------|
| J1              | 1:5      | 19.66               |
| J18             | 1:1.5    | 21.53               |
| J16             | 1:8      | 20.3                |
| Small worms     | 1:6      | 21.45               |
| J15             | 1:8      | 20.3                |
| 1‑02            | 1:5      | 23.75               |
| Control (*Stylophora pistillata*) | — | 19.0 |
| NTC             | —        | —                   |

---

## 🔬 Primers  

- **Folmer et al., 1994** (Tm: 55 °C)  
  - LCO1490: `5'-ggtcaacaaatcataaagatattgg-3'`  
  - HC02198: `5'-taaacttcagggtgaccaaaaaatca-3'`  

- **Degenerative Primers – Geller et al., 2013** (Tm: 54 °C)  
  - jgLCO1490: `5'-TITCIACIAAYCAYAARGAYATTGG-3'`  
  - jgHCO2198: `5'-TAIACYTCIGGRTGICCRAARAAYCA-3'`  

---

## ⚗️ PCR Setup  

**Reaction volume: 25 µl**  

| Component                   | Volume (1X) | Final Conc. |
|-----------------------------|-------------|-------------|
| GoTaq® Green Master Mix (2X)| 12.5 µl     | 1X          |
| Upstream primer (10 µM)     | 1.5 µl      | 0.6 µM      |
| Downstream primer (10 µM)   | 1.5 µl      | 0.6 µM      |
| H₂O                         | 8.5 µl      | —           |
| DNA template (~20 ng)       | 1.0 µl      | —           |

**Cycler program (Applied Biosystems SimpliAmp):**  
- Initial denaturation: 94 °C, 2 min  
- 34 cycles:  
  - 94 °C, 45 s  
  - 49 °C, 30 s  
  - 72 °C, 1 min  
- Final extension: 72 °C, 3 min  

---

## 🧫 Gel Electrophoresis  
- **Gel:** 1% agarose in 0.5X TBE + RedSafe  
- **Run:** 40 min at 110 V  
- **Ladders:** 1 kb Perfect Plus, 100 bp Perfect DNA ladder  
- **Lane order:**  
  - Lanes 3–10: Folmer primers (J1, J18, J16, Small worms, J15, 1‑02, Stylophora, NTC)  
  - Lanes 11–18: Degenerative primers (same sample set)  
![gel](https://univstaff-my.sharepoint.com/:i:/r/personal/rbober_univ_haifa_ac_il/Documents/Documents/GitHub/RachelBober_Lab_Notebook/images/Fire%20worms%20gel%2028.1.25.png?csf=1&web=1&e=Jf0aBD)
---

## 📑 Sequencing Setup  

| Sample          | Service                     | Primer    | Size | Conc. (ng/µl) |
|-----------------|-----------------------------|-----------|------|---------------|
| Fireworm J1     | PCR clean‑up + sequencing   | djLCO1490 | 700  | 4             |
| Fireworm J1     | Sequencing                  | djHCO2198 | 700  | 4             |
| Fireworm J18    | PCR clean‑up + sequencing   | djLCO1490 | 700  | 4             |
| Fireworm J18    | Sequencing                  | djHCO2198 | 700  | 4             |
| Fireworm J16    | PCR clean‑up + sequencing   | djLCO1490 | 700  | 4             |
| Fireworm J16    | Sequencing                  | djHCO2198 | 700  | 4             |
| Fireworm J15    | PCR clean‑up + sequencing   | djLCO1490 | 700  | 4             |
| Fireworm J15    | Sequencing                  | djHCO2198 | 700  | 4             |
| Fireworm 1‑02   | PCR clean‑up + sequencing   | djLCO1490 | 700  | 4             |
| Fireworm 1‑02   | Sequencing                  | djHCO2198 | 700  | 4             |
| Small fireworm  | PCR clean‑up + sequencing   | djLCO1490 | 700  | 4             |
| Small fireworm  | Sequencing                  | djHCO2198 | 700  | 4             |

---

## 🧾 BLAST Results  

### Sample J15  
- **Top hit:** *Hermodice carunculata* (marine fireworm) – 98.79% identity, 96% coverage  
- Other matches: *Sabella spallanzanii* (97.71%), multiple *Hermodice carunculata* vouchers (99–100% identity)  

### Sample 1‑02  
- **Top hit:** *Eurythoe complanata* – 98.49% identity, 96% coverage  
- Other matches: Amphinomidae sp. (99.84%), *Eurythoe cf. complanata* isolates (98–99%)  

---

## 🔁 How to Reproduce  

1. **Sample Collection & Storage**  
   - Collect fire worms and store at -20 °C in ethanol.  

2. **DNA Extraction**  
   - Use Quick DNA/RNA Miniprep Plus Kit.  
   - Homogenize tissue in DNA/RNA shield with glass beads.  
   - Perform Proteinase K digestion, lysis, and wash steps.  
   - Elute DNA in DNase/RNase‑free water.  

3. **Quality Check**  
   - Measure DNA concentration and purity using NanoDrop.  
   - Dilute samples to ~20 ng/µl for PCR.  

4. **PCR Amplification**  
   - Prepare 25 µl reactions with GoTaq® Green Master Mix.  
   - Use Folmer or Geller COI primers.  
   - Run thermal cycling program 94 °C → 49 °C