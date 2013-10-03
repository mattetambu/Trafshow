=============================
Trafshow
=============================

 Progetto:
	Trafshow
	
 Autore:
	Tamburini Matteo <mattetambu@gmail.com>
	
 Descrizione: 
	Aggiungere un opzione al port trafshow che permetta di esportare periodicamente 
	le statisctiche su file in un formato che renda semplice la realizzazione di grafici.

 Caratteristiche aggiunte al port trafshow:
	Options:
		-e <time>
					Enable the export of the network stats for all the interfaces whit period <time>.
					In each file will be exported <time> seconds of traffic (elapsed <time> seconds the export file will be changed automatically)
	Commands:
		'e'			Begin to export the network stats for the selected interface (require <time> as input)
		CTRL-'e'	Stop to export the network stats for the selected interface

 Esempi:
	La cartella example contiene una directory NETSTAT creata come risultato di una esecuzione e
	un insieme di grafici di esempio ottenuti dai dati esportati e realizzati tramite matlab e excel.
	