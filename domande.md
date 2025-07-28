1) Cos'è un container ?



2) Che relazione cìè tra immagine e container ?

l'immagine di un container docker è un modello solo di lettura che contiene le istruzioni per la creazione di un container, quindi un'immagine è uno snapshot delle librerie e delle dipendenze necessarie per l'esecuzione dell'applicazione, è quindi come una specie di file system (metafora: container=oggetto immagine=classe l'oggetto viene istanziato dalla classe)

3) Cos'è un'immagine ?



4) il container è strettamente legato a docker ?

No, si associa spesso a docker perchè è l'azienda che ha reso i container accessibili a tutti quanti, esiste quindi da prima di quando esiste docker

5) cos'è podman ?

un motore

6) differenze tra docker e podman

docker = linux mac windows
podman = linux

docker richede accesso root 
podman no

docker:central daemon (programma eseguito in background)
podman: daemonless

7) come si chiamano le interfacce standard di un container 



8) docker compose e Kubernetes cosa sono ?

strumenti per la gestione di applicazioni containerizzate

9) quali sono i principali vantaggi di Kubernetes ?

- riduzione dei tempi di sviluppo = facilita l'integrazione dei container ed è ottimo per la gestione di architetture a microservizi
- ottimizzazione dei costi = grazie alla amministrazione dinamica e smart dei container
- maggiore scalabilità 
- flessibilità in ambienti cloud 
- percorsi per la migrazione sul cloud

10) quali sono i principali svantaggi di Kubernetes ?

- le conoscenze che richiede sono spesso troppe e troppo trasversali
- YAML un linguaggio che non è un linguaggio, dipende troppo dalle immagini e il livello di astrazione richiesto è spesso troppo alto
- è vero che è ottimo nella gestione di microservizi ma per l'impostazione di kubernetes è facile che si creino falle nel sistema

11) conclusioni

kubernetes è quindi un'ottima tecnologia ma che molto probabilmente presto verrà sostituita per via della complessità eccessiva



