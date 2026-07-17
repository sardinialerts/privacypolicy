# Informativa sulla Privacy — SardiniAlert

**Ultimo aggiornamento:** 17-07-2026

SardiniAlert è sviluppata da SardiniAlert. Questa informativa descrive quali dati raccogliamo, perché, e come vengono trattati.

## Dati che raccogliamo

**Non richiediamo registrazione, nome, email o numero di telefono per usare l'app.** I dati che raccogliamo sono i seguenti:

### Comune selezionato
Il comune (o i comuni, fino a 2 aggiuntivi in watchlist) che scegli nell'app, per mostrarti notizie, avvisi e contenuti rilevanti per la tua zona. Non raccogliamo la posizione GPS del tuo dispositivo: l'app non richiede né utilizza mai il permesso di localizzazione. Per alcuni comuni con dati a livello di via, puoi facoltativamente scegliere la tua via da un elenco (anch'essa una selezione manuale, non una posizione rilevata) per ordinare gli eventi per rilevanza.

### Messaggi in chat e segnalazioni
Se pubblichi un messaggio nella chat di città o una segnalazione (es. guasto idrico, elettrico, ecc.), raccogliamo il testo del messaggio, un nome utente facoltativo che puoi impostare tu stesso (non verificato, puramente visualizzativo), l'argomento/categoria, e — solo per alcuni comuni con dati a livello di via, se scegli la tua via da un elenco — le coordinate di quella via. Anche in questo caso non viene mai rilevata la posizione GPS del dispositivo: è sempre una scelta manuale da un elenco.

### Indirizzo IP (in forma anonimizzata)
Per prevenire abusi e spam (es. limitare quante segnalazioni o messaggi puoi inviare in un dato periodo), il tuo indirizzo IP viene trasformato con una funzione crittografica irreversibile (hash) prima di essere salvato. Non conserviamo mai l'indirizzo IP in chiaro: l'hash non può essere usato per risalire al tuo indirizzo IP originale.

### Voti
Se voti su un evento, una segnalazione o un messaggio (es. "risolto"/"non risolto", pollice su/giù), registriamo il voto insieme all'hash del tuo IP, per evitare voti duplicati dallo stesso dispositivo.

### Token per le notifiche push
Se attivi le notifiche, il tuo dispositivo riceve un identificativo tecnico (token) usato da Firebase Cloud Messaging per recapitarti le notifiche che hai scelto di ricevere (es. allerte meteo, aggiornamenti chat, sagre). Il token è associato solo al comune selezionato e alle tue preferenze di notifica — non a un nome o a un'identità personale.

### Messaggi di feedback
Se ci invii un feedback dall'app, raccogliamo il testo del messaggio, la lingua dell'app e il comune selezionato al momento dell'invio. Nessun identificativo personale viene associato al feedback.

### Statistiche di utilizzo aggregate
Registriamo in forma aggregata e anonima (hash IP + comune + data) le visualizzazioni di alcune sezioni dell'app, per capire l'utilizzo generale del Servizio. Questi dati non vengono mai analizzati riga per riga per ricostruire l'attività di una singola persona.

## Come usiamo i dati

- Per mostrarti contenuti (notizie, allerte, sagre, albo pretorio) rilevanti per il tuo comune.
- Per far funzionare la chat di città e le segnalazioni della community.
- Per inviarti le notifiche push che hai scelto di attivare.
- Per prevenire spam e abusi (rate-limiting tramite hash IP).
- Per migliorare il Servizio tramite feedback e statistiche aggregate.

Non vendiamo né condividiamo i tuoi dati con terze parti per scopi pubblicitari o di marketing.

## Con chi condividiamo i dati

I dati sono ospitati su infrastruttura di terze parti che agisce come nostro responsabile del trattamento (data processor):

- **Supabase** (database PostgreSQL) — ospita tutti i dati elencati sopra.
- **Google Firebase Cloud Messaging** — usato esclusivamente per la consegna delle notifiche push, riceve il token del dispositivo.

Nessun altro soggetto terzo riceve i tuoi dati.

## Conservazione dei dati

- Le segnalazioni, i voti, i messaggi in chat e le visualizzazioni aggregate vengono conservati per un massimo di 365 giorni, dopodiché vengono eliminati automaticamente in modo definitivo.
- Puoi eliminare un tuo messaggio in chat entro 15 minuti dalla pubblicazione, direttamente dall'app (l'autore originale può oscurare il testo del proprio messaggio).
- Notizie e atti dell'albo pretorio (contenuti pubblici scaricati da fonti ufficiali, non generati dagli utenti) seguono un proprio periodo di conservazione, anch'esso di 365 giorni di default.

## Richiesta di cancellazione dati

Poiché l'app non richiede un account, non esiste un login associato ai tuoi contenuti da cui richiedere la cancellazione in autonomia. Se vuoi richiedere la rimozione di un messaggio, una segnalazione o un feedback specifico che hai pubblicato, scrivici a **sardegnaallerte@gmail.com** indicando il contenuto e, se possibile, la data/ora e il comune — verificheremo e provvederemo alla rimozione.

## Sicurezza

I dati sono trasmessi tramite connessioni cifrate (HTTPS/TLS) tra l'app e i nostri server. Gli indirizzi IP non vengono mai conservati in chiaro.

## Minori

Il Servizio non è rivolto specificamente a minori di 13 anni e non raccogliamo consapevolmente dati aggiuntivi da minori oltre a quanto sopra descritto (già raccolto in forma anonima/pseudonima da chiunque usi l'app).

## Modifiche a questa informativa

Potremmo aggiornare periodicamente questa informativa. La data di "Ultimo aggiornamento" in cima alla pagina riflette l'ultima revisione.

## Contatti

Per domande su questa informativa o sul trattamento dei tuoi dati, scrivici a: **sardegnaallerte@gmail.com**

---

*English summary: SardiniAlert requires no account, name, or email, and does not request or use device location/GPS permission. We collect: your selected comune (and optionally a street, both manually chosen from a list — never a detected position), optional chat/report content tied to a one-way hashed IP address (never stored in plain form), push notification tokens (via Firebase Cloud Messaging), optional feedback text, and aggregate anonymous usage stats. Data is hosted on Supabase (PostgreSQL) as our data processor. Most content is auto-deleted after 365 days; chat messages can be self-deleted by the author within 15 minutes of posting. We don't sell or share data with third parties for advertising. Contact sardegnaallerte@gmail.com for deletion requests or questions.*
