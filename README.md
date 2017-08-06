# fortunes
Raccolta di file fortunes creati da me da usare con 
fortune-mod

installazione
apt install fortune-mod -y
copiare i file .dat dentro a /usr/share/games/fortunes/
avviare 
fortune [nome archivio dat1] [archivio dat2] oppure solo fortune -a per avviarli tutti

attenzione per crearli usa file con le frasi separate da una riga con solo un % e ASSOLUTAMENTE il codice di capo riga deve essere LF di linux!
poi usare strfile [nome del file], creerà un file .dat da usare
