Il progetto Spesa è lo sviluppo di un tutorial REST, del prof. Andrea Pollini, per la gestione delle voci di spesa alimentare o di altro.
Attraverso questa applicazione è possibile gestire, aggiungendo le opportune voci di spesa di cui si necessita, una completa e semplice lista spesa: infatti, ad ogni nuova riga generata
è possibile, agendo su un semplice flag modificare lo stato dell'articolo, premendo il tasto "cambia" dichiarare se l'articolo va acquistato, oppure è già presente.
Per una visione migliore e più immediata, sono stati messi in grassetto gli articoli da acquistare.
I dati sono memorizzati in una tabella del db ListaSpesa che si compone di 5 colonne dove vengono memorizzati i dati nei seguenti formati: 
Integer id; String articolo; Boolean spunta; Integer corsia; Integer scaffale.
Una futura estensione prevede l'aggiunta della gestione di vari tipi di negozi da cui la presenza, al momento non utilizzate, delle colonne corsia e scaffale.
Al termine, cliccando sul pulsante "Riepilogo" si ottiene, in una seconda videata, la presentazione della lista, ordinata alfabeticamente.
Cliccando sul pulsante "Invia email" si aprirà il vostro Client e-mail che conterrà l'elenco delle cose da comprare. Basterà fare copia ed incolla dello screenshot della tabella sul messaggio in uscita.
In questo modo si otterrà sulla propria e-mail box una copia consultabile delle voci da acquistare.
Prerequisiti: STS 4 (oppure un plug-in di Spring boot per il vostro ambiente di sviluppo) e MySQL server.
