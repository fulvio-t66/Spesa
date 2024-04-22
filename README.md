#ITA
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

#ENG
The Spesa project is the development of a REST tutorial, by prof. Andrea Pollini, for the management of food and other expenditure items.
Through this application it is possible to manage, by adding the appropriate expense items needed, a complete and simple shopping list: in fact, with each new line generated
it is possible, by acting on a simple flag, to change the status of the item, by pressing the "change" button to declare whether the item must be purchased, or is already present.
For a better and more immediate view, the items to purchase have been highlighted in bold.
The data is stored in a table of the ListaSpesa db which is made up of 5 columns where the data is stored in the following formats:
Integer id; String article; Boolean check; Integer lane; Whole shelf.
A future extension involves the addition of the management of various types of shops, hence the presence, currently unused, of the aisle and shelf columns.
At the end, by clicking on the "Summary" button you obtain, in a second screen, the presentation of the list, ordered alphabetically.
Clicking on the "Send email" button will open your email client which will contain the list of things to buy. Just copy and paste the screenshot of the table into the outgoing message.
In this way you will receive a consultable copy of the items to be purchased in your e-mail box.
Prerequisites: STS 4 (or a Spring boot plugin for your development environment) and MySQL server.
