# 📋 Calcolatore SF-12 (Indici PCS e MCS)

Un'applicazione web standalone e interattiva per il calcolo automatico dei punteggi **PCS (Physical Component Summary)** e **MCS (Mental Component Summary)** basati sul questionario sullo stato di salute SF-12 (Short Form Health Survey).

L'applicazione è progettata per essere semplice, veloce e per offrire un riscontro visivo immediato all'utente o al professionista.

## Caratteristiche Principali

* **Calcolo Immediato:** Inserimento rapido delle 12 risposte e calcolo automatico dei punteggi standardizzati in base ai coefficienti normativi.
* **Visualizzazione Avanzata (Dashboard Grafica):**
    * Barre verticali con scala cromatica (rosso/giallo/verde).
    * Tachimetri (Gauge) per la visualizzazione dei punteggi PCS e MCS.
    * Barre di progresso lineari.
    * Grafico di confronto con la media della popolazione generale (fissata a 50).
    * Scala interpretativa da "Scarso" a "Eccellente".
* **Esportazione Dati:**
    * **CSV:** Per l'analisi in Excel o altri fogli di calcolo.
    * **JSON:** Per l'integrazione con altri software o database.
    * **Report PDF:** Generazione di un documento impaginato contenente i risultati numerici e i grafici renderizzati, pronto per la stampa o l'archiviazione.
* **Privacy-First:** L'intero calcolo avviene lato client (nel browser dell'utente). Nessun dato medico o personale viene inviato a server esterni.

## Tecnologie e Librerie Utilizzate

Il progetto è costruito interamente con **HTML5, CSS3 e Vanilla JavaScript**. Non richiede framework pesanti (come React o Angular) né un backend.

Fa uso delle seguenti librerie esterne incluse via CDN:
* [Chart.js](https://www.chartjs.org/) - Per il rendering di tutti i grafici.
* [html2canvas](https://html2canvas.hertzen.com/) - Per catturare i risultati visivi e trasformarli in immagini.
* [jsPDF](https://parall.ax/products/jspdf) - Per la generazione del file PDF finale.

## Come si usa

Essendo un'applicazione interamente statica (client-side), l'installazione è immediata:

1. Clona questo repository:
   ```bash
   git clone [https://github.com/danielelozzi/sf12.git](https://github.com/danielelozzi/sf12.git)
   ```
2. Apri la cartella del progetto.
3. Fai doppio clic sul file `index.html` per aprirlo nel tuo browser web preferito (Chrome, Firefox, Safari, Edge).

*Non è necessario alcun web server, Node.js o database.*

## Disclaimer Medico

*Questo strumento è stato sviluppato a scopo informativo e di ricerca. I punteggi generati non costituiscono una diagnosi medica. Per qualsiasi valutazione clinica, fare riferimento a un professionista sanitario qualificato.*

## Citazione

Questo strumento è basto sul codice dell'Università di Bologna

[https://amsacta.unibo.it/id/eprint/5751/](https://amsacta.unibo.it/id/eprint/5751/)

DOI: 10.6092/unibo/amsacta/5751

