# service_status

Lo scopo di questo script è quello di fare ogni tot di tempo dei controlli sui servizi esposti in locale o su internet e assicurarsi del corretto funzionamento, in caso di disservizio viene generato un file e subito parte in catena uno script di invio mail per segnalarci il problema

requisiti:

- almeno 1 server linux dove poter mettere in crontab lo script
- tutti i server devono avere una share condivisa in comune (vedi nfs)
- in questo caso viene utilizzato una componente della suite di SAS per l'invio mail (in alternativa bisogna avere un server mail)
