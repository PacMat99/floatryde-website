# floatryde-website
Sito web in Jekyll per FloatRyde

Ecco la struttura strategica e il layout per il sito one-page Jekyll, ottimizzata per **tutelare la proprietà intellettuale (IP)**, valorizzare i dati di mercato reali  e sfruttare gli screenshot dell'app Flutter senza bisogno di video o dettagli hardware sensibili.

---

## 1. Struttura a Blocchi "IP-Safe" (Wireframe Logico)

Questa sequenza sposta l'attenzione dall'architettura elettronica interna al problema di mercato , all'approccio metodologico (ISO) e al valore per i brand :

```
┌────────────────────────────────────────────────────────┐
│ 1. HERO SECTION                                        │
│    Headline ad alto impatto + Mockup App + Badge       │
├────────────────────────────────────────────────────────┤
│ 2. IL PROBLEMA & IL VUOTO DI MERCATO                   │
│    Soggettività vs Sistemi Race da 1.500€+             │
├────────────────────────────────────────────────────────┤
│ 3. LA SOLUZIONE METODOLOGICA (Black Box)               │
│    Principio di funzionamento ad alto livello + ISO    │
├────────────────────────────────────────────────────────┤
│ 4. ESPERIENZA DIGITALE & UI SHOWCASE                   │
│    Screenshot App (Dashboard, Fork, Wheels, Feedback)  │
├────────────────────────────────────────────────────────┤
│ 5. VALIDAZIONE DI MERCATO (I Dati del Sondaggio)       │
│    Metriche chiave: 73% interesse, N=328, B2B OEM      │
├────────────────────────────────────────────────────────┤
│ 6. CONTATTO & RICHIESTA DOSSIER TECNICO / NDA          │
│    Profilo Ingegneristico + Form / Contatto diretto    │
└────────────────────────────────────────────────────────┘

```

---

## 2. Copywriting & Messaggistica delle Sezioni

### Blocco 1: Hero Section (Above the Fold)

* **Badge:** `PROTOTIPO FUNZIONANTE • METODOLOGIA VALIDATA`
* **Headline:** L'Analisi Dinamica e il Comfort Ciclistico Diventano Oggettivi.
*  **Sottotitolo:** FloatRyde colma il divario tra le sensazioni empiriche del rider e la complessità inaccessibile dei sistemi di telemetria tradizionali. Una piattaforma integrata per l'ottimizzazione del setup basata su standard scientifici.
* **Visual:** Mockup smartphone affiancati (`smartphone_dashboard.png` + `smartphone_feedback.png`).
* **CTA Primaria:** `[ Scopri la Metodologia ]` (Scroll)
* **CTA Secondaria:** `[ Richiedi Dossier Tecnico ]`

### Blocco 2: Il Vuoto di Mercato (The Gap)

* **Concetto Chiave:** Perché l'industria sta perdendo valore percepito sul cliente finale.
* **Contenuto a 3 Colonne:**
  1. *Il Limite delle Sensazioni:* Il 74% dei praticanti vorrebbe regolare meglio assetto e pressioni ma non ha riferimenti oggettivi.
  2. *La Telemetria Tradizionale:* Sistemi da oltre 1.500€ pensati esclusivamente per team corse, complessi e non plug-and-play.
  3. *L'Approccio FloatRyde:* Valutazione scientifica del disturbo vibrazionale e suggerimenti di taratura chiari, accessibili ed efficaci.

### Blocco 3: Come Funziona (Architettura Funzionale "Black Box")

> *Nota di riservatezza:* **Non citare** modelli di MCU, integrati, sigle IMU specifiche, schemi elettrici o costi BOM dettagliati.

Parla di **funzioni di sistema**:
* **Headline:** Architettura Modulare e Standard Scientifici 
* **I 3 Pilastri Funzionali:**
* **Rilevazione Multi-Punto Sincronizzata:** Acquisizione wireless del comportamento dinamico e delle oscillazioni sui nodi chiave della bicicletta.
* **Analisi Standardizzata (ISO 2631 / ISO 5349):** Normalizzazione dei dati di accelerazione e rotazione per quantificare scientificamente l'impatto sul sistema mano-braccio e sul corpo intero.
* **Algoritmo Predittivo di Setup:** Traduzione automatica dei parametri fisici registrati in raccomandazioni pratiche (click di ritorno, precarico, pressioni gomme).

### Blocco 4: UI Showcase & User Experience

Inserisci gli screenshot effettivi dell'app Flutter con layout a carosello o griglia pulita:

* **Configurazione Assetto (`smartphone_fork_screen.png`):** Gestione immediata di corsa, tipologia molla/aria e idraulica.
* **Setup Ruote & Pressioni (`smartphone_wheels_screen.png`):** Profilazione cerchi e sezioni pneumatici in PSI/BAR.
* **Output & Feedback Rapido (`smartphone_feedback.png`):** La notifica decisionale che guida l'utente alla regolazione senza perdersi in grafici complessi.

### Blocco 5: Market Validation & Opportunità B2B

Mostra la solidità dell'indagine condotta per incuriosire R&D e Product Manager:

* **73% Propensione Positiva:** Emersa dall'indagine campionaria ($N = 328$, margine $\pm 5,4\%$).
* **55% Core Demographic:** Rispondenti nella fascia 35–54 anni (il target con maggiore propensione di spesa per componentistica ed E-Bike).
* **Ambiti di Integrazione B2B:**
  * *Produttori Sospensioni & Telai:* Data intelligence reale su assorbimento e risposta dinamica sul campo.
  * *E-Bike OEM:* Potenziale integrazione nel firmware/elettronica di bordo per diagnosi predittiva e supporto all'utente.

### Blocco 6: Contatto & Richiesta Informazioni Riservate

* **Posizionamento Personale:** *Project Lead & Embedded Systems Developer* (o *Founder & Hardware/Software Engineer*).
* **CTA di Riservatezza:** *"I dettagli architetturali, i dataset di test e i modelli matematici proprietari sono disponibili per team R&D previa sottoscrizione di accordo di riservatezza (NDA)."*
* **Pulsanti:** `[ Richiedi Scheda Tecnica / NDA ]`, `[ Salva Contatto VCF ]`, `[ Profilo LinkedIn ]`.

---

## 3. UI, Stile Visivo & Palette

Coerente con il tema **Electric Velocity** dell'app Flutter:

| Token UI | Valore HEX | Utilizzo |
| --- | --- | --- |
| **Primary Dark** | `#0D1B2A` | Testo principale, titoli H1/H2, card a contrasto |
| **Action Blue** | `#2962FF` | Bottoni CTA principali, badge attivi, linee d'accento |
| **Accent Cyan** | `#00B0FF` | Icone tecniche, bordi evidenziati, hover states |
| **Surface Ice** | `#F0F2F5` | Sfondi sezioni alternate, box e card di supporto |
| **Background** | `#FFFFFF` | Sfondo pagina principale (massima leggibilità outdoor) |
| **Outline / Border** | `#CFD8DC` | Separatori sottili, bordi card e input |

* **Font Titoli:** `Inter` o `Space Grotesk` (700 Bold / Semi-Bold).
* **Font Testo:** `Roboto` o `Inter` (uguale all'app).

---

## 4. Mobile & Fair Optimization (Senza Video)

1. **Asset WebP Leggeri:** Converti i 4 screenshot PNG in `.webp` con qualità 85% e risoluzione scalata al 50% per mobile (peso totale immagini < 350 KB).
2. **Zero Dipendenze Esterne:** Un singolo file CSS statico compilato da Jekyll (nessun framework JS pesante, nessun player esterno come YouTube o Vimeo che rallenterebbe il caricamento sotto copertura fiera instabile).
3. **Download Diretto VCard (`.vcf`):** Inserisci nel pulsante di contatto il download immediato della scheda contatto completa di link al sito e note sul progetto.

---

## 5. Setup Jekyll Consigliato

Per mantenere il processo veloce senza partire da zero:

1. **Base consigliata:** Usa un template minimalista statico (es. **Agency Jekyll** o un template custom basato su una singola pagina HTML + Tailwind CSS compilato).
2. Struttura del repository GitHub Pages:
```
.
├── _config.yml
├── index.html
├── assets/
│   ├── css/style.css
│   ├── img/ (screenshot in .webp)
│   └── contact.vcf

```
