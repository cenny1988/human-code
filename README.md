# human-code
//Richiesta base:- implementare un layout assegnato come esercitazione pomeridiana
Accedo a GitHub

Creo un nuovo repo

Apro VSC e clono il repo

Analizzo la macrostruttura del layout 

? SE esistono macro-sezioni riutilizzabili 
-	creo una nota
:ALTRIMENTI
-	vado avanti finchè non termino l’analisi

Creazione file e collegamento tra essi

?SE le operazioni sono molte eseguo un stage ed un commit

?SE non è terminata la stesura delle macro-aree
-	creo la nuova macro-area
:ALTRIMENTI 
-	eseguo un commit e un push

Inizia la creazione dei contenuti e dello style

?FINCHE’ non termino la macro-sezione con contenuti e style
-	eseguo implementazione codice e verifica
    ?SE la verifica è ok 
        -	commit 
    :ALTRIMENTI
        -	revisione codice errato

Fase di testing finale

?SE si verificano problemi
-	revisione codice, commit.
:ALTRIMENTI
-	Push finale e inoltro per correzione




// attraversare un incrocio sulle strisce (c’è il semaforo?)
Mi fermo al ciglio dell'incrocio

Controllo la presenza del semaforo
?SE non c'è
    - controllo la segnaletica
    - FINCHE' non trovo scrisce pedonali, avanzo sul mio lato del marciapiede

    - controllo la direzione delle auto

    - controllo la presenza di auto in avvicinamento
    ?SE sono in transito
        - controllo che si femrino per farmi attraversare
        ?SE si fermano
            - attraverso
        :ALTRIMENTI 
            - attendo
    :ALTRIMENTI
        - attraverso
:ALTRIMENTI
    - controllo stato semaforo
    ?SE è rosso
        - attendo
    :ALTRIMENTI
        - attraverso


