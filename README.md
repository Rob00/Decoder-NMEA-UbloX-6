# Decoder-NMEA-UbloX-6
Programma INCOMPLETO che riceve i dati dal gps tramite porta uart. scritto per Mega2560

Il programma fa parte di un progtto, cercherò di tenerlo aggiornato.

Serve per decodificare tutto quello che entra dall pin 15 (RX3) di arduino Mega2560.
Al momento non decodifica un bel niente, ma memorizza le stringhe che riceve in un array di stringhe.
Questa memorizzazione serve nel caso si voglia fare un utilizzo successivo dei dati già elaborati, 
visto che l'elaborazione stessa li distrugge.

Il numero di stringhe memorizzate è definito dalla costante intera SM. 3
Il gps Ublox 6 emette 10 sentenze ogni lettura. 

Il resto deve ancora venire.

