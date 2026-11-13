# 📁 FileOrganizer & NumPy Image Automation

Progetto sviluppato in **Python** e **NumPy** nell'ambito del percorso di formazione in Artificial Intelligence e Data Analytics. L'obiettivo del progetto è combinare l'automazione del file system, la gestione di interfacce a riga di comando (CLI) e l'analisi di immagini basata su array numerici.

---

## 🛠️ Struttura del Progetto

Il progetto si articola in tre sezioni principali (Step):

### Step 1: Organizzazione Automatica dei File (`Fileorganizer.ipynb`)
* **Obiettivo:** Gestione dei path (assoluti e relativi) e scansione del file system.
* **Funzionalità:** 
  * Creazione automatica di sottocartelle di destinazione (`audio`, `docs`, `images`).
  * Smistamento ordinato dei file presenti nella cartella di origine.
  * Generazione di un file di riepilogo (`recap.csv`) contenente nome, tipologia e dimensione in byte di ciascun file elaborato.

### Step 2: Interfaccia a Riga di Comando - CLI (`Addfile.py`)
* **Obiettivo:** Sviluppo di uno script eseguibile da terminale tramite la libreria `argparse`.
* **Funzionalità:** Gestione del passaggio dinamico dei parametri da riga di comando per l'aggiunta e lo smistamento di singoli file con controlli di esistenza.

### Step 3: Analisi di Immagini con NumPy
* **Obiettivo:** Sfruttare la potenza di calcolo matriciale di NumPy per l'elaborazione visiva.
* **Funzionalità:**
  * Conversione delle immagini in array multidimensionali (`np.array`).
  * Estrazione delle proprietà geometriche fondamentali (`ndim`, `shape`).
  * Calcolo statistico dei valori dei pixel (es. media dei canali di colore per immagini Grayscale, RGB o RGBA).

---

## 🚀 Tecnologie Utilizzate
* **Python 3.x**
* **NumPy** (per la manipolazione degli array e il calcolo numerico)
* **OS & Shutil** (per la gestione del file system e delle directory)
* **PIL / Pillow** (per il caricamento e la gestione preliminare delle immagini)
* **Argparse** (per la creazione della CLI)
