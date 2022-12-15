# impariamoGH
## Lezione 1 - GITHUB WEB 
* [Introduzione a GITHUB (Per la Didattica)](https://docs.google.com/presentation/d/e/2PACX-1vQy6yuKZ_ewYe0XDskxTbNPvuUHiLfyMVasIEB7YVqZw9NObtHhF3joL_XDw2nBadLHdl5Ute6rAfOQ/pub?start=false&loop=false&delayms=10000)

### Prerequisiti agli esercizi

* Creazione di Account su github.com

![image](https://user-images.githubusercontent.com/94290557/201487323-88a14ef8-b3a7-4359-9bfd-88ba77004ba7.png)

* [Creazione Nuovo Progetto (Guida Video)](https://youtu.be/47bZxjEwE_c)

### Esercizio 1: aggiungi file manualmente
step 1: crea nuovo file "newFile.txt" e inserisci il testo in linea 1, inserisci testo in linea 2, commit il nuovo file

step 2: crea nuovo file "MATERIALI/README.md e inserisci il testo in linea 1"# Elenco Materiale", inserisci testo in linea 2 "Presentazione GITHUB Per la Didattica", commit il nuovo file

### Esercizio 2: storicità dei file
step 1: modifica il file "newFile.txt" inserendo del testo in una nuova linea tra linea 1 e linea 2 precedentemente inserite e esegui il commit

step 2: verifica la storicità del file che è stato modificato

#### [Guida Video allgli esercizi 1 & 2: modifica progetto e visiona la storicità](https://youtu.be/jAusId8fp1g)

### Effettuare modifiche ad un progetto condiviso e collaborativo

Introduciamo un ***metodo*** che facilita la gestione di un progetto che deve essere aggiornato:
* L'aggiornamento non è banale e richiede tempo e molte modifiche
* L'aggiornamento viene proposto da un collaboratore

#### Introduzione al Branching e Pull Request  [PRESENTAZIONE](https://docs.google.com/presentation/d/e/2PACX-1vTEUX6JVUF_dxrxPhtN7qX8dJbUL4IT554ypH1pxKBkXhY0DLDiGZ5wNLOYLiRfvL-DZc2uwoi6vZID/pub?start=false&loop=false&delayms=3000) | [VIDEO](https://youtu.be/tWNMzqhSmy4)

### Esercizio 3: Branching e Pull Request

step 1: crea nuovo Branch chiamato "Esercizio3"

step 2: Modifica "newFile.txt" inserendo una ulteriore linea di testo e quindi commit le modifiche

step 3: verifica che il file "newFile.txt" nel Branch "main" non sia stato modificato

step 4: esegui una "Pull Request" per aggiornare il Branch "main" con le modifiche apportate nel Branch "Esercizio3"

step 5: chiedi ad un compagno di visionare Esercizio 3 e di inserire un commento nella conversazione della tua Pull Request

step 6: Esegui il Merge del codice

step 7: Verifica che la modifica sia stata inserita nel Branch "main"

step 8: Verifica il grafico che visualizza il Branch e il Merge

#### [Guida Video all'esercizio 3](https://youtu.be/GYF2R_0r21w)

### Esercizio 4: Domande e Risposte sugli argomenti trattati

E' venuta l'ora di confrontarsi e aiutarci l'uno con l'altra, per fare ciò il Prof. ha creato una Pull Request. Visiona la Pull Request riguardo al Branch "Domande-e-Risposte" di questo Repo e intervieni nella conversazione.

## Fork <img src="https://user-images.githubusercontent.com/94290557/201693532-480ac324-2a5a-4a08-873f-33fe83584751.png" width="50" height="50" />

Una volta che abbiamo capito il **BRANCH**, capire il **FORK** è uno scherzo:

Il Fork non è altro che la copia di un REPO che non mi appartiene, sotto il mio ACCOUNT.

Infatti il **FORK** può essere pensato ad una copia di un progetto altrui (evidentemente Open Source), da cui partire e modificare a mio piacimento.

Il Fork verrà registrato, e ne verrà tenuta traccia. In questo modo, sarà possibile fare delle modifiche personali ed eventualmente proporle al progetto di origine mediante una Pull Request... proprio come se fossi un collaboratore, anche se in realtà non faccio parte del team... 

Quindi si comporta esattamente come un BRANCH, ma a differenza del BRANCH la copia viene trasferita nel mio ACCOUNT, così che, anche se non ho il permesso di modificare il progetto di origine, adesso che lo possiedo, posso fare tutte le modifiche che ritengo opportune... 

Ho quindi la possibilità di derivarne un progetto MIO, oppure, fare delle modifiche ed eventualmente proporle al Team di appartenenza del progetto originale.

### Esercizio 5: Fork

step 1: naviga al Repo del Porf., selezional il progetto [LabSist2c-2022](https://github.com/Prof-Palitto/LabSist2C-2022) e prova ad editare uno dei files...

step 2: genera un Fork del Repo del Prof. e prova a cambiare il file che prima non ti lasciava cambiare

step 3: Esegui esercizio 3 ma chiamando il branch "Esercizio5" e senza eseguire il Merge finale (fino a step 5 incluso)

step 4: Invia un commeneto alla Pull Request "[Esercizio 5](https://github.com/Prof-Palitto/impariamoGH/pull/2)" nel Repo del Prof.per segnalare la consegna (il completamento dell'ES 5)

step 5: monitorizza l'avvenuta correzzione da parte del Prof.

### Esercizio 6: Il Prof. ha bisogno del tuo aiuto

Saluti a tutti, vorrei modificare il Progetto inserendo una sezione nel README file in cui inserire dei suggerimenti di come utilizzare GitHub nella didattica... mi interesserebbe inziare una conversazione in cui ognuno possa condividere delle idee... una specie di "Brain Storming"...

Inserisci dei commenti nella Pull Request per entrare a far parte della discussione di classe su questa modifica (esercizio 4)

Per divertirci un pò, a seconda degli interventi verranno attribuiti dei punteggi in questo modo:
Interventi:

0 - non significativi

1 - significativi

2 - Molto Sgnificativi

Risposte: 0 - non significative/errate, 2 - significative/corrette, 4 - Molto significative/ben esposte e dettagliate

Per la consegna assicurati di inserire il commento: @Prof-Palitto CONSEGNA + link del tuo Branch "Esercizio 4" entro la data di consegna GG/MM/YY
## Lezione 2 Command Line GIT
Nella scorsa lezione abbiamo usato GITHUB per gestire un progetto mediante l'interfaccia WEB, normalmente GITHUB si usa come "magazzino remoto"(Remote Repository) e lo sviluppo del codice avviene sul proprio Personal Computer.

In effetti, per lo sviluppo del codice abbiamo bisogno di strumenti non disponibili su GitHUb come un editore più evoluto, un compilatore... quindi abbiamo bisogno che il prgetto risieda sul computer in cui sviluppiamo, e usiamo GitHub per mantenerne una copia sulla nuvola con tutti i vantaggi offerti e discussi la lezione scorsa.

La copia locale (sul nostro PC) verrà gestita da un GIT Client che si sincronizza con la copia remota su GitHub.
```
GIT Client <--> GitHub (Remote Repository)
```
### Git Client
#### Installazione
Ci sono molte versioni disponibili per qualsiasi piattaforma del GIT Client, le seguenti sono le mie raccomandazioni:
* Windows: [Git for Windows](https://gitforwindows.org/) che offre un Client sia a "linea di comando" che GUI
* Linux(Ubuntu): `apt install git` che offre un Client a "linea di comando" 

#### Configurazione
Per creare un progetto **myProject** basta creare una cartella 'myProject' in cui risiederanno tutti i files (organizzati nelle eventuali sottocartelle).

Per indicare che intendiamo gestire il progetto con GIT, una volta entrati nella cartella del progetto, invochiamo il comando `git init`
```
mkdir myProject
cd myProject
git init
```
Questo crea una sotto-cartella "nascosta" **.git** contenente tutte le informazioni necessarie per il suo corretto funzionamento.

Dobbiamo quindi dire a GIT chi siamo
```
  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"
```
Nel caso volessimo avere una identità differente per ogni progetto, possiamo 

Siamo pronti a iniziare il nostro progetto e cioè ad aggiungere dei files all'interno della cartella.

#### Staging e Commit
Normalmente un progetto è composto da un insieme di files e l'avanzamento dello sviluppo comporta la modifica di un gruppo di files.

Questo significa che alcuni files sono ancora in uno stato di "working in progresss", cioè ci stiamo ancora lavorando e non siamo pronti per renderli pubblici agli altri membri del gruppo di sviluppo, mentre ci sono dei files che sono stati modificati e che ci riteniamo soddisfatti e siamo quindi pronti alla loro pubblicazione al resto del gruppo di lavoro...

Per indicare quali files possono essere "pubblicati"(committed), usiamo `git add filename`, per controllare la lista dei files che abbiamo inserito
possiamo usare il comando `git status`

```
git add index.html
```

```
git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached ..." to unstage)
    new file: index.html
```
Per effettuare la "pubblicazione" vera e propria, si usa il comando `git commit`

```
git commit -m "messaggio per spiegare le modifiche fatte"
```

#### Remote Repository (GitHub)
Per poter usare GitHub come Server dobbiamo creare un associazione

**git remote add origin URL** dove **origin** indica che da adesso in poi il luogo ufficiale di residenza del progetto è identificato dal **URL** specificato.

Nel nostro caso sarà l'URL del nostro account di GitHub che nel mio caso corrisponde a **https://github.com/Prof-Palitto/nuovo-progetto.git**

Per motivi di sicurezza GitHub ci chiede di generare un **token** da utilizzare per le operazioni dal client:

**GitHub.com --> my profile (icona in alto a destra)  --> Settings --> Developer settings --> Personal access token -->  Tokens (classic) --> Generate New Token**

compila: 
* Note (what is this token for?)
* Expiration (seleziona: No Expiration)
* Select Scope (flag Repo)

Premi **generate token** 

copia il token e inseriscilo nel comando seguente:

`git remote add origin https://`**yourToken**@`github.com/Prof-Palitto/nuovo-progetto.git` nel caso non lo avessi già fatto

oppure 

`git remote set-url origin https://`**yourToken**@`github.com/Prof-Palitto/nuovo-progetto.git` nel caso fosse già configurato e volessi sostituirlo

`git push --set-upstream origin master` per fare modo che il Branch 'master' venga sincronizzato con il **remote** branch 'master' from 'origin'(GitHub).

## Lezione 3
