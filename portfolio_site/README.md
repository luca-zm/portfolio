# Portfolio di Luca – Istruzioni per l'hosting gratuito

Questa cartella contiene il codice sorgente di un sito web statico realizzato per
il portfolio professionale di **Luca**, ingegnere informatico e application architect.

Il sito include una pagina principale (`index.html`), risorse grafiche e uno
stile personalizzato per presentare i progetti *Medicamee* e *Gestionale
aziendale*. Le immagini presenti nella cartella `images` sono state generate
artificialmente a scopo decorativo.

## Come visualizzare il sito in locale

Per aprire il portfolio in locale:

```bash
# dalla radice del progetto
open index.html
```

In alternativa, puoi trascinare il file `index.html` nel browser.

## Pubblicazione su GitHub Pages (gratuita)

Per rendere disponibile il portfolio online senza alcun costo di hosting,
puoi utilizzare **GitHub Pages**. GitHub Pages è un servizio di GitHub che
permette di pubblicare siti statici direttamente da un repository. Come
evidenziato da GeeksforGeeks, GitHub Pages "offre una soluzione **semplice e
gratuita** per l'hosting di siti statici direttamente dai tuoi repository"
【407590446711357†L102-L106】. Inoltre, una guida di Kinsta sottolinea che GitHub
Pages è un modo pratico e potente per ospitare gratuitamente il tuo sito
statico【771979923456918†L658-L662】.

Per procedere alla pubblicazione:

1. **Crea un nuovo repository pubblico su GitHub.** Se non hai un account
   GitHub, registrati gratuitamente.
2. **Carica tutti i file di questa cartella** (inclusa la cartella `images` e
   `style.css`) nel repository. Puoi farlo tramite interfaccia web o usando
   Git:

   ```bash
   git init
   git add .
   git commit -m "Pubblica portfolio"
   git branch -M main
   git remote add origin https://github.com/tuo-utente/tuo-repo.git
   git push -u origin main
   ```

3. **Abilita GitHub Pages.** Vai nelle *Settings* del repository, trova la
   sezione **Pages**, seleziona il branch `main` e la cartella root (`/`) come
   sorgente e salva. GitHub genererà l'URL del tuo sito nel formato
   `https://tuo-utente.github.io/tuo-repo`【407590446711357†L186-L191】.
4. Dopo pochi minuti il tuo portfolio sarà accessibile tramite quell'URL.

### Utilizzare un dominio personalizzato

Con GitHub Pages è possibile associare un dominio personalizzato. Consulta le
guide ufficiali di GitHub per la configurazione di un record CNAME se desideri
un indirizzo più professionale.

## Prossimi passi

Questo sito è una versione statica di un portfolio. Per trasformarlo in una
pietra miliare di un **servizio multi‑utente** dove ogni iscritto può
personalizzare la propria vetrina e ottenere un link pubblico condivisibile,
potresti sfruttare strumenti come **Lovable**. Lovable permette di generare
applicazioni web complete da prompt testuali e offre funzionalità di back‑end
integrate, autenticazione e database come Supabase, oltre a un piano gratuito
con 5 crediti al giorno e pubblicazione con un click【763167817622846†L287-L307】【391347245723897†L97-L103】.
Nel file principale della conversazione sono presenti suggerimenti su come
strutturare un prompt efficace per Lovable.
