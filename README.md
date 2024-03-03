# Guida all'installazione e ai comandi di base di Git

## Installazione di Git

Per utilizzare Git sul tuo computer, devi prima scaricarlo e installarlo. Ecco come farlo:

1. Sito di Git per Windows: [https://git-scm.com/](https://git-scm.com/download/win)
2. Nell installazione l'unica cosa essenziale da selezionare oltre alle cose raccomandate e' quella di impostare VSC come editor di testo di git quando ce lo chiede all'inizio, il resto e' facoltativo. (Io ho utilizzato tutto quello raccomandato e nient'altro).

Per far funzionare git dobbiamo impostare un username ed un email tramite bash o powershell. Apro git bash e per vedere se e' installato correttamente faccio:
```
git --version
```
Se mi mostra una linea di codice con una versione significa che e' installato correttamente e posso procedere con i due comandi seguenti:
```
git config --global user.name "Il Tuo Nome"
git config --global user.email "tua_email@example.com"
```
Dove "Il Tuo Nome" e' il tuo nome attuale o pseudonimo e come "tua_email@example.com" la tua mail attuale.

## Segnalazione errori

Per qualsiasi errore riscontrato nella guida riportero' gli errori qui e come risolverli. Per segnalarne qualcuno puoi utilizzare questo server di discord per segnalare l'errore e risolverlo con me. [Clicca qui per entrare nel server.](https://discord.gg/f7nHr2bwag)

## Sincronizzazione Git/Github/VSC

Una volta aperto VSC dobbiamo essere loggati con github (In basso a sinistra) ed in caso non fossimo loggati facciamo il login.

Proseguo con il clonare una repository cosi' facendo sincronizzo github e vsc con le repo e rifaccio il login dal sito.

Se dovesse aprire una scheda bianca ed un caricamento su vsc molto lungo del tipo (autenticazione github) puoi fare annulla e ti fara' aprire un link da locale che risolvera' il problema.

Poi una volta aggiornato il file o la repo da aggiornare faccio un push (in alto a sinistra al lato di "controllo del codice sorgente" ci sono dei tre puntini alla fine "..." e faccio esegui push. 

Faccio l'accesso con Github un ultima volta e sotto nei commit dovrei vedere che il commit e' stato pushato ad origin.

