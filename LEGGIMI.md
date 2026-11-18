# Editor caroselli

Apri `editor.html` con Chrome (doppio clic, o trascinalo su una finestra di Chrome). Serve internet solo per il font e per l'esportazione.

## Come si usa

1. **A sinistra** ci sono le slide. Clicca una miniatura per modificarla. **Trascinala** su o giù per cambiare l'ordine (una linea oro mostra dove finirà; vicino al bordo la colonna scorre da sola). In alternativa usa le frecce ↑ ↓ sotto la miniatura, che serve anche per duplicare o eliminare.
2. **Al centro** c'è l'anteprima. Clicca un elemento per selezionarlo.
3. **A destra** modifichi l'elemento selezionato e aggiungi altri elementi. I campi di modifica (testo, colore, dimensione, foto) stanno in un menù a tendina chiuso, "Modifica: …": lo apri con un clic quando ti serve e, una volta aperto, resta aperto anche cambiando elemento. Il testo si scrive anche direttamente sulla slide con il doppio clic: in quel caso il menù "Modifica" si apre da solo e si richiude quando finisci di scrivere (se lo avevi già aperto tu a mano, o se clicchi dentro il menù stesso per scrivere nel suo campo di testo, resta aperto).
4. **+ Nuova slide** apre i template (copertina con foto, solo titolo, titolo + post-it, foto + testo, slide vuota).
5. **File → Nuovo progetto** riparte dalle 3 slide iniziali (copertina, solo titolo, titolo + due post-it), con il cerchio aperto come logo. Se hai modifiche non salvate in un file, prima ti chiede se salvarle ("Salva", "Non salvare" o "Annulla"). Anche dopo, "Annulla" nell'avviso recupera il lavoro precedente.

## Parole evidenziate

Nei titoli e nei testi metti la parola tra asterischi: `Chi *decide*?` diventa "Chi" in bianco e "decide" nel colore evidenziato. Vale anche dentro i post-it (testo grande e piccolo): lì la parola evidenziata diventa rossa (`#C4261A`, il rosso del bagliore dell'editor), perché il giallo non si legge sui colori chiari dei post-it. Si cambia da "Colori e logo", alla voce "Parole evidenziate nei post-it".

**Scorciatoia Control+B (o Cmd+B):** seleziona delle parole e premi Control+B, e l'editor mette gli asterischi al posto tuo. Senza selezione evidenzia la parola dove sta il cursore; se il testo è già evidenziato, ripremendo Control+B torna normale. Va bene sia nei campi del pannello a destra sia scrivendo direttamente sulla slide (doppio clic). Sulla slide il giallo compare subito; nel campo del pannello vedi gli asterischi.

**Scrivere direttamente sulla slide:** doppio clic su un titolo, un testo o un post-it (sul post-it si modifica il testo grande) e scrivi lì dov'è. Sulla slide vedi già il risultato finale (le parole evidenziate sono gialle, senza asterischi); gli asterischi restano visibili solo nel campo di testo del pannello a destra. Con un clic fuori, oppure Esc, finisci di scrivere. Sul testo che stai scrivendo il puntatore diventa una barretta, per non coprire le parole. Il testo piccolo del post-it si modifica dal pannello a destra.

## Elementi in flusso e liberi

- **In flusso** (predefinito): si dispongono da soli uno sotto l'altro. Due post-it con larghezza "Metà" si affiancano.
- **Eliminare un elemento:** selezionalo (nell'anteprima o nella lista) e premi il tasto cancella del Mac, quello con la freccia all'indietro. Se hai il cursore dentro un campo di testo il tasto cancella le lettere, come è giusto; se ti sei sbagliato c'è "Annulla" nell'avviso.
- **Libero**: lo trascini dove vuoi sulla slide, oppure scrivi x, y e larghezza nel pannello. Utile per il tag in copertina.
- "Dove si dispongono gli elementi" (alto, centro, basso) decide dove si raccoglie il flusso.
- **Cambiare l'ordine dalla lista "Elementi":** nel pannello a destra le righe si trascinano su e giù (una linea oro mostra dove finiscono), oppure si usano le frecce ↑ ↓ accanto a ognuna: valgono tutte e due.
- **Cambiare l'ordine trascinando:** clicca un elemento in flusso nell'anteprima e trascinalo su o giù; una linea oro mostra dove finirà (tra due post-it affiancati diventa una barra verticale). Eccezione: la foto in riquadro già selezionata, che si trascina per farla slittare (per spostarla usa le frecce ↑ ↓ nella lista degli elementi, oppure seleziona prima un altro elemento).
- Il "Post-it con percentuale" non compare più tra i pulsanti di "Aggiungi elemento", ma i progetti vecchi che lo contengono si aprono ancora normalmente.

## Logo, sfondo e foto

- **Già incluso:** il **cerchio aperto** disegnato a mano (`assets/cerchio_aperto.png`, con il tratto più spesso e panciuto dal 17/11; la versione sottile originale è in `assets/cerchio_aperto_originale.png`), che è il logo di partenza di ogni progetto, e lo sfondo in cemento (stessa immagine, senza la scritta). I file originali sono in `assets/`, mentre `assets.js` li porta dentro l'editor: tienili nella stessa cartella di `editor.html`.
- **Logo:** ogni progetto nuovo parte con il cerchio. I progetti salvati prima di questa novità (versione 2 o più vecchia, anche i `.carosello` e i `.json`) lo ricevono come logo la prima volta che li apri; se poi li risalvi con un altro logo, quello resta. Da "Colori e logo" in alto: puoi cambiarlo, toglierlo e regolarne la larghezza. Compare in alto a sinistra su tutte le slide (si può spegnere per singola slide).
- **Sfondo:** sempre in "Colori e logo": puoi cambiarlo, toglierlo (resta il colore) o scurirlo con il cursore per leggere meglio il testo.
- **Trascinare un'immagine dal Finder:** lasciala sopra la slide al centro (o sopra una miniatura a sinistra) e viene inserita come foto. Se la lasci sopra una foto già presente la sostituisce; se la slide ha una foto ancora vuota (ad esempio quella della copertina) riempie quella; altrimenti aggiunge una nuova foto "come riquadro". Puoi trascinarne più di una insieme. "Annulla" nell'avviso la toglie. Lasciata altrove, la pagina non si lascia più e non perdi il lavoro.
- **Foto:** aggiungi l'elemento "Foto". "A tutta slide" fa la copertina con il velo scuro, "Come riquadro" la mette in mezzo agli altri elementi.
- **Far slittare la foto:** se la foto viene tagliata, scegli quale parte mostrare con i due cursori "Parte della foto che si vede" (sinistra ↔ destra, alto ↔ basso), oppure, con la foto in riquadro già selezionata, trascinala direttamente nell'anteprima. "Ricentra" la riporta al centro. Vale anche per la foto a tutta slide (lì solo con i cursori).

## Salvare ed esportare

- **Ogni volta che apri l'editor parti dal preset** (copertina, solo titolo, titolo + due post-it). Se l'ultima volta avevi lavoro non salvato in un file, non va perso: compare un avviso con "Recupera" e in alto la voce **File → Recupera lavoro precedente** (un pallino arancio sul menu File ti avvisa; resta finché non la usi). Per tenere un progetto a lungo, salvalo con **Salva progetto**.
- Il lavoro si salva da solo nel browser (in alto vedi "Salvato nel browser"). Se svuoti i dati del browser lo perdi, quindi ogni tanto usa **File → Salva progetto** (scarica un file `.carosello`, che dentro è un normale JSON) e **File → Apri progetto** per riprenderlo (accetta anche i vecchi `.json`).
- **Esporta → PNG di questa slide** o **Esporta → Tutte le slide (ZIP)** creano immagini 1080×1350 pronte per Instagram.
- **Annulla** (pulsante in alto, oppure Control+Z / Cmd+Z, anche con il cursore dentro un campo di testo o mentre scrivi sulla slide) torna indietro fino a 60 passi: scrittura, spostamenti, giallo, elementi aggiunti o eliminati stanno nella stessa storia. Il passo avanti (rifare) non c'è.

## Per modificare l'editor

Il file è un'unica pagina, con commenti in italiano in cima allo script. Nuovo tipo di elemento: `DEF` e `renderBlocco`. Nuovo template: `TEMPLATE`. Colori di partenza: `IMPOSTAZIONI_DEFAULT`.

## Aspetto dell'editor

L'interfaccia è scura e calda (nero, bagliore arancio/rosso, oro del logo UNDER per i comandi principali). I colori stanno in cima al CSS, nel blocco `:root` (`--ui-acc` è l'oro, `--ui-bg` il fondo). Cambia solo l'editor: le slide esportate non dipendono da questi colori.

## Aprire un progetto con il doppio clic

> Questa parte riguarda un piccolo aiuto solo per macOS (l'app "Apri in MiniCanva") che **non è incluso nel repository di GitHub**: è un extra personale. Se hai scaricato il progetto da GitHub, apri i progetti da **File → Apri progetto** dentro l'editor.

Il browser non permette a una pagina locale di leggere da sola un file, quindi serve un piccolo aiuto: l'app **Apri in MiniCanva** (con lo script `apri_progetto.sh`, che lavora dietro le quinte). Devono stare nella stessa cartella di `editor.html`.

**Una volta sola**, per far aprire i `.carosello` con quell'app:
1. Clic destro su un file `.carosello`, poi **Ottieni informazioni**.
2. Alla voce **Apri con** scegli **Apri in MiniCanva** (con "Altro…" se non la vedi).
3. Premi **Cambia tutto…** e conferma.

Da quel momento il doppio clic su un `.carosello` apre Chrome con l'editor e quel progetto già caricato. La prima volta macOS può chiedere il permesso di accedere ai file della Scrivania: consenti.

- **Un vecchio `.json`** non lo associo all'app (aprirebbe con MiniCanva tutti i JSON, anche quelli di altri progetti). Per aprirlo: clic destro, **Apri con**, **Apri in MiniCanva**. Oppure rinominalo in `.carosello`.
- **Se sposti la cartella** dell'editor, l'app e lo script si spostano insieme e funzionano ancora, ma l'associazione dei doppi clic potrebbe andare rifatta (stessi 3 passi).
- Lo script scrive `progetto_da_aprire.js` nella cartella dell'editor (è una copia del progetto, ad ogni apertura viene sovrascritta). L'editor lo legge solo quando viene aperto da questa app, quindi aprendo `editor.html` normalmente non rispunta un vecchio progetto. Puoi cancellarlo quando vuoi.
- Se apri più file insieme, viene aperto solo il primo.
