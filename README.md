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

1. Una volta aperto VSC dobbiamo essere loggati con github (In basso a sinistra) ed in caso non fossimo loggati facciamo il login.
2. Proseguo con il clonare una repository cosi' facendo sincronizzo github e vsc con le repo e rifaccio il login dal sito.
3. Se dovesse aprire una scheda bianca ed un caricamento su vsc molto lungo del tipo (autenticazione github) puoi fare annulla e ti fara' aprire un link da locale che risolvera' il problema.
4. Poi una volta aggiornato il file o la repo da aggiornare faccio un push (in alto a sinistra al lato di "controllo del codice sorgente" ci sono dei tre puntini alla fine "..." e faccio esegui push. 
5. Faccio l'accesso con Github un ultima volta e sotto nei commit dovrei vedere che il commit e' stato pushato ad origin.

### Swappare account e ricollegarlo a VSC

Se dovessimo utilizzare un account diverso con Github e mi da un errore mentre pusho la repo devo seguire questi passaggi trovati su [questo thread](https://stackoverflow.com/questions/68080637/you-do-not-have-permission-to-push-to-on-github-would-you-like-to-create-a-fork).

Qui trovi la traduzione se il thread venisse cancellato:

1. In VScode uscire facendo clic sull'icona della persona a sinistra in basso sullo schermo e chiudere VScode.
2. Successivamente, accedere al "Pannello di controllo" in "Windows OS", cercare "Credential Manager" e scegliere "Credenziali di Windows".
3. Di seguito vedrete un elenco chiamato "Credenziali generiche", rimuovete tutto ciò che ha il nome "Git" e "Github" (questo rimuoverà i vostri accessi).
