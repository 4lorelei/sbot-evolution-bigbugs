== PROCEDURE PER L'AMMINISTRAZIONE DEL BOT LaraLuu 4.0 ==


================== CHESTNUT ANTEPRIMA ===================

Per predisporre il bot ad una nuova gara, preceduta dall'anteprima, predisporre i seguenti file a partire dai file presenti in FILE CARATTERISTICI/Anteprima

- Creare il file restore.txt 
- Creare il file monitor.txt 
- Creare il file livello.txt 
- Creare il file anagrafica.txt 
- Modificare il file amministratore.txt
- Aggiornare il file about_.txt
- Aggiornare il file black_list.txt 
- Aggiornare il file domande.xml 

Avviare il bot con il comando /match go -s
Sospendere il bot con il comando /match sleep -s prima di effettuare i backup e riavviare il bot


===================== CHESTNUT GARA ===================== 

Per passare da CHESTNUT ANTEPRIMA all'assetto di gara, fare riferimento ai file presenti in FILE CARATTERISTICI/Gara

- Effettuare il reset del bot con il comando /reset game

- Mettere in linea il file livello.txt prdotto dopo il reset 
  livello.txt può essere recuperato ad un link del tipo
  https://sbot-evolution-bigbugs.herokuapp.com/livello.txt
- Modificare il file amministratore.txt a partire dal file presente in FILE CARATTERISTICI/Gara
- Aggiornare il file domande.xml a partire dal file presente in FILE CARATTERISTICI/Gara

Dopo aver messo in linea i file ripetere il comando /reset game
La prima volta avviare il bot con il comando /match start -t gg/mm/aaaa hh:mm
Sospendere il bot con il comando /match sleep -t gg/mm/aaaa hh:mm (è obbligatorio l'uso del comando a tempo per rendere valido il meccanismo di sospensione del tempo)
Dopo i backup portare il bot in pausa con il comando /match sleep -s
Avviare il bot con il comando /match go -t gg/mm/aaaa hh:mm (è obbligatorio l'uso del comando a tempo per rendere valido il meccanismo di sospensione del tempo)


==================== CHESTNUT REPLAY ==================== 

Per passare dall'assetto di gara all'assetto "Chestnut Replay" fare riferimento ai file presenti in FILE CARATTERISTICI/Gara

- Creare il file restore.txt a partire dal file presente in FILE CARATTERISTICI/Replay
- Creare il file monitor.txt a partire dal file presente in FILE CARATTERISTICI/Replay
- Modificare il file amministratore.txt a partire dal file presente in FILE CARATTERISTICI/Replay
- Aggiornare il file about_.txt a partire dal file presente in FILE CARATTERISTICI/Replay
- Aggiornare il file black_list.txt a partire dal file presente in FILE CARATTERISTICI/Replay
- Aggiornare il file domande.xml partire dal file presente in FILE CARATTERISTICI/Replay

