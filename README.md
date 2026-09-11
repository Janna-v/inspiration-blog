# Inspiration Blog

Sito statico dedicato a viaggi e destinazioni, realizzato durante Hackademy di Aulab.

**Progetto individuale.** Esercitazione sulla costruzione di pagine web con HTML e CSS.

## Contenuti e interfaccia

- Homepage con presentazione e schede degli articoli.
- Pagina di raccolta degli articoli.
- Pagine di dettaglio dedicate alle destinazioni.
- Sezione About.
- Icone Font Awesome e stili CSS condivisi.
- Regole CSS per schermi piccoli, tra cui una media query a 578 px e adattamenti delle pagine di dettaglio.

## Struttura

- `index.html`: homepage.
- `allArticles.html`: raccolta degli articoli.
- `card1.html` – `card12.html`: pagine di dettaglio.
- `aboutUs.html`: pagina About.
- `style.css`: stili comuni e adattamenti del layout.
- File immagine nella radice: risorse delle pagine.

## Visualizzazione

Aprire `index.html` in un browser moderno. Non sono necessari npm, una build o un database. Serve una connessione Internet per caricare il kit Font Awesome esterno.

In alternativa, con Python disponibile, avviare dalla radice:

```powershell
python -m http.server 8080
```

Visitare `http://localhost:8080/index.html`.

## Stato

È un sito statico con contenuti scritti nelle pagine HTML. Gli adattamenti responsive sono presenti nel CSS; la resa sulle diverse dimensioni dello schermo e tutti i collegamenti richiedono ancora una verifica visiva. Questa revisione è stata svolta sul codice.
