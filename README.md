# Progetto di Programmazione Sicura (CTF-Format0)

## Descrizione
Questo progetto si concentra sulla risoluzione di una sfida CTF utilizzando la macchina virtuale [Protostar](https://exploit.education/protostar/).

## Team
- Carmine Citro
- Alessandro Cavaliere
- Salvatore Russo

## Obiettivo
Il focus della sfida era risolvere la CTF "Format Zero", con l'obiettivo di manipolare una vulnerabilità di stringhe formattate per impostare la variabile `target` a `0xdeadbeef`.

## Protostar Virtual Machine
Protostar è una macchina virtuale progettata per l'apprendimento della sicurezza informatica, che include esercizi su buffer overflow e vulnerabilità di formato.

## Approccio
Il team ha adottato un approccio mirato all'utilizzo di input inferiori a 10 byte per manipolare la memoria e raggiungere l'obiettivo della sfida. Il progetto è stato strutturato nelle seguenti fasi:
- Raccolta di informazioni sul sistema operativo Debian 6.0.3 (squeeze) i686.
- Analisi del codice sorgente `format0.c`, che utilizza `sprintf` per la gestione delle stringhe.
- Analisi della memoria tramite GDB per comprendere il layout dello stack e individuare la posizione della variabile `target`.

## Risultati e Conclusioni
Il progetto ha offerto agli studenti un'esperienza pratica nella scoperta e mitigazione delle vulnerabilità informatiche, dimostrando l'efficacia nel manipolare il flusso di esecuzione di un 
programma sfruttando vulnerabilità nelle stringhe formattate. 
Questo percorso ha permesso agli studenti di sviluppare competenze cruciali per affrontare vulnerabilità reali nel campo della sicurezza informatica.
