PMS
===

Installazione

1) Estrarre l'archivio sul vostro web server, potete estrarre nella root directory oppure in una sottocartella a vostra scelta.

2) Aprire il file config.php contenuto nella cartella scripts/. Dovrete modificare ciò che si trova tra le virgolette "" senza rimuoverle. 

$nome_gioco = "NomeGioco"; 

Scrivete il nome del vostro GDR tra le virgolette(esempio: "D&D Prova" )

$nome_cartella = "nomecartella";

Scrivete qui il nome della sottocartella in cui avete estratto PMS.
Se PMS è estratto nella root directory del vostro hosting, lasciate esclusivamente "" (ossia vuoto)

$db_host = "localhost";

Inserite l'indirizzo del database su cui PMS girerà.(esempio : "123.123.123.123" ma il più delle volte è localhost )

$db_username = "username_db";

Inserite l'username del vostro database. (esempio : "Pippo" )

$db_password = 'password_db';

Inserite la password del vostro database. (esempio : "SuperPasswordSicura" )

$db_nome = 'nome_database';

Inserite il nome del vostro database (esempio : "db_pms" ). Deve esser stato creato già in precedenza. 

3) Adesso dovete avviare l'installazione. 
Se avete installato PMS nella root directory del vostro dominio, l'installazione partirà digitando nel browser :

www.miodominio.it/installazione/avvia_installazione.php

Se avete installato PMS in una sottocartella, l'installazione partirà digitando nel browser : 

www.miodominio.it/nomesottocartella/installazione/avvia_installazione.php
