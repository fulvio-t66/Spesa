Il progetto Spesa è lo sviluppo di un tutorial REST per la gestione delle voci di spesa alimentare o di altro.
Attraverso questa applicazione è possibile gestire, aggiungendo le opportune voci di spesa di cui si necessita, una completa e semplice lista spesa: infatti, ad ogni nuova riga generata
è possibile, agendo su un semplice flag, dichiarare se l'articolo va acquistato, oppure è già presente. Per una visione migliore, sono stati messi in grassetto gli articoli da acquistare.
I dati sono memorizzati in una tabella del db ListaSpesa che si compone di 5 colonne dove vengono memorizzati i dati nei seguenti formati: 
Integer id; String articolo; Boolean spunta; Integer corsia; Integer scaffale.
Una futura estensione prevede l'aggiunta della gestione di vari tipi di negozi da cui la presenza, non utilizzate al momento, delle colonne corsia e scaffale.
