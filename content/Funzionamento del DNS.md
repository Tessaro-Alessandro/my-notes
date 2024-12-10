[[DNS]]

## Funzionamento del DNS

Quando un utente inserisce un URL nel browser, il DNS inizia un processo noto come **risoluzione dei nomi**. Questo processo coinvolge diversi componenti chiave:

- **Resolver DNS Ricorsivo**: Si tratta di un server che riceve la richiesta dal client e cerca di risolvere il nome di dominio in un indirizzo IP. Se non ha già l'informazione nella sua cache, interroga altri server DNS per ottenere la risposta

- **Root Nameserver**: Questo è il primo punto di contatto nel processo di risoluzione. Indica al resolver quali server sono responsabili dei domini di primo livello (TLD), come .com o .it

- **TLD Nameserver**: Questi server gestiscono i domini di primo livello e forniscono informazioni sui nameserver autoritativi per i domini specifici

- **Nameserver Autoritativo**: Questi server contengono le informazioni definitive sui domini e forniscono l'indirizzo IP corretto al resolver

## Struttura Gerarchica

Il DNS è organizzato in una struttura gerarchica ad albero rovesciato. Ogni dominio è composto da vari livelli separati da punti.

- "com" è il dominio di primo livello.
- "example" è il dominio secondario.
- "www" è un sottodominio.

Questa struttura consente una gestione scalabile e distribuita delle informazioni sui nomi di dominio
## Cache DNS

Per migliorare l'efficienza, i server DNS utilizzano la **cache**, memorizzando temporaneamente le informazioni sui domini già risolti. Questo riduce i tempi di risposta per richieste successive allo stesso dominio, poiché non è necessario interrogare nuovamente i server autoritativi ogni volta



Il DNS è spesso descritto come l'"elenco telefonico" di Internet. Senza di esso, gli utenti dovrebbero ricordare gli indirizzi IP per accedere ai siti web, rendendo l'esperienza online molto meno user-friendly. Inoltre, il DNS supporta anche funzionalità avanzate come il **Dynamic DNS (DDNS)**, che consente l'aggiornamento automatico dei record DNS quando gli indirizzi IP cambiano frequentemente[

1

](https://www.acs.it/it/blog/digitalizzazione-aziendale/dns-definizione/)[

5

](https://www.creativemotions.it/cosa-e-il-dns/). In sintesi, il DNS svolge un ruolo cruciale nell'accessibilità e nell'usabilità di Internet, fungendo da intermediario tra nomi comprensibili e indirizzi IP necessari per la comunicazione tra dispositivi.