<div align="center">

⭐ **Se ti piace questo progetto, metti una stella al repository!** ⭐ <br>
------- 🇬🇧 **[Readme in English][readme-en-url]** 🇬🇧 --------

<hr />
</div>

<div align="center">
<h2>FreeClock 3D Print</h2>

[![3D Printabile](https://img.shields.io/badge/3D_Stampabile-FDM-orange?logo=3dprint&logoColor=white)](#)
[![Senza supporti](https://img.shields.io/badge/Supporti-Non_necessari-brightgreen)](#)
[![Senza AMS](https://img.shields.io/badge/AMS-Non_richiesto-blue)](#)
[![Specchiabile](https://img.shields.io/badge/Stampa-Specchiabile-purple)](#)

<hr/>

<p><em>Questo modello fa parte del progetto <a href="https://github.com/Matese-Makers/FreeClock"><strong>FreeClock</strong></a> — un orologio smart open source, facile da assemblare, con scocca stampabile in 3D e un'app mobile per la gestione. Costruisci il tuo e unisciti al progetto!</em></p>

</div>

## 💡 Panoramica

FreeClock 3D Print contiene tutti i file **STL** della scocca stampabile in 3D di FreeClock, insieme al file sorgente **CAD** e al progetto **3MF** pronto per lo slicing.\
La scocca è progettata per alloggiare l'elettronica **FreeClock ESP32** ed è stata ingegnerizzata per essere semplice da stampare e rapida da assemblare, anche se sei alle prime armi con la stampa 3D.

## ✨ Caratteristiche

- 🚫 **Senza supporti** — ogni parte è orientata per stampare senza supporti, riducendo sprechi e post-lavorazione
- 🧩 **Facile da stampare e assemblare** — geometrie semplici e accoppiamenti puliti, si monta in pochi minuti
- 🎨 **Multicolore senza AMS** — le parti sono suddivise per colore, così puoi ottenere un risultato multicolore anche senza un sistema multimateriale
- 🪞 **Stampa specchiata** — i componenti possono essere stampati specchiati per personalizzare l'orientamento della scocca
- 📦 **Design modulare** — la scocca è divisa in più parti che stampano in piano e si incastrano tra loro
- 🖨️ **FDM friendly** — progettato per stampanti FDM standard con ugello da 0,4 mm e materiali comuni (PLA / PETG)

## 🗂️ Struttura del Repository

```
FREECLOCK-model/
├── 3MF/
│   └── freeclock.3mf          # File di progetto pronto per lo slicing
├── CAD/
│   └── FREECLOCK.f3z          # File sorgente Fusion 360
├── STL/
│   ├── a v3.stl               # Parte A (variante v3)
│   ├── b v3.stl               # Parte B (variante v3)
│   ├── buttom.stl             # Base inferiore
│   ├── display cover.stl      # Cover del display
│   ├── frame.stl              # Cornice frontale
│   ├── main body.stl          # Corpo principale / scocca
│   └── retro.stl              # Pannello posteriore
├── LICENSE
├── README.md
└── README.it.md
```

## 🧱 Componenti

Tutti i file STL si trovano nella cartella [`STL/`](STL/).

| File | Descrizione |
|------|-------------|
| [`main body.stl`](STL/main%20body.stl) | Corpo principale (scocca) che alloggia l'elettronica |
| [`buttom.stl`](STL/buttom.stl) | Base inferiore della scocca |
| [`retro.stl`](STL/retro.stl) | Pannello posteriore |
| [`frame.stl`](STL/frame.stl) | Cornice frontale del display |
| [`display cover.stl`](STL/display%20cover.stl) | Cover / maschera del display |
| [`a v3.stl`](STL/a%20v3.stl) | Parte decorativa / strutturale A (v3) |
| [`b v3.stl`](STL/b%20v3.stl) | Parte decorativa / strutturale B (v3) |

### 📐 Sorgente CAD

Il file sorgente Fusion 360 è disponibile in [`CAD/FREECLOCK.f3z`](CAD/FREECLOCK.f3z) per chiunque voglia modificare o remixare il design.

### 📦 Progetto 3MF

Un file di progetto 3MF pronto per lo slicing è disponibile in [`3MF/freeclock.3mf`](3MF/freeclock.3mf), pre-configurato con l'orientamento dei pezzi e le impostazioni consigliate.

## 🚀 Come Iniziare

### Cosa ti serve

- 🖨️ Una **stampante 3D FDM** (ugello da 0,4 mm)
- 🧵 Filamento **PLA** o **PETG** (uno o più colori a tua scelta)
- 🪛 Uno **slicer** (PrusaSlicer, OrcaSlicer, Cura o equivalente)

### Impostazioni di stampa consigliate

> **Nota:** questi sono valori di partenza testati; adattali alla tua stampante e al tuo filamento.

- **Altezza layer:** 0,2 mm
- **Perimetri (pareti):** 3
- **Riempimento:** 15–20%
- **Supporti:** ❌ nessuno
- **Adesione al piatto:** brim consigliato per i pezzi più piccoli

### Come stampare

1. **Scarica** o clona il repository:

   ```bash
   git clone https://github.com/Danzaywer/FREECLOCK-model.git
   cd FREECLOCK-model
   ```

2. **Opzione A — Usa il 3MF:** Apri [`3MF/freeclock.3mf`](3MF/freeclock.3mf) direttamente nel tuo slicer per una configurazione già pronta.

3. **Opzione B — Usa gli STL:** Importa i singoli file dalla cartella [`STL/`](STL/) nel tuo slicer, orientali in piano (nessun supporto necessario) e affetta.

4. **Stampa** ogni componente e procedi con il montaggio.

### 🎨 Stampa multicolore (senza AMS)

Poiché la scocca è suddivisa in più parti, puoi assegnare un colore di filamento diverso a ciascun componente e ottenere un risultato multicolore **senza** bisogno di un AMS / sistema multimateriale: stampa semplicemente i pezzi separatamente con il filamento desiderato.

### 🪞 Stampa specchiata

I componenti possono essere stampati **specchiati** direttamente dallo slicer, utile per ribaltare l'orientamento della scocca in base alle tue esigenze.

## 📟 Elettronica Compatibile

- **FreeClock ESP32** — la scheda e il display si alloggiano all'interno della scocca
- Per il firmware e l'app di gestione, consulta il [progetto principale FreeClock](https://github.com/Matese-Makers/FreeClock)

## 🤝 Contribuire

I contributi sono benvenuti! Ecco come puoi aiutare:

1. **Fork** del repository
2. **Crea** un branch per la tua modifica (`git checkout -b feature/mia-modifica`)
3. **Commit** delle tue modifiche (`git commit -m 'Aggiungo mia modifica'`)
4. **Push** del branch (`git push origin feature/mia-modifica`)
5. **Apri** una Pull Request

Se hai stampato la scocca, condividi una foto o suggerisci miglioramenti al modello! Per segnalare problemi o proporre nuove varianti, [apri una issue](https://github.com/Danzaywer/FREECLOCK-model/issues).

## 📄 Licenza

Questo progetto è rilasciato sotto la **GNU Affero General Public License v3.0 (AGPL-3.0)**.

Ciò significa che sei libero di usare, modificare e distribuire questi file, a condizione che:
- Qualsiasi versione modificata resa disponibile su una rete debba essere rilasciata con la stessa licenza
- Il codice sorgente / file originali devono essere resi disponibili agli utenti che interagiscono con il progetto su una rete

Per il testo completo della licenza, consulta il file [LICENSE](LICENSE).

<!--URL for Links-->
[readme-en-url]: README.md
[readme-it-url]: README.it.md
