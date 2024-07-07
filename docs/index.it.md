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

Dal momento che lavoro quasi esclusivamente con RHEL e visto che sono fermamente convito che RHEL è la scelta migliore in ambienti di produzione, ho scelto di utilizzare una delle distribuzioni disponibili gratuitamente. Zabbix è supportato su Ubuntu, Debian, SuSE, Raspberry... E può essere compilato su qualsiasi sistema operativo basato su Unix, quindi è praticamente impossibile documentarli tutti. Tuttavia, questo libro è open-source e in git, quindi chiunque può contribuire con le proprie preferenze. Io userò [Rocky Linux](https://rockylinux.org/) 9 in questo libro, ma le istruzioni saranno sicuramente valide (con qualche minima variazione) anche su altre distribuzioni.

## What version of Zabbix is used in this book ?

Since we are almost at the release of Zabbix 7, I will focus on version 7 since it will be the new LTS. It should also apply to most other versions but of course there will be minor changes. In the future, if there is enough support from the community to update this book together, it would be great if we could build a book for every LTS version available.


## How to use this book ?

The book will try to cover all the topics, feel free to let me know if something is missing or feel free to make a pull request. 
There is no need to start from page 1 and read the book till the end. Some people will be looking for basic knowledge others might want to skip to the fun part, so I want the book to be useful for everyone. Therefor I will try to explain as best as possible in every topic the exact steps needed to reproduce.
 
There will be moments in the book where you need to type some code, I will show the commands you need to type in a box just like here.

```
# some command 
```

Notes to some useful documentation will be added at the bottom of the page.


Here is a simple footnote[^1]. With some additional text after it.

[^1]: My reference.


In case there is some important information to share I will add notes in the documentation like can be seen here :

???+ note
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

???+ info
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

???+ tip
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

???+ question
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

???+ warning
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

???+ bug
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.

???+ example
    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor massa, nec semper lorem quam in massa.


