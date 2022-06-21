# csharp-blog-frontend
WebServer che fa chiamate axios per interrogare un WebServer API

Il progetto gestisce l'inserimento di post in un blog attraverso chiamate API sul progetto csharp-blog-backend

la struttura è pensata per avere gli elementi gestiti come componenti che si possono modificare o eliminare in modo indipendente
La home presenta una barra di ricerca che cerca sia nel titolo che nella descrizione

Sono presenti due tasti per l'inserimento dei post sia se l'immagine che si ha proviene da url sia se si inserisce file
Il salvataggio del file avviene sia in locale che su server

La gestione voluta in parallelo viene mantenuta anche per la view dei dettagli ( il primo e terzo bottone di lato al post )
che per l'update ( il secondo e quarto bottone ) 
