
WORTH: WORkTogetHer

1. Descrizione del problema
Negli ultimi anni sono state create numerose applicazioni collaborative, per la condivisione di contenuti,
messaggistica, videoconferenza, gestione di progetti, ecc. In questo progetto didattico, WORTH
(WORkTogetHer), ci focalizzeremo sull’organizzazione e la gestione di progetti in modo collaborativo. Le
applicazioni di collaborazione e project management (es. Trello, Asana) aiutano le persone a organizzarsi e
coordinarsi nello svolgimento di progetti comuni. Questi possono essere progetti professionali, o in
generale qualsiasi attività possa essere organizzata in una serie di compiti (es. to do list) che sono svolti da
membri di un gruppo: le applicazioni di interesse sono di diverso tipo, si pensi alla organizzazione di un
progetto di sviluppo software con i colleghi del team di sviluppo, ma anche all’organizzazione di una festa
con un gruppo di amici.
Alcuni di questi tool (es. Trello) implementano il metodo Kanban (cartello o cartellone pubblicitario, in
giapponese), un metodo di gestione “agile”. La lavagna Kanban fornisce una vista di insieme delle attività e
ne visualizza l’evoluzione, ad esempio dalla creazione e il successivo progresso fino al completamento,
dopo che è stata superata con successo la fase di revisione. Una persona del gruppo di lavoro può prendere
in carico un’attività quando ne ha la possibilità, spostando l’attività sulla lavagna.
Il progetto consiste nell’implementazione di WORkTogetHer (WORTH): uno strumento per la gestione di
progetti collaborativi che si ispira ad alcuni principi della metodologia Kanban.
2. Specifica delle operazioni
Gli utenti possono accedere a WORTH dopo registrazione e login.
In WORTH, un progetto, identificato da un nome univoco, è costituito da una serie di “card” (“carte”), che
rappresentano i compiti da svolgere per portarlo a termine, e fornisce una serie di servizi. Ad ogni progetto
è associata una lista di membri, ovvero utenti che hanno i permessi per modificare le card e accedere ai
servizi associati al progetto (es. chat).
Una card è composta da un nome e una descrizione testuale. Il nome assegnato alla card deve essere
univoco nell’ambito di un progetto. Ogni progetto ha associate quattro liste che definiscono il flusso di
lavoro come passaggio delle card da una lista alla successiva: TODO, INPROGRESS, TOBEREVISED, DONE.
Qualsiasi membro del progetto può spostare la card da una lista all’altro, rispettando i vincoli illustrati nel
diagramma in FIG. 1.
Le card appena create sono automaticamente inserite nella lista TODO. Qualsiasi membro può spostare una
card da una lista all’altra. Quando tutte le card sono nella lista DONE il progetto può essere cancellato, da
un qualsiasi membro partecipante al progetto.
Ad ogni progetto è associata una chat di gruppo, e tutti i membri di quel progetto, se online (dopo aver
effettuato il login), possono ricevere e inviare i messaggi sulla chat. Sulla chat il sistema invia inoltre
automaticamente le notifiche di eventi legati allo spostamento di una card del progetto da una lista
all’altra.
1
FIG.1
Un utente registrato e dopo login eseguita con successo ha i permessi per:

● recuperare la lista di tutti gli utenti registrati al servizio;

● recuperare la lista di tutti gli utenti registrati al servizio e collegati al servizio (in stato online);

● creare un progetto;

● recuperare la lista dei progetti di cui è membro.

Un utente che ha creato un progetto ne diventa automaticamente membro. Può aggiungere altri utenti
registrati come membri del progetto. Tutti i membri del progetto hanno gli stessi diritti (il creatore stesso è
un membro come gli altri), in particolare:

● aggiungere altri utenti registrati come membri del progetto;

● recuperare la lista dei membri del progetto;

● creare card nel progetto;

● recuperare la lista di card associate ad un progetto;

● recuperare le informazioni di una specifica card del progetto;

● recuperare la “storia” di una specifica card del progetto (vedi seguito per dettagli);

● spostare qualsiasi card del progetto (rispettando i vincoli di Fig.1);

● inviare un messaggio sulla chat di progetto;

● leggere messaggi dalla chat di gruppo;

● cancellare il progetto.
