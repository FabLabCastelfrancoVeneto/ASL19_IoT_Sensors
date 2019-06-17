# ASL19_IoT_Sensors
## ASL FabLab Castelfranco Veneto

Abbiamo utilizzato :   **Scheda RaspberryPi**

                                      **Arduino 1**  con :

-  sensore DHT22 ( temperatura, umidità )
-  sensore Luminosità
-  sensore RFID

                                      **Wemos D1 Mini** con:

- sensore DHT22 ( temperatura, umidità )





**RaspberryPi**  Il Raspberry Pi è un [single-board computer](https://it.wikipedia.org/wiki/Single-board_computer) sviluppato nel [Regno Unito](https://it.wikipedia.org/wiki/Regno_Unito) dalla [Raspberry Pi Foundation](https://it.wikipedia.org/wiki/Raspberry_Pi_Foundation). La scheda è stata progettata per ospitare sistemi operativi basati sul [kernel](https://it.wikipedia.org/wiki/Kernel) [Linux](https://it.wikipedia.org/wiki/Linux_(kernel)) o [RISC OS](https://it.wikipedia.org/wiki/RISC_OS)
![1](/IMAGE/1.jpg)





**Arduino** Arduino è una [piattaforma](https://it.wikipedia.org/wiki/Piattaforma_(informatica)) [hardware](https://it.wikipedia.org/wiki/Hardware) composta da una serie di [schede elettroniche](https://it.wikipedia.org/wiki/Scheda_elettronica) dotate di un [microcontrollore](https://it.wikipedia.org/wiki/Microcontrollore). Con Arduino si possono realizzare in maniera relativamente rapida e semplice piccoli [dispositivi](https://it.wikipedia.org/wiki/Dispositivo_(informatica)) come controllori di luci, di velocità per motori, sensori di luce, automatismi per il controllo della temperatura e dell&#39;umidità e molti altri progetti che utilizzano [sensori](https://it.wikipedia.org/wiki/Sensori), [attuatori](https://it.wikipedia.org/wiki/Attuatori) e comunicazione con altri dispositivi.

 ![](data:image/*;base64,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)

**Sensore dht22**  Rileva Umidità(%) e Temperatura(C)

                                                                                                          **Sensore Luminosità**  Rileva la  luminosità



**Scheda RFID**    Lettore Schede magnetiche









**Wemos D1 MINI** Il Modulo [WeMos D1 mini ](https://www.adrirobot.it/wemos_d1_mini/wemos_d1_mini.htm)è basato sul microcontrollore Wi-Fi ESP8266 ESP-12F che può essere programmato utilizzando l&#39;IDE di Arduino oppure NodeMCU. La semplicità della programmazione che può essere effettuata anche in modalità wireless e l&#39;ampia disponibilità di shield aggiuntivi permettono di sviluppare il proprio progetto di &quot;Internet delle cose&quot; in tempi estremamente rapidi.







**SOFTWARE:**



**-Node-RED** è un software open source per programmare online contemporaneamente ad altre persone sullo stesso hardware creando dei &quot;flow&quot; a blocchi sfruttando principalmente Javascript, MQTT e JSON.

**-Emoncms.org** è una piattaforma online  per chiunque sia interessato alla programmazione ma soprattutto per l&#39;elaborazione e visualizzazione tramite dashboard e grafici di dati in input come energia, luminosità, temperatura ed in generale dati ambientali.



Per salvare ed elaborare i dati provenienti da alcuni sensori abbiamo usufruito di EMONCMS che, in primo luogo, ci ha permesso di salvare i dati in un server gratuito e di poterli rivedere tramite la sezione &quot;inputs&quot;; in secondo luogo di creare delle &quot;dashboards&quot;, ovvero delle schermate che ti permettono di monitorare in tempo reale l&#39;andamento dei report.

1. 1)
# Dati in arrivo dal sensore


Tramite il &quot;flow&quot; in sovraimpressione, prima rivisto e spiegato, arrivano i dati al sensore nel database, qui vengono gestiti e raggruppati in sezioni. Nel nostro caso abbiamo diviso i dati in input in:

-Luminosità

-Temperatura

-Umidità

I dati, qualora il sensore fosse sempre attivo, vengono cambiati in tempo reale e sono visibili nella sezione &quot;inputs&quot; di Emoncms.



Avendo utilizzato 2 sensori, come si può vedere, abbiamo le 3 sezioni per entrambi i sensori, con differenti valori.

#

# 2) Feeds

Le &quot;feeds&quot; gestiscono la memorizzazione dei dati degli input e si occupano di passarli al modulo successivo. Sempre all&#39;interno di questo modulo si può visualizza l&#39;attività di invio dei dati

#  3) Dashboards e visualizzazione finale dei dati

#

Come potete vedere dall&#39;immagine soprastante, tramite l&#39;utilizzo delle dashboards si è potuti ad arrivare ad un risultato grafico dei dati arrivati in input. Queste dashboards però non sono esportabili, e sono visibili soltanto nel caso in cui si è nella stessa wifi della raspberry e si ha l&#39;account ad emoncms relativo.

Anche in questo caso i dati cambiano in tempo reale a sensore attivo.
