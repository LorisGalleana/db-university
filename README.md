
---

# DB-UNIVERSITY

## Descrizione

Il progetto **DB-UNIVERSITY** consiste nella modellazione della struttura di un database per memorizzare tutte le informazioni riguardanti un'università, inclusi dipartimenti, corsi di laurea, corsi, insegnanti, esami e studenti. L'obiettivo è progettare un modello relazionale che tenga traccia di tutti gli aspetti accademici dell'università e delle interazioni tra studenti, corsi e esami.

### Funzionalità

1. **Modellazione della struttura del database**:
   - Creare entità (tabelle) per memorizzare le seguenti informazioni:
     - **Dipartimenti**: Ogni dipartimento (es. Lettere e Filosofia, Matematica, Ingegneria) ha un nome e altre informazioni correlate.
     - **Corsi di Laurea**: Ogni corso di laurea è offerto da un dipartimento (es. Civiltà e Letterature Classiche, Informatica, Ingegneria Elettronica) e appartiene a un dipartimento specifico.
     - **Corsi**: Ogni corso di laurea prevede vari corsi (es. Letteratura Latina, Sistemi Operativi 1, Analisi Matematica 2), e ogni corso può essere tenuto da più insegnanti.
     - **Insegnanti**: Ogni insegnante può tenere uno o più corsi.
     - **Appelli d’Esame**: Ogni corso ha diversi appelli d’esame.
     - **Studenti**: Ogni studente è iscritto a un solo corso di laurea e può partecipare a più appelli d’esame.
     - **Voti**: Per ogni appello d’esame a cui uno studente ha partecipato, è necessario memorizzare il voto ottenuto.

2. **Creazione delle relazioni**:
   - Stabilire le relazioni tra le tabelle, come le relazioni molti-a-molti tra corsi e insegnanti, corsi e appelli, e corsi e studenti.
   - Definire le chiavi primarie e le chiavi esterne per le relazioni tra le entità.

3. **Schema del database**:
   - Utilizzare uno strumento come **draw.io** o **MySQL Workbench** per creare lo schema del database, rappresentando visivamente le tabelle e le relazioni.
   - Esportare il diagramma in formato **jpg** e caricarlo nella repo.

### Tecnologie utilizzate

- **draw.io** o **MySQL Workbench**: Per la creazione dello schema del database.
- **MySQL**: Per la gestione del database e la definizione delle tabelle e delle relazioni.

---
