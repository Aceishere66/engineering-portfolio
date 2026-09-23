# Simone Ferrari — Portfolio di Ingegneria

**Software Engineering · AI · Sistemi Intelligenti**

[**English**](README.md) · **Italiano**

Studio **Ingegneria Informatica, Elettronica e delle Telecomunicazioni all'Università di Parma** e sviluppo progetti personali software e tecnologici attraverso **EDITH Dev Studio**, il mio studio personale di sviluppo software dedicato ad applicazioni, prototipi e sperimentazione tecnica.

Questa repository è l'indice di una selezione curata di progetti di ingegneria. Le repository complete di sviluppo restano private quando contengono dati personali, configurazioni, pianificazione interna o materiale proprietario; le edizioni pubbliche collegate mostrano invece architettura, codice rappresentativo ed evidenze di verifica.

## Progetti di ingegneria selezionati

### 1. EDITH Overdrive — Performance Cockpit

**Systems engineering · telemetria · concorrenza · performance**

Cockpit Windows per il monitoraggio delle prestazioni, costruito attorno a telemetria live a basso overhead, snapshot condivisi, acquisizione asincrona, diagnostica, integrazione benchmark e degradazione controllata quando alcuni dati non sono disponibili.

Evidenze principali:

- separazione tra fast path e slow path
- riutilizzo degli snapshot tramite TTL
- controllo della concorrenza durante refresh costosi
- guardrail automatici contro regressioni prestazionali
- codice C# rappresentativo
- la revisione sorgente mostrata registra 201 test C# superati

Repository: https://github.com/Aceishere66/EDITH-Overdrive-Showcase

---

### 2. EDITH Fit

**Android · dati wearable · sincronizzazione · validazione su dispositivi reali**

Piattaforma Android per dati salute/allenamento basata su Health Connect, Samsung Health, Wear OS, coroutine Kotlin, Room e sincronizzazione persistente.

Evidenze principali:

- provenance di sorgente/dispositivo mantenuta durante la normalizzazione
- sincronizzazione incrementale e gestione idempotente dello stato
- protocollo Wear OS con telefono autorevole e revisioni monotone
- test strumentati su hardware Android reale
- 8 test protocollo + 191 test app + 34 test wear registrati come superati nella revisione sorgente mostrata
- 54 test strumentati su telefono fisico registrati come superati

Repository: https://github.com/Aceishere66/EDITH-Fit-Showcase

---

### 3. EDITH Aegis — AI Engineering & Model Lab

**Valutazione LLM · coding agent · context engineering · workflow multi-model**

Sezione pubblica di ricerca focalizzata sull'uso strutturato di LLM e coding agent.

Evidenze principali:

- routing dei modelli specifico per task/ruolo
- holdout di benchmark congelato
- criteri di accettazione predefiniti
- correzione dello scorer dopo aver individuato un difetto metodologico
- workflow separati di implementazione/revisione
- handoff strutturati tra modelli e sessioni

In un holdout reale da 12 casi per il ruolo di critic, entrambi i modelli finalisti hanno raggiunto 12/12 verdict corretti con 0 FP/FN; il modello selezionato ha ottenuto recall delle evidenze pari a 0,9722 contro 0,8889 del finalista più veloce.

Repository: https://github.com/Aceishere66/EDITH-Aegis-Research

---

### 4. EDITH Intake — Multimodal Sensing Research

**Computer vision · IMU · RGB · depth · inferenza temporale**

Progetto di ricerca su sensing wearable event-triggered e inferenza multimodale.

Evidenze principali:

- esperimenti locali con DINOv2
- reference bank multi-prototipo da 72 immagini
- esecuzione locale di Depth Anything V2 Small
- pipeline di elaborazione temporale dei segnali
- state machine a 4 stati per il rilevamento di eventi di assunzione
- base software per acquisizione/import di dati IMU fisici
- auditing di timing/jitter/gap
- separazione rigorosa tra evidenze software/simulate e futura validazione fisica del prodotto

Repository: https://github.com/Aceishere66/EDITH-Intake-Research

---

## Profilo tecnico

### Software engineering

- Python
- C
- C#
- Kotlin / Android
- JavaScript / TypeScript
- Git / GitHub
- SQL
- testing automatico
- debugging
- programmazione asincrona e concorrente

### Sistemi e dati

- pipeline di telemetria
- normalizzazione di dati eterogenei
- sincronizzazione
- gestione dello stato
- integrazione API/dispositivi
- sviluppo su piattaforme Windows e Android
- validazione su hardware reale
- architetture attente alle prestazioni

### AI-assisted software engineering

Utilizzo LLM e coding agent all'interno di workflow di sviluppo strutturati, senza considerare automaticamente corretto il codice generato.

Pratiche tipiche:

- requisiti e criteri di accettazione espliciti
- context engineering
- decomposizione dei task
- selezione del modello in base al tipo di problema
- handoff strutturati tra modelli/sessioni
- separazione implementazione/revisione
- evidenze tramite build/test
- architettura e validazione finale sotto controllo umano

Vedi [AI-assisted engineering](docs/AI_ASSISTED_ENGINEERING.md).

## Rilevanza per sistemi intelligenti e autonomi

Questi progetti **non** vengono presentati come precedenti implementazioni di guida autonoma.

La base ingegneristica trasferibile comprende:

- software asincrono/concorrente
- pipeline di telemetria live e dati da sensori
- integrazione hardware/API
- gestione di dati parziali e failure
- sistemi sensibili alle prestazioni
- sincronizzazione dello stato
- validazione automatizzata
- ricerca AI multimodale
- sviluppo riproducibile basato su Git

Vedi:

- [Rilevanza ingegneristica trasferibile](docs/INTELLIGENT_SYSTEMS_RELEVANCE.md)
- [Matrice delle evidenze dei progetti](docs/PROJECT_EVIDENCE_MATRIX.md)

## Esperienze aggiuntive

Altri progetti includono:

- **Upscaler Studio** — elaborazione multimediale AI locale con FFmpeg e modelli di upscaling
- **STEAM Lab / Arduino** — precedenti attività di prototipazione e physical computing
- progetti web/applicativi in TypeScript, Python e sistemi con database
- modellazione 3D
- video editing

## Sito

**Portfolio tecnico:** https://edithdevstudio.com/engineering

## Policy del portfolio

Ogni repository collegata è un'edizione showcase/research curata.

L'obiettivo è rendere ispezionabile il lavoro ingegneristico rappresentativo mantenendo privati:

- dati personali
- credenziali/configurazioni
- codice sorgente completo dei prodotti privati
- materiale di pianificazione interna
- contenuti di ricerca sensibili
