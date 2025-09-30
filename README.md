# Appunti di Algoritmi e Strutture Dati 📘

Questo repository raccoglie gli **appunti del corso di Algoritmi e Strutture Dati** tenuto dal professor Benerecetti per il Corso di Laurea in Informatica presso l’Università degli Studi di Napoli *Federico II*.

## 🚀 Come iniziare

### Requisiti
- [LaTeX (TeX Live / MikTeX)](https://www.latex-project.org/get/)
- `make`

### Compilazione
Per generare il PDF degli appunti:
```bash
# Senza utilizzare il makefile messo a disposizione
lualatex -shell-escape --interaction=nonstopmode --halt-on-error --file-line-error

# Utilizzando il makefile
make build
```
### 📂 Struttura
La repo è organizzata così:
```bash
├── chapters/     # Capitoli suddivisi
├── fonts/        # Font richiesti (link simbolico)
├── pdf/          # Risorse PDF
├── res/          # Risorse aggiuntive
├── sources/      # Risorse comuni (logo, ecc.)
├── index.ist     # Stile indice
├── main.tex      # Documento principale
├── Makefile      # Compilazione automatica
└── unina_doc_class.cls
```
### 🤝 Contribuire
Le regole di contribuzione sono spiegate [qui](./CONTRIBUTING.md)

### 🛠 Supporto

Se riscontri problemi:
* Apri una Issue su GitHub
* Oppure proponi una Pull Request con la correzione

### Credits
Questo progetto usa il [template](./unina_doc_class.cls) sviluppato da [@luftmensch-luftmensch](https://github.com/luftmensch-luftmensch).

### 📄 Licenza
Questo lavoro è distribuito con licenza Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International ([CC BY-NC-SA 4.0](./LICENSE)).
Puoi usarlo e modificarlo liberamente solo per scopi non commerciali, citando questa repository come fonte e mantenendo la stessa licenza.
