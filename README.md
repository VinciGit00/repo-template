## Dettaglio dei file generati da `init.sh`

Ecco una panoramica dei principali file creati dallo script, con focus su quelli fondamentali per la collaborazione e l’uso avanzato di Copilot/AI:

- **.github/copilot-instructions.md**: 
    - Contiene regole, convenzioni e prompt di esempio per guidare Copilot e altri agenti AI nella generazione di codice e documentazione.
    - **Struttura consigliata:**
        ```markdown
        # Istruzioni per Copilot/AI

        ## Obiettivi del progetto
        - Descrivi in modo chiaro e sintetico cosa deve fare il progetto.

        ## Convenzioni di stile
        - Elenca regole di formattazione, nomi variabili, struttura delle funzioni/classi, ecc.

        ## Prompt di esempio
        - Fornisci esempi di commenti o richieste che portano a generare codice di qualità.
        - Esempio:
            ```python
            # Scrivi una funzione che calcola la media di una lista di numeri
            ```

        ## Regole per la documentazione
        - Come devono essere scritte docstring, commenti, README, ecc.

        ## Best practice per l’uso di Copilot
        - Suggerimenti su come ottenere suggerimenti utili e come validare il codice generato.
        ```

- **.github/COMMIT_CONVENTION.md**: Regole per i messaggi di commit (es. Conventional Commits).
- **.github/CONTRIBUTING.md**: Linee guida per contribuire al progetto.
- **.github/PULL_REQUEST_TEMPLATE.md**: Template per le pull request.
- **.github/SECURITY.md**: Modalità di segnalazione delle vulnerabilità.
- **.github/CODEOWNERS**: Definisce i responsabili delle revisioni del codice.
- **.github/ISSUE_TEMPLATE/**: Template per segnalazione bug e richieste feature.
- **.gitignore**: Esclude file e cartelle comuni da versionamento.
- **CHANGELOG.md**: Storico delle modifiche rilevanti.
- **LICENSE**: Licenza del progetto (es. MIT).
- **package.json**: Configurazione base per progetti Node.js.
- **README.md**: Documentazione principale del progetto.
- **jest.config.js**, **setupTests.js**: Configurazione e setup per test JavaScript/React.
- **pytest.ini**, **requirements-dev.txt**: Configurazione e dipendenze per test e sviluppo Python.
- **.editorconfig**, **.prettierrc**, **.eslintrc.json**, **.flake8**: Regole di formattazione e linting per vari linguaggi.

Personalizza questi file secondo le esigenze del tuo team e del progetto per ottenere il massimo da Copilot e dalla collaborazione.
# Project Template with Copilot

Questa repository è pensata come template per iniziare rapidamente nuovi progetti, sfruttando le potenzialità di GitHub Copilot.

## Struttura della repository

- `src/` — Cartella per il codice sorgente del progetto
- `docs/` — Documentazione e guide
- `.gitignore` — File per escludere file/folder comuni
- `init.sh` — Script di inizializzazione automatica della struttura e dei file base del progetto (vedi sotto)
## Cosa fa `init.sh`

Lo script `init.sh` automatizza la creazione della struttura di base della repository e di tutti i file fondamentali per un nuovo progetto. In particolare:

- Crea la cartella `.github/` con template per issue, pull request, linee guida per i contributi, sicurezza, convenzioni di commit e istruzioni per Copilot/AI.
- Genera file di configurazione comuni come `.gitignore`, `LICENSE`, `CHANGELOG.md`, `package.json`, `README.md`, file di test (`jest.config.js`, `setupTests.js`, `pytest.ini`), e file di configurazione per formattazione e linting (`.editorconfig`, `.prettierrc`, `.eslintrc.json`, `.flake8`).
- Prepara template per issue e feature request in `.github/ISSUE_TEMPLATE/`.
- Crea file per la gestione delle dipendenze di sviluppo (`requirements-dev.txt`).

**Scopo:** velocizzare l'avvio di un nuovo progetto fornendo una base completa e personalizzabile, pronta per essere adattata alle esigenze specifiche.

**Come usare:**
1. Esegui `bash init.sh` dalla root della repository.
2. Personalizza i file generati secondo le necessità del tuo progetto.

**Nota:** Puoi modificare lo script per aggiungere/rimuovere file o cambiare i contenuti predefiniti.

## Come usare questo template

1. Clicca su "Use this template" su GitHub per creare un nuovo repository basato su questo.
2. Personalizza la struttura secondo le tue esigenze.
3. Inizia a scrivere codice nella cartella `src/`.

## Tips & Tricks per Copilot

- **Scrivi commenti chiari**: Copilot genera codice migliore se i commenti sono dettagliati.
- **Sfrutta i suggerimenti**: Premi `Tab` per accettare, `Esc` per ignorare, e `Ctrl+Space` per vedere più opzioni.
- **Chiedi funzioni complesse**: Descrivi cosa vuoi ottenere, Copilot può generare intere funzioni o classi.
- **Refactoring**: Usa Copilot anche per migliorare codice esistente, non solo per scriverne di nuovo.
- **Documentazione**: Chiedi a Copilot di generare docstring o commenti per il tuo codice.

## Esempio di utilizzo

```python
# src/example.py
"""Esempio di funzione generata con Copilot"""
def somma(a, b):
    """Restituisce la somma di due numeri"""
    return a + b
```

---

Per domande o suggerimenti, apri una issue!
