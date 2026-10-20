# Vita cristiana e ministero → WhatsApp

Prima versione prototipo, pensata per Samsung Android e Mac.

## Pubblicazione su GitHub Pages
1. Nel repository `vita-cristiana-whatsapp`, premi **Add file → Upload files**.
2. Carica `index.html` e `README.md` (oppure copia i file).
3. Premi **Commit changes**.
4. Vai in **Settings → Pages**.
5. In **Build and deployment**, scegli **Deploy from a branch**; branch `main`, folder `/(root)`, quindi **Save**.
6. Attendi la pubblicazione. L'indirizzo sarà simile a `https://NOME-UTENTE.github.io/vita-cristiana-whatsapp/`.

## Limiti della prima versione
- La pagina non ha ancora accesso diretto alla cartella privata di Google Drive.
- I nomi si inseriscono e verificano manualmente.
- La pagina non legge la rubrica Android né invia autonomamente messaggi WhatsApp.
- La condivisione di immagine dipende dal supporto del browser; se non disponibile, si apre WhatsApp con il testo e l'immagine va allegata manualmente.
- Non pubblicare immagini reali, numeri di telefono o altri dati personali nel repository pubblico.

Per collegare Drive servirà configurare Google OAuth/Drive API e autorizzazioni appropriate; non mettere segreti o token nel codice pubblico.
