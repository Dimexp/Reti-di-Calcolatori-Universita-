# Universita'

### Progetto Universitario di Reti di Calcolatori 2023/2024

Studente: Esposito Dimitri Gennaro

Professore: Emanuel Di Nardo

Link Relazione: https://github.com/Dimexp/Reti-di-Calcolatori-Universita-/blob/9d2f1ed835258b9054dd71cfeaa58e1e8b15840a/docs/index.md

## Traccia:

### Scrivere un'applicazione client/server parallelo per gestire esami universitari.

#### Segreteria:

- Inserisce gli esami sul server dell'universita' (salvare in un file o conservare in memoria il dato);
- Inoltra la richiesta di prenotazione degli studenti al server universitario;
- Fornisce allo studente le date degli esami disponibili per l'esame scelto dallo studente.

#### Studente:

- Chiede alla segreteria se ci siano esami disponibili per un corso;
- Invia una richiesta di prenotazione di un esame alla segreteria.

#### Server Universitario:

- Riceve l'aggiunta di nuovi esami;
- Riceve la prenotazione di un esame.

### Condizioni Aggiuntive: Gruppo 2 Studenti

Il server universitario ad ogni richiesta di prenotazione invia alla segreteria il numero di prenotazione progressivo
assegnato allo studente e la segreteria a sua volta lo inoltra allo studente.
