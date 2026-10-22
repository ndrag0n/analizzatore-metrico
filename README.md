# analizzatore-metrico
Analizzatore metrico dell’endecasillabo italiano: ictus, sillabe, sinalefe, dialefe, dieresi, sineresi e tipo di verso. Funziona nel browser, senza server.

# Analizzatore metrico dell'endecasillabo

Strumento per analizzare versi italiani: colloca gli accenti, divide in sillabe,
riconosce sinalefe, dialefe, dieresi e sineresi e classifica l'endecasillabo
(a maiore, a minore, non canonico; tronco, piano, sdrucciolo…).
Serve anche come aiuto alla scrittura di sonetti: i versi non riconosciuti
ricevono suggerimenti (iati, accenti alternativi).

**Prova online:** https://ndrag0n.github.io/analizzatore-metrico/

## Uso
Incolla un verso o una poesia intera e premi *Analizza*. L'analisi avviene
interamente nel tuo browser: i testi non vengono inviati a nessun server.
Il menu «Dieresi/sineresi al massimo» regola la rigidità: «0 (rigorosa)» esclude
ogni licenza, «2» è la modalità permissiva.

## Uso locale
- Sito: `python avvia_web.py`
- Terminale: `python project.py` (opzione `-r` per la modalità rigorosa)

## Dati
`exceptions.json`, `iati.json`, `apocopi.json`, `sdrucciole_extra.json`,
`curiosita.json`: librerie di parole modificabili (si possono aggiungere voci).

## Fonti metriche
Beltrami, *La metrica italiana*; Menichetti, *Metrica italiana*; corpus
della Divina Commedia di Asperti per la verifica.
