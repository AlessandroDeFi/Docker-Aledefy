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

7) 