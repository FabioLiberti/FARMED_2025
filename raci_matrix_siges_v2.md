# Matrice RACI - Reingegnerizzazione SIGES Flusso F

**Progetto:** Sistema Regionale SIGES - Reingegnerizzazione Flusso F (Distribuzione Diretta)  
**Data:** Agosto 2025  
**Responsabile:** Area Farmaci e Dispositivi - Regione Lazio

## Legenda RACI:
- **R** = Responsible (Responsabile dell'esecuzione)
- **A** = Accountable (Garante del risultato - uno solo per attività)
- **C** = Consulted (Consultato - fornisce input)
- **I** = Informed (Informato - riceve comunicazioni)

## Matrice RACI

| Attività/Deliverable | Area Farmaci Regione Lazio | LAZIOcrea S.p.A | Responsabili ICT Aziendali | Referenti Flussi Informativi Aziendali | Software House |
|---------------------|---------------------------|-----------------|---------------------------|---------------------------------------|----------------|
| **Definizione specifiche funzionali** | A | R | C | C | I |
| **Consolidamento documento funzionale** | A | R | C | C | I |
| **Sviluppo sistema XML** | C | A | I | I | R |
| **Implementazione cooperazione applicativa M2M** | C | A | R | I | R |
| **Aggiornamento infrastruttura SIGES** | C | A | I | I | I |
| **Adeguamento sistemi aziendali** | I | C | A | C | R |
| **Test di sperimentazione con aziende pilota** | C | R | A | C | C |
| **Formazione referenti aziendali** | A | R | C | R | I |
| **Validazione tracciati XML** | C | R | A | C | C |
| **Collaudo sistema** | C | A | R | C | I |
| **Avvio a regime nuovo sistema** | A | R | C | C | I |
| **Coordinamento tavoli tecnici** | A | C | R | C | I |
| **Monitoraggio conformità NSIS** | A | R | I | I | I |

## Ruoli coinvolti:

### **Area Farmaci e Dispositivi - Regione Lazio**
- Direzione e coordinamento del progetto
- Definizione requisiti funzionali
- Supervisione conformità normativa
- Approvazione deliverable

### **LAZIOcrea S.p.A**
- Direzione Sistemi Informativi
- Sviluppo e implementazione tecnica
- Gestione infrastruttura regionale
- Supporto tecnico specialistico

### **Responsabili ICT Aziendali**
- Coordinamento tecnico aziendale
- Interfaccia con Software House
- Gestione adeguamenti infrastruttura locale
- Supervisione test e collaudo

### **Referenti Flussi Informativi Aziendali**
- Competenza funzionale sui flussi
- Validazione dati e controlli
- Formazione operatori
- Supporto nell'implementazione

### **Software House**
- Sviluppo adeguamenti sistemi aziendali
- Implementazione tracciati XML
- Sviluppo interfacce M2M
- Supporto tecnico specializzato

## Note:
- Timeline progetto: Settembre 2025 - Giugno 2026
- Ogni attività deve avere almeno un **R** e un **A**
- La matrice sarà rivista durante gli incontri tecnici programmati
- Focus prioritario sul Flusso F (Distribuzione Diretta) come indicato nella presentazione del 03/07/2025

---

# Matrice RACI di Dettaglio - OPBG (Ospedale Pediatrico Bambino Gesù)

**Progetto:** Reingegnerizzazione Flusso Farmaci (FARMED/File F) - OPBG  
**Data:** Agosto 2025  
**Responsabile Aziendale:** Fabio Liberti (PM OPBG)

## Stakeholder OPBG identificati:

### **Nominativi e Ruoli:**
- **Donatelli David**: Sistemi Informativi (File F)
- **Liberti Fabio**: Gestione Amministrativa Ciclo Attivo (FARMED) - **PM PROGETTO**
- **Pelosi Simone**: Sistemi Informativi (FARMED) - **Referente Tecnologico Regione**
- **Corsetti Tiziana**: Farmacia (File F, FARMED) - **Referente Clinico Regione**
- **Brusco Carla**: Servizio Informativo Ospedaliero (Anagrafiche Assistiti)

### **Referenti per il progetto:**
- **PM OPBG**: Fabio Liberti (Coordinamento generale progetto)
- **Referente Tecnologico con Regione**: Simone Pelosi (Interfaccia tecnica)
- **Referente Clinico con Regione**: Tiziana Corsetti (Interfaccia funzionale/clinica)

## Matrice RACI Dettagliata OPBG

| Attività/Deliverable | Liberti F. (PM) | Donatelli D. (SI File F) | Pelosi S. (SI-Ref.Tecn.) | Corsetti T. (Farm-Ref.Clin.) | Brusco C. (SIO) | Software House OPBG |
|---------------------|-----------------|--------------------------|--------------------------|------------------------------|-----------------|-------------------|
| **Coordinamento generale progetto** | A | I | C | C | I | I |
| **Interfaccia tecnologica con Regione** | C | C | A | I | I | C |
| **Interfaccia clinica/funzionale con Regione** | C | I | C | A | I | I |
| **Analisi impatti sistemici File F** | C | A | R | C | I | C |
| **Mappatura dati FARMED esistenti** | A | C | C | R | I | C |
| **Progettazione adeguamenti XML** | C | R | A | C | I | R |
| **Sviluppo interfacce M2M** | C | C | A | I | I | R |
| **Configurazione sistema contabilità** | A | C | R | C | I | R |
| **Adeguamento flusso farmacia** | C | I | C | A | I | R |
| **Integrazione anagrafiche SIO** | I | C | C | C | A | R |
| **Validazione funzionale File F** | C | A | C | R | I | C |
| **Test di integrazione** | A | R | R | R | C | C |
| **Formazione utenti finali** | C | C | C | A | C | I |
| **Validazione dati migrazione** | A | C | C | R | C | I |
| **Monitoraggio flusso verso SIGES** | A | C | R | C | C | I |
| **Go-live sistema** | A | R | R | R | C | C |
| **Supporto post go-live** | C | R | R | C | C | A |

## Responsabilità Specifiche OPBG (AGGIORNATE):

### **Liberti Fabio - PM OPBG (Gestione Amministrativa Ciclo Attivo - FARMED)**
- **Coordinatore Generale Progetto OPBG**
- Responsabile funzionale dati FARMED
- Validazione logiche contabili FARMED
- Controllo coerenza dati economici flusso
- Controllo processo funzionale flusso (bottom-up)
- Monitoraggio processo e migrazione dati alla regione (SIGES)
- Gestione escalation OPBG

### **Donatelli David (Sistemi Informativi - File F)**
- Responsabile funzionale e tecnico implementazione File F
- Validazione funzionale File F
- Controlli tecnici integrazione con File F
- Testing tecnico File F

### **Pelosi Simone (Sistemi Informativi FARMED - Referente Tecnologico Regione)**
- **Interfaccia Tecnologica con Regione Lazio e LAZIOcrea**
- Responsabile tecnico implementazione FARMED e integrazioni
- Interfaccia sistemi informativi per lo sviluppo
- Coordinamento con Software House OPBG
- Gestione aspetti infrastrutturali
- Backup e recovery procedure

### **Corsetti Tiziana (Farmacia - Referente Clinico Regione)**
- **Interfaccia Clinica/Funzionale con Regione Lazio e LAZIOcrea**
- Responsabile funzionale/clinico flusso farmacia
- Validazione dati clinici e farmaceutici
- Formazione staff farmacia
- Controllo qualità dati

### **Brusco Carla (Servizio Informativo Ospedaliero)**
- Responsabile flusso servizio informativo ospedaliero (SIO)
- Gestione integrazione anagrafiche assistiti
- Verifica funzionale integrazione con sistema SIO
- Validazione conformità

### **Software House OPBG**
- Sviluppo customizzazioni
- Implementazione tracciati XML
- Sviluppo interfacce automatiche M2M
- Supporto tecnico specializzato

## Timeline Specifica OPBG:
- **Settembre 2025**: Kick-off progetto, definizione team
- **Ottobre 2025**: Analisi AS-IS e gap analysis
- **Novembre-Dicembre 2025**: Sviluppo e configurazioni
- **Gennaio-Febbraio 2026**: Test e validazioni
- **Marzo-Aprile 2026**: Formazione e preparazione go-live
- **Maggio 2026**: Go-live pilota
- **Giugno 2026**: Avvio a regime