# Guida all'installazione e ai comandi di base di Git

## Installazione di Git

Per utilizzare Git sul tuo computer, devi prima scaricarlo e installarlo. Ecco come farlo:

### Windows

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


