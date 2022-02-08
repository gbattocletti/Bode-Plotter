# Bode-Plotter
Applicazione per disegnare il diagramma di Bode di filtri passivi del primo ordine. Creata con MATLAB App Designer.

## Utilizzo
Il pannello di controllo sulla sinistra permette di scegliere tra quattro filtri di primo ordine:
- RC (passa-basso)
- CR (passa-alto)
- RL (passa-alto)
- LR (passa-basso)
Per ciascuno dei quattro circuiti viene data la possibilità di scegliere il valore dei componenti presenti. I menù a cascata sulla destra permettono di scegliere l'ordine di grandezza del componente (ad esempio, consentono di passare da Ohm a kOhm e a MOhm, che corrispondono rispettivamente a 10^0 Ohm, 10^3Ohm e 10^6Ohm.

Una volta scelto il valore dei componenti, è sufficiente fare click sul pulsante "Calcola Grafico" per ottenere il diagramma di Modulo e Fase della funzione di trasferimento corrispondente al circuito scelto. È anche possibile salvare i due grafici premendo il pulsante "Salva Immagine". Le immagini vengono salvate in formato .png nella stessa cartella da cui è stato aperto il programma.

È anche possibile interagire con i grafici attraverso i pulsanti di zoom (le lenti d'ingrandimento coi simboli + e -), o trascinando la finestra del grafico per muoversi al suo interno. Per ripristinare la visualizzazione iniziale è sufficiente premere il pulsante a forma di casa.
