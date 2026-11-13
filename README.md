# progetti-montaletti

Sorgente del portfolio dei progetti open source pubblicato su <https://progetti.montaletti.eu>.

Il sito è una singola pagina statica (`index.html`) senza fase di build. Ogni push sul ramo `main` viene pubblicato automaticamente sull'hosting Hostinger tramite Git auto-deploy.

## Aggiornare il portfolio

1. Modificare `index.html`: ogni progetto è un elemento `<article class="card">` dentro la sezione `<section class="group">` della sua area tematica.
2. Aggiornare i conteggi nella sezione `stats` se cambia il numero di progetti, pacchetti R o siti di documentazione.
3. Fare commit e push su `main`.

Anteprima locale:

```bash
python3 -m http.server 8765
```

## Autore

Giampaolo Montaletti — [github.com/gmontaletti](https://github.com/gmontaletti) — ORCID [0009-0002-5327-1122](https://orcid.org/0009-0002-5327-1122)
