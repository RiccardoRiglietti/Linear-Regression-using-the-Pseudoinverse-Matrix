# Matrice pseudoinversa per la regressione lineare

## Introduzione

Sia in scienza che in ingegneria è necessario creare modelli che si adattino ai nostri dati, il più semplice dei quali è un modello lineare.

Il problema di regressione (o fit) lineare consiste nel trovare la retta che si adatta meglio ad una nuvola di punti dati ed è simile al (ma più difficile del) problema di trovare la linea che passa per un gran numero di punti colineari. La difficoltà è che ovviamente non esiste una linea che passa attraverso tutti i punti in una nuvola di punti non colineari, ovvero del tipo che si ottengono da misurazioni sperimentali (considerando le incertezze e la modellizzazione non perfetta dell'esperimento).

Lo scopo di questa lezione è di introdurre la pseudoinversa, lo strumento matematico utilizzato per calcolare la i coefficienti di pendenza e intercetta di un fit lineare, in modo graduale e intuitivo, ed esplorare il potenziale di generalizzazione di tale metodo utilizzando lo stesso codice e gli stessi concetti per stimare i pagamenti per assicurazione medica date altre caratteristiche di salute, un problema di regressione con più variabili di input.
