### ESERCIZIO
Social Posts
Creare una pagina che elenchi una lista di post socials a partire da un array di oggetti.
Gli attributi minimi del modello di un post: id, contenuto, immagine, 
autore (nome, avatar), numero di likes, data creazione.
Un secondo array conterrà solo gli id dei posts a cui abbiamo dato like.

Immagini: va bene utilizzare qualsiasi servizio di placeholder
ad es. Unsplash (https://unsplash.it/300/300?image=<id>)
 *
Bonus 1: Visualizzare la data con formato italiano (gg/mm/aaaa)
Bonus 2: Gestire l'assenza dell'immagine profilo con un elemento di fallback che contiene
le iniziali dell'utente (es. Sofia Perlari > SP)
Bonus 3: Click al pulsante "Mi Piace" incrementa il counter dei like al post.


### SOLUZIONE

Prelevare il contenitore di tutti i post

Per ogni post nell'array
    Creare elemento del post
    Aggiungerlo al contenitore dei posts