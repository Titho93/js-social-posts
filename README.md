Social Posts
===
Ricreiamo un feed social aggiungendo al layout di base fornito, il nostro script JS in cui:
1. Creiamo il nostro array di oggetti che rappresentano ciascun post.
Ogni post dovrà avere le informazioni necessarie per stampare la relativa card:
- id del post, numero progressivo da 1 a n
- nome autore,
- foto autore,
- data in formato americano (mm-gg-yyyy),
- testo del post,
- immagine (non tutti i post devono avere una immagine),
- numero di likes.
*Non è necessario creare date casuali*
*Per le immagini va bene utilizzare qualsiasi servizio di placeholder ad es. Unsplash (https://unsplash.it/300/300?image=<id>)*
2. Prendendo come riferimento il layout di esempio presente nell’html, stampiamo i post del nostro feed.
3. Se clicchiamo sul tasto “Mi Piace” cambiamo il colore al testo del bottone e incrementiamo il counter dei likes relativo.
Salviamo in un secondo array gli id dei post ai quali abbiamo messo il like.

<!-- Ragionamento  -->
1. Creo un array di oggetti
2. Creo un ciclo forEach per estrarre gli elementi e creare la singola card
3. Creo un pulsante che quando viene cliccato, cambia il colore del testo e incrementa il contatore dei likes e pusha in un secondo array gli id a cui abbiamo messo like