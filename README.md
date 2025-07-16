# 🔄 SyncEase – Sistema intelligente di sincronizzazione file

**Autore:** Raffaele Diomaiuto  
**Licenza:** Apache 2.0
**Repository:** [start94/SyncEase](https://github.com/start94/SyncEase)

---

## 📦 Descrizione

SyncEase è uno strumento avanzato sviluppato in Python per sincronizzare in modo efficiente due cartelle locali.  
Utilizza **parallelismo con thread e processi**, gestione intelligente dei file tramite timestamp, **log dettagliato**, e include un **sistema di test automatico**.

> ✅ Progetto utile per portfolio, sistemi locali, backup incrementali e dimostrazione di capacità avanzate in Python e OOP.

---

## ⚙️ Funzionalità

- 📁 Sincronizzazione file tra due cartelle
- ♻️ Aggiornamento automatico dei file modificati
- 🗑️ Rimozione dei file obsoleti
- 📂 Supporto completo a sottocartelle
- 🔄 Parallelismo con `ThreadPoolExecutor` e `ProcessPoolExecutor`
- 🧪 Sistema di **test automatici** su casi realistici
- 🧠 Logging dettagliato per diagnosi e tracciamento

---

## 🚀 Avvio rapido

### ✅ Requisiti

- Python 3.7 o superiore  
- Nessuna libreria esterna richiesta (usa solo librerie standard)

### ▶️ Esecuzione

```bash
python prog_raffaele_diomaiuto_coding_avanzato.py
Questo avvierà la modalità test, che simula diversi scenari reali.

📁 Struttura del Progetto
bash

SyncEase/
├── prog_raffaele_diomaiuto_coding_avanzato.py  # Script principale
├── README.md
├── LICENSE
└── sync_log.txt                                # Log delle operazioni (generato a runtime)
📈 Esempio di output
text

 Avvio del sistema per sincronizzare File SyncEase

Scenario: Test 1: Pochi file
test 1: sincronizzazione iniziale/copia 
  Completato in: 0.07 secondi

 Statistiche di sincronizzazione 
File copiati: 2
File aggiornati: 0
File eliminati: 0
Errori riscontrati: 0
Totale operazioni gestite: 2
💡 Possibili Estensioni Future
Integrazione GUI con Tkinter o PyQt

Sincronizzazione via rete (LAN o SSH)

Supporto backup su Google Drive o S3

Notifiche via email o Telegram

🙌 Contribuire
Pull request benvenute!
Se trovi un bug o vuoi proporre miglioramenti, apri una Issue o scrivimi.

🧠 Autore
👨‍💻 Raffaele Diomaiuto
💡 Studente e sviluppatore nel campo del Machine Learning, AI e automazione.
