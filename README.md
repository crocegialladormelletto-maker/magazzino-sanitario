# Magazzino Sanitario – Croce Gialla Emergenza ODV

Applicazione web autonoma predisposta per hosting statico su Vercel e backend Supabase.

## Stato
- UI Croce Gialla con logo ufficiale e colori giallo/blu
- Login tramite Supabase Auth
- Accesso dati bloccato salvo il Responsabile autorizzato in `mag_responsabili`
- Articoli, categorie, lotti, scadenze, movimenti, ubicazioni, inventario, riordino e dotazioni mezzi 06–09
- Movimenti transazionali lato database con controllo giacenza negativa
- CSV e stampa per le principali viste

## Nota accesso
L’unico indirizzo autorizzato è `magazzinosanitario@crocegiallaemergenza.it`. Al primo accesso il responsabile crea la propria password e, se richiesto, conferma l’indirizzo email.
