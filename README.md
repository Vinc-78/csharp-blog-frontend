# csharp-blog-frontend
WebServer che fa chiamate axios per interrogare un WebServer API

Il progetto gestisce l'inserimento di post in un blog attraverso chiamate API sul progetto csharp-blog-backend

la struttura è pensata per avere gli elementi gestiti come componenti che si possono modificare o eliminare in modo indipendente
La home presenta una barra di ricerca che cerca sia nel titolo che nella descrizione

Sono presenti due tasti per l'inserimento dei post, sia se l'immagine che si allega al post, proviene da url che se si inserisce l'immagine da file
Il salvataggio del file avviene sia in locale che su server con conversione in binario dell'immagine

La gestione voluta in parallelo viene mantenuta anche per la view dei dettagli 
In sintesi a lato al post ci sono 5 tasti: 

il primo tasto gestisce la view di dettaglio se il post ha un immagine inserita da file
il secondo ne gestisce la modifica
il terzo gestisce la view di dettaglio se il post ha un immagine inserita da url
il quarto la relativa modifica
il quinto elimina il post da db. 
