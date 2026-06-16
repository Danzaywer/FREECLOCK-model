<div align= "center">

⭐ **Se ti piace questo progetto, metti una stella al repository!** ⭐ <br>
------- 🇬🇧 **[Readme in English][readme-en-url]** 🇬🇧 --------

<hr />
</div>

<div align="center">
<h2>FreeClock 3D Print</h2>

[![3D Printable](https://img.shields.io/badge/3D_Printable-FDM-orange?logo=3dprint&logoColor=white)](#)
[![No Supports](https://img.shields.io/badge/Supporti-Non_necessari-brightgreen)](#)
[![No AMS](https://img.shields.io/badge/AMS-Non_richiesto-blue)](#)
[![Mirror](https://img.shields.io/badge/Stampa-Speculare-purple)](#)

<hr/>

<a href="https://github.com/Matese-Makers/FreeClock">
<img alt="Progetto FreeClock" src="./gh-assets/FreeClock_project.png" width="200">
</a>

<p><em>Questo modello fa parte del progetto <a href="https://github.com/Matese-Makers/FreeClock"><strong>FreeClock</strong></a> — un orologio smart open source facile da assemblare, con un guscio stampabile in 3D e un'app mobile per la gestione. Costruiscilo anche tu ed entra a far parte del progetto!</em></p>

</div>

## 💡 Overview

FreeClock 3D Print contiene tutti i file **STL** del guscio stampabile in 3D di FreeClock.\
Il case è pensato per ospitare l'elettronica **FreeClock ESP32** ed è stato progettato per essere semplice da stampare e veloce da assemblare, anche per chi è alle prime esperienze con la stampa 3D.

## ✨ Caratteristiche

- 🚫 **Senza supporti** — ogni componente è orientato per stampare senza supporti, riducendo gli scarti e il post-processing
- 🧩 **Facile da stampare e assemblare** — geometrie semplici e incastri puliti, si monta in pochi minuti
- 🎨 **Multicolore senza AMS** — i pezzi sono separati per colore, così puoi ottenere un risultato multicolore anche senza sistema multimateriale
- 🪞 **Stampa speculare** — i componenti possono essere stampati in versione speculare per personalizzare l'orientamento del case
- 📦 **Design modulare** — il guscio è suddiviso in più parti che stampano in piano e si combinano tra loro
- 🖨️ **Compatibile FDM** — pensato per stampanti FDM standard con ugello da 0.4 mm e materiali comuni (PLA / PETG)

## 🧱 Componenti

Tutti i file STL si trovano nella cartella [`stl/`](stl/). I numeri indicano l'ordine consigliato di stampa e assemblaggio.

| # | File | Descrizione |
|---|------|-------------|
| 1 | [`1_box.stl`](stl/1_box.stl) | Corpo principale (scocca) che racchiude l'elettronica |
| 2 | [`2_bottom.stl`](stl/2_bottom.stl) | Base inferiore del case |
| 3 | [`3_top.stl`](stl/3_top.stl) | Coperchio superiore |
| 4 | [`4_back.stl`](stl/4_back.stl) | Pannello posteriore |
| 5 | [`5_display_mask.stl`](stl/5_display_mask.stl) | Maschera del display |
| 6 | [`6_display_frame.stl`](stl/6_display_frame.stl) | Cornice frontale del display |

## 🚀 Getting Started

### Cosa ti serve

- 🖨️ Una **stampante 3D FDM** (ugello da 0.4 mm)
- 🧵 Filamento **PLA** o **PETG** (uno o più colori a piacere)
- 🪛 Uno **slicer** (PrusaSlicer, OrcaSlicer, Cura o equivalenti)

### Impostazioni di stampa consigliate

> **Nota:** sono valori di partenza testati; adattali alla tua stampante e al tuo filamento.

- **Altezza layer:** 0.2 mm
- **Perimetri (pareti):** 3
- **Riempimento:** 15–20%
- **Supporti:** ❌ nessuno
- **Adesione piatto:** brim consigliato per i pezzi più piccoli

### Come stampare

1. **Scarica** o clona il repository:

   ```bash
   git clone https://github.com/luigirossidev/freeclock-3dprint.git
   cd freeclock-3dprint
   ```

2. **Importa** i file STL dalla cartella [`stl/`](stl/) nel tuo slicer.
3. **Orienta** i pezzi come da anteprima (sono già pensati per stampare senza supporti) ed esegui lo slicing.
4. **Stampa** ogni componente e procedi con l'assemblaggio seguendo l'ordine numerico.

### 🎨 Stampa multicolore (senza AMS)

Dato che il case è suddiviso in più parti, puoi assegnare un colore di filamento diverso a ciascun componente e ottenere un risultato multicolore **senza** bisogno di un sistema AMS / multimateriale: basta stampare i pezzi separatamente con il filamento desiderato.

### 🪞 Stampa speculare

I componenti possono essere stampati in versione **speculare** (mirror) direttamente dallo slicer, utile per invertire l'orientamento del case in base alle tue esigenze.

## 📟 Elettronica compatibile

- **FreeClock ESP32** — la scheda e il display alloggiano all'interno del guscio
- Per il firmware e l'app di gestione fai riferimento al [progetto principale FreeClock](https://github.com/Matese-Makers/FreeClock)

## 🤝 Contribuire

I contributi sono benvenuti! Ecco come puoi aiutare:

1. **Fai il fork** del repository
2. **Crea** un branch per la tua modifica (`git checkout -b feature/la-mia-modifica`)
3. **Committa** le tue modifiche (`git commit -m 'Aggiunta la mia modifica'`)
4. **Pusha** il branch (`git push origin feature/la-mia-modifica`)
5. **Apri** una Pull Request

Se hai stampato il case, condividi una foto o suggerisci migliorie al modello! Per segnalare problemi o proporre nuove varianti, [apri una issue](https://github.com/luigirossidev/freeclock-3dprint/issues).

## 📄 Licenza

Questo progetto è rilasciato sotto la licenza **GNU Affero General Public License v3.0 (AGPL-3.0)**.

Questo significa che sei libero di usare, modificare e distribuire questi file, a condizione che:
- Qualsiasi versione modificata resa disponibile tramite rete deve essere rilasciata con la stessa licenza
- Il codice sorgente / i file originali devono essere resi disponibili agli utenti che interagiscono con il progetto tramite rete

Per il testo completo della licenza, consulta il file [LICENSE](LICENSE).

<!--URL for Links-->
[readme-en-url]: README.md
[readme-it-url]: README.it.md
