# Di cosa parla questo libro?

Benvenuti e grazie per l'interesse per il mio libro su Zabbix. Ho scritto [Zabbix cookbook](https://www.packtpub.com/product/zabbix-cookbook/9781784397586) and co wrote with Richards [Zabbix 4 Network Monitoring](https://www.packtpub.com/product/zabbix-4-network-monitoring-third-edition/9781789340266) qualche tempo fa per PackPub.

![Zabbix cookbook](images/book1.png) ![Zabbix Network Monitoring 4](images/book2.png)

Il "ricettario", primo nel suo genere, probabilmente datato, verrà sostituito da [Zabbix 7 IT Infrastructure Monitoring Cookbook](https://www.packtpub.com/product/zabbix-7-it-infrastructure-monitoring-cookbook-third-edition/9781801078320), scritto da Brian e Nathan, persone con le quali ho lavorato con piacere e che raccomando caldamente. Ci sono molti libri disponibili da Packt su Zabbix. Una panoramica completa è disponibile qui: [Zabbix books at pack](https://www.packtpub.com/search?query=zabbix). Se preferite cercare libri che non siano in lingua inglese, su Amazon sono disponibili libri editi da Packt e altri  editori in cinese, spagnolo e possibilmente anche in altre lingue. [Other books](https://www.amazon.com/s?k=zabbix&crid=3G0JRTVTKS7YU&sprefix=zabbix+%2Caps%2C167&ref=nb_sb_noss_2)

Poiché Zabbix è un prodotto open-source, fare soldi da un libro non è mia intenzione, perciò ho pensato di fare le cose diversamente.

Come realizzare un libro senza passare per un editore, come ho fatto invece in passato? 
Dopo un po' ho avuto un idea di un libro gratis e aggiornato costantemente.
Visto che sono un grande sostenitore della documentazione in formato markdown e/o ascii ho avuto l'idea di diffondere questo libro con Git e utilizzare il formato markdown.
L'unico problema rimasto era: come far sì che che i files md fossero leggibili facilmente come un vero libro? Dopo aver fatto delle ricerche ho trovato [MkDocs](https://www.mkdocs.org). MkDocs è una libreria Python-Markdownche converte tutto in HTML e che può fungere anche da modello di documentazione personalizzabile. In questo modo il problema è risolto e il libro è nato.

## Chi sono?

Il mio nome è Patrik Uytterhoeven e lavoro per un'azienda belga chiamata Open-Future. Ho iniziato a lavorare per questa azienda nel gennaio 2013 e da allora ho iniziato il mio "viaggio" con Zabbix. 
Mi è stata data l'opportunità di accrescere la mia esperienza e diventare istruttore certificato di Zabbix.
Da quest'anno sono ufficialmente istruttore di Zabbix da dieci anni. Per seguire uno dei miei corsi è sufficiente registrarsi sul sito [www.open-future.be](https://www.open-future.be). 
Perché bisognerebbe seguire un corso quando si può leggere un libro  gratuitamente? Perché seguire un corso svela tutti i dettagli su come realizzare una soluzione di monitoraggio efficente che un semplice libro non potrà mai dare. I libri non possono spiegare tutto quanto.

## Che sistema operativo serve?

Dal momento che lavoro quasi esclusivamente con Red Hat Enterprise Linux (d'ora in poi RHEL). Sebbene io sia fermamente convito che RHEL sia la scelta migliore in ambienti di produzione, in questo libro ho scelto di utilizzare una delle distribuzioni disponibili gratuitamente. Zabbix è supportato su Ubuntu, Debian, SuSE, Raspberry... E può essere compilato su qualsiasi sistema operativo basato su Unix, quindi è praticamente impossibile documentarli tutti. Tuttavia, questo libro è open-source e in git, quindi chiunque può contribuire con le proprie preferenze. Io userò [Rocky Linux](https://rockylinux.org/) 9 in questo libro, ma le istruzioni saranno sicuramente valide (con qualche minima variazione) anche su altre distribuzioni.

## Quale versione di Zabbix è utilizzata in questo libro?

Questo libro utilizza la versione 7.x LTS (acronimo che sta per Long Term Support). Le istruzioni contenute in questo libro sono valide anche per le altri versioni con qualche variazione. In futuro, se ci sarà sufficiente supporto dalla community per la stesura di questo libro, sarebbe magnifico scrivere un libro per ogni versione LTS.

## Come utilizzare questo libro?

Questo libro cercherà di coprire tutti quanto gli argomenti ma se qualcosa manca fatemelo sapere, fate una richiesta pull. Non c'è bisogno di leggere questo libro da copertina a copertina: chi è alle prime armi probabilmente lo farà, altri possono saltare delle parti se non sono necessarie. Vorrei che questo libro sia veramente utile per tutti. Perciò, cercherò di spiegare ogni argomento al meglio, illustrando tutti quanti i passi nella maniera migliore.

Il codice illustrato in questo libro verrà scritto come segue (con la possibilità di copiarlo direttamente): 
```
codice 
```

Altre annotazioni utili verrando indicate a piè di pagina:

Esempio di nota a piè di pagina[^1] con un testo aggiuntivo.

[^1]: Qui si troveranno informazioni aggiuntive.

Le altre informazioni importanti verranno mostrate come segue:

[!NOTE]  
Evidenzia informazioni di cui gli utenti dovrebbero tenere conto.

[!TIP]
Informazioni facoltative per aiutare un utente a migliorare il proprio codice.

[!IMPORTANT]  
Informazioni  necessarie affinché l'utente riesca a utilizzare una certa funzione.

[!WARNING]  
Contenuti importanti che richiedono l'attenzione immediata dell'utente per evitare potenziali rischi.

[!CAUTION]
Possibili conseguenze negative di un'azione da evitare.
