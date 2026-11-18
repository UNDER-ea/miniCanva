# miniCanva

Un editor di caroselli per Instagram che funziona nel browser. È una sola pagina web: niente da installare, niente account, niente server. Scrivi i testi, aggiungi foto e post-it, esporti le slide in PNG (1080×1350) pronte da pubblicare.

**Provalo online:** https://under-ea.github.io/miniCanva/

## Usarlo sul tuo computer (3 passi, senza sapere nulla di GitHub)

1. Su questa pagina clicca il bottone verde **Code**, poi **Download ZIP**.
2. Apri il file ZIP scaricato: ottieni una cartella.
3. Apri il file `editor.html` dentro la cartella con Chrome (doppio clic, oppure trascinalo su una finestra di Chrome).

Serve internet solo per il font e per l'esportazione delle immagini. Il lavoro si salva da solo nel tuo browser; per tenerlo a lungo usa **File → Salva progetto**.

Le istruzioni d'uso complete (elementi, foto, parole evidenziate, scorciatoie) sono in [LEGGIMI.md](LEGGIMI.md).

## Farne una tua versione

È un progetto open source: puoi copiarlo e cambiarlo come vuoi.

1. In alto a destra su questa pagina premi **Fork** e conferma. GitHub crea una copia tua, a tuo nome.
2. Nella tua copia apri `editor.html`, premi la matita in alto a destra per modificarlo, poi **Commit changes** per salvare. In alternativa scarica la copia sul tuo computer e modificala con l'editor di testo che preferisci.
3. Per avere la tua versione online: nella tua copia vai in **Settings → Pages**, scegli **Deploy from a branch**, ramo **main**, cartella **/ (root)** e salva. Dopo un minuto il tuo sito è all'indirizzo `https://TUO-NOME.github.io/miniCanva/`.

Non serve conoscere altro: ogni modifica che salvi nella tua copia aggiorna il tuo sito da sola.

## Dove mettere le mani

Tutto il codice sta in `editor.html`, con commenti in italiano in cima allo script.

- Nuovo tipo di elemento: `DEF` e `renderBlocco`.
- Nuovo template di slide: `TEMPLATE`.
- Colori di partenza: `IMPOSTAZIONI_DEFAULT`.

## Cosa c'è nella cartella

| File | A cosa serve |
|---|---|
| `editor.html` | L'editor vero, tutto in una pagina |
| `assets.js` | Logo e sfondo incorporati nell'editor |
| `assets/` | Le stesse immagini come file separati, da cui si genera `assets.js` |
| `index.html` | Rimanda a `editor.html` (serve a GitHub Pages) |
| `LEGGIMI.md` | Istruzioni d'uso |
| `LICENSE` | Licenza MIT |

## Logo e sfondo

Il cerchio aperto e lo sfondo in cemento sono inclusi come esempio. Nella tua versione puoi sostituirli con i tuoi da **Colori e logo**, dentro l'editor.

## Licenza

Codice rilasciato con licenza [MIT](LICENSE): puoi usarlo, copiarlo, modificarlo e anche venderlo, basta mantenere l'avviso di copyright.
