# 🦠 Zooxanthellae Clade (Algae) Identification Protocol

This document outlines the laboratory procedure for identifying the clade of **Zooxanthellae** (symbiotic algae, primarily *Symbiodiniaceae*) associated with coral tissue. The protocol involves **gDNA extraction** using the ISOLATE II Plant DNA Kit, followed by **PCR** amplification of the **ITS2** region, and visualization via **Agarose Gel Electrophoresis**.

---

## A. gDNA Extraction with ISOLATE II Plant DNA Kit

The ISOLATE II Plant DNA Kit is designed for rapid purification of genomic DNA (gDNA) from plant material.

### 🧪 Kit Features

* **Target:** Plant genomic DNA.
* **Isolation Time:** ~30 minutes.
* **Purity:** High-purity DNA (typical 260/280 ratio 1.6 to 1.9).
* **Lysis Systems:** Contains optimized CTAB and SDS lysis buffers.
* **Components:** Includes **RNase A** to remove RNA.
* **Downstream Applications:** Suitable for PCR, qPCR, cloning, and NGS.
* **Link:** [ISOLATE II Plant DNA Kit Guide](https://www.bioline.com/mwdownloads/download/link/id/1197/nucleic_acid_isolation_guide.pdf)

### 🔬 Plant DNA Isolation Procedure

1.  Pre-heat incubator to **65 ºC**.
2.  Fill a bucket with **ice**.

#### Initial steps for Tissue Samples

1.  Add **0.25mm glass beads** to an empty sterile Eppendorf tube.
2.  Use a blade razer and cut **25 mm** of a coral tissue sample.
3.  Vortex at **max speed for 2 min**.
4.  Transfer **400 µl** of the supernatant to a clean tube.
5.  Centrifuge at **9,000 x g for 3 min**.
6.  Transfer **300 µl** of the supernatant to a clean tube, and discard the pellet.

#### Initial steps for Samples Stored in Acetone

1.  Centrifuge at **max speed for 1 min**.
2.  Remove acetone.
3.  Repeat centrifuge step to remove acetone remains.
4.  Use a filter tip to remove remaining acetone.
5.  Wash pellet in **1 ml FSW** (0.22µ filtered sea water) or **PBS**.
6.  Mix pellet with FSW or PBS.
7.  Centrifuge again.
8.  If a pellet does not form, add another centrifugation step: **5 min at max speed**.
9.  Remove FSW supernatant using a filter tip, taking care not to disturb the pellet.
    > **Note:** If some FSW remains, continue without trying to remove it.

#### Lysis

1.  Add **15 µl Proteinase K** + **30 µl PK digestion buffer** (from Zymo kit - *not included*).
2.  Incubate for **30 min at RT** (Room Temperature).
3.  Vortex.
4.  Spin down.
5.  Centrifuge at **max speed for 2 min**.
6.  Add **400 µl Lysis Buffer PA1** (Pre-heated to **65 ºC**).
7.  Incubate for **25 min at 65 ºC**.

#### Filter Crude Lysate

1.  Transfer lysate to a collection tube with a **purple filter column**.
2.  Centrifuge **11,000 x g, 2 min**.
3.  Collect supernatant to a new tube, discard the pellet.
4.  Add **450 µL Binding Buffer PB**.
5.  Pipette **5 times** up and down to mix.

#### Bind DNA

1.  Load lysate onto a collection tube with a **green filter column** (up to 700 µl).
2.  Centrifuge **11,000 x g, 1 min**.
3.  Discard the flow-through.

#### Wash and Dry Silica Membrane

1.  **1st wash:** Add **400 µL Wash Buffer PAW1**.
2.  Centrifuge **11,000 x g, 1 min**.
3.  Discard the flow-through.
4.  **2nd wash:** Add **700 µL Wash Buffer PAW2**.
5.  Centrifuge **11,000 x g, 1 min**.
6.  Discard the flow-through.
7.  **3rd wash:** Add **200 µL Wash Buffer PAW2**.
8.  Centrifuge **11,000 x g, 2 min**.
9.  Discard the flow-through and collection tube.

#### Elute DNA

1.  Place the **green filter column** in an empty sterile eppendorf tube.
2.  Add **50 µL Elution Buffer PG** (Pre-heat to **65ºC**).
3.  Incubate **65ºC, 5 min**.
4.  Centrifuge **11,000 x g, 1 min**.
5.  **Repeat** DNA elution step (This yields the isolated DNA).
6.  Measure **DNA quantity and ratio** with **NanoDrop**.

---

## B. Polymerase Chain Reaction (PCR)

### 🧬 Primers for ITS2 Amplification

The following primers are used to amplify the **Internal Transcribed Spacer 2 (ITS2)** region, a standard marker for *Symbiodiniaceae* identification.

| Primer Name | Type | Sequence (5' to 3') |
| :---: | :---: | :--- |
| **CS1F** | F (Forward) | ACACTGACGACATGGTTCTACATGTGAATTGCAGAACTCCGTG |
| **CS2R** | R (Reverse) | TACGGTAGCAGAGACTTGGTCTTACTTATATGCTTAAATTCRGCGG |

### 🧪 PCR Reaction Mix (GoTaq® Green Master Mix)

This is the setup for a **50 µl** reaction volume in a 0.2 ml PCR tube.

| Component | Volume | Final Concentration |
| :---: | :---: | :---: |
| GoTaq® Green Master Mix, 2X | **25 µl** | 1X |
| upstream primer (CS1F), 10µM | **5.0 µl** | 1.0 µM |
| downstream primer (CS2R), 10µM | **5.0 µl** | 1.0 µM |
| DNA template | **10.0 µl** | e.g., 52 ng, 55 ng, or 0.46 ng |
| **BSA** | **5.0 µl** | - |
| **H₂O** (Nuclease-free) | **-** | (Volume to bring total to 50 µl) |

### 🌡️ PCR Program (ITS CS - 16/_NGS)

The program is run on a BioRad C1000 Touch Thermal Cycler.

| Cycles | Time | Temp (°C) | Step |
| :---: | :---: | :---: | :---: |
| **1** | 45 sec | **94** | Initial Denaturation |
| 10 | 15 sec | **94** | Denaturation |
| | 15 sec | **50** | Annealing |
| | 30 sec | **72** | Elongation |
| 15 | 15 sec | **94** | Denaturation |
| | 15 sec | **60** | Annealing |
| | 30 sec | **72** | Elongation |
| **1** | 2 min | **72** | Final Extension |

---

## C. Agarose Gel Electrophoresis (1% Gel)

### 🔬 Gel Preparation

1.  Weigh **1 g** of agarose.
2.  Add **100 ml** of **0.5X TBE buffer**.
3.  Microwave for **1 min** to dissolve the agarose fully.
4.  Chill with tap water.
5.  Add **4 µl** of **Red Safe** (DNA stain).
6.  Pour the mixture into the gel formation device with a proper comb.
7.  Wait **45 min** for the gel to solidify.

### ⚡ Electrophoresis Setup

1.  Fill the running device tanks with used **0.5X TBE buffer**.
2.  Place the gel in the device and ensure the wells are submerged/filled with buffer.
3.  Load **2 µl** of **EuRx Perfect 100bp DNA ladder** (100bp-2500bp)  **2 µl** of **1 kb DNA ladder**.
4.  Load **5 µl** of the PCR product sample into the wells.
5.  Plug in the wires.
6.  Set running time to **75 minutes** and voltage to **110 V** (10 V of cm gel).