Consegna
L'utente clicca su un bottone che genererà una griglia di gioco quadrata.
Ogni cella ha un numero progressivo, da 1 a 100.
Ci saranno quindi 10 caselle per ognuna delle 10 righe.
Quando l'utente clicca su ogni cella, la cella cliccata si colore di azzurro ed emetto un messaggio in console con il numero della cella cliccata.

1 sul bottone play dove l'utente clicchera ci agganciamo un event listener che nel momento che attivato va ad inserire nel main tutte le caselle.
Dobbiamo tener conto che ogni volta che creaiamo le caselle quelle nuove saranno sovrascitte a quelle vecchie.

2 Con l'inserimento delle caselle nel main tramite un ciclo for la variabile che usciamo per il ciclo può essere utilizata come indice della casella.

3 le dimmensioni delle caselle quindi quante ne entrano in una righa le andiamo a definire nel css.

4sempre nel ciclo for che utiliziamo per la creazione delle celle ad ogni cella creata ci agganciamo un event listener che al click sulla casella aggiungera una classe che gli cambierà colore un console.log che gli farà stampare l'indice in console.

Bonus
Aggiungere una select accanto al bottone di generazione, che fornisca una scelta tra tre diversi livelli di difficoltà:

- con difficoltà 1 => 100 caselle, con un numero compreso tra 1 e 100, divise in 10 caselle per 10 righe;
- con difficoltà 2 => 81 caselle, con un numero compreso tra 1 e 81, divise in 9 caselle per 9 righe;
- con difficoltà 3 => 49 caselle, con un numero compreso tra 1 e 49, divise in 7 caselle per 7 righe;
