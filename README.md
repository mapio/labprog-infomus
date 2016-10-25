# Leioni del laboratorio di "Programmazione" del corso di "Informatica Musicale"

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)
[![License: CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/80x15.png)](http://creativecommons.org/licenses/by-sa/4.0/)

Questo repository contiene i testi degli esercizi del [laboratorio](https://santini.di.unimi.it/d/labprog/) dell'insegnamento di [Programmazione](http://www.ccdinfmi.unimi.it/it/corsiDiStudio/2017/F3Xof2/default/F3X-36/index.html) del corso di laurea in [Informatica Musicale](http://www.ccdinfmi.unimi.it/it/corsiDiStudio/2017/F3Xof2/), suddivisi in una directory per ciascuna lezione.

Il contenuto relativo ad una lezione coincide sostanzialmente con quanto descritto nella guida "[Istruzioni
per lo svolgimento degli esercizi del laboratorio di
programmazione](https://santini.di.unimi.it/d/labprog/laboratorio.html)" a cui si rimanda per maggiori informazioni.

## A casa

Chi intendesse utilizzare questo materiale al di fuori del laboratorio (ad esempio per esercitarsi a casa, o per prepararsi all'esame) può scaricare un [archivio compresso](https://github.com/mapio/labprog-infomus/archive/master.zip) di questo repository, oppure ottenere un *clone* locale con il comando `git clone git@github.com:mapio/labprog-infomus.git`; in questo caso si osserva che:

- il comando `firma` non è definito, non è infatti prevista una modalità di autenticazione
  nel caso di utilizzo al di fuori del laboratorio;

- non è presente il file `LEGGIMI.md`, sostituito da questo file;

- non è presente la directory `bin/`, il cui contenuto è utile, e disponibile,
  solo nel contesto del laboratorio;

- per poter eseguire i *test* è necessario definire la variabile d'ambiente
  `MAKEFILES` in modo che contenga il percorso assoluto del file `Makefile`
  (tale variabile risulta viceversa già  definita nell'ambiente di laboratorio).

Se si usa l'interprete di comandi `bash`, la variabile d'ambiente `MAKEFILES` può
essere definita semplicemente portandosi nella directory in cui è contenuto questo
file `README.md` ed impartire il comando

	export MAKEFILES=$(pwd)/Makefile

## In laboratorio

Durante lo svolgimento delle lezioni, il materiale contenuto in questo repository sarà reso disponibile agli studenti tramite [Tristo Mietitore](https://github.com/mapio/tristo-mietitore), [See you](https://github.com/mapio/see-you) e [See you viewer](https://github.com/mapio/see-you-viewer), una *suite* di strumenti che consentono la somministrazione, raccolta e valutazione di esercizi di programmazione.

Il docente provvederà le necessarie istruzioni durante lo svolgimento delle lezioni.

## Nota di copyright

I testi ed i sorgenti contenuti in questo repository sono protetti dalle leggi sul copyright e dalle disposizioni dei trattati internazionali; in particolare ai testi si applica la [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/) ed ai sorgenti la [GNU General Public License 3](https://www.gnu.org/licenses/gpl-3.0.html).

L'informazione qui contenuta è ritenuta essere accurata alla data della pubblicazione. Essa è fornita per scopi esclusivamente didattici e non per essere utilizzata in progetti di impianti, prodotti, ecc. Tale informazione è soggetta a cambiamenti senza preavviso. L'autore non si assume alcuna responsabilità per il contenuto di queste pagine (ivi incluse, ma non limitatamente a, la correttezza, completezza, applicabilità ed aggiornamento dell'informazione). In ogni caso non può essere dichiarata conformità all'informazione in oggetto.

In ogni caso questa nota di copyright non deve mai essere rimossa e deve essere riportata anche in utilizzi parziali.

© Massimo Santini 2016
