GREGORIO PERRUCCI - IMPRESA EDILE
App preventivi edili (PWA)

CONTENUTO
- index.html: applicazione
- manifest.webmanifest: impostazioni installazione Android
- sw.js: cache offline
- icon.svg: logo/icona

FUNZIONI
- Dati cliente e indirizzo cantiere
- Righe di lavorazione con quantità, unità e prezzo unitario
- Calcolo subtotale, sconto, IVA e totale
- Salvataggio preventivi nell'archivio locale del dispositivo
- Stampa / Salva come PDF tramite la funzione di stampa del browser

INSTALLAZIONE SU ANDROID
Per installarla come app con icona e modalità a schermo intero, pubblica questa cartella su un hosting statico HTTPS (ad esempio GitHub Pages o Netlify).
Poi apri l'indirizzo HTTPS in Chrome su Android > menu ⋮ > Installa app (oppure Aggiungi a schermata Home).
Il service worker e l'installazione PWA richiedono HTTPS (o localhost).

USO LOCALE
Apri index.html in un browser per provare le funzioni. Per la piena installazione PWA serve un indirizzo HTTPS.

PRIVACY E DATI
I preventivi vengono salvati in localStorage del browser, sul dispositivo. Non vengono inviati a un server.
Non cancellare i dati del browser prima di aver esportato/stampato i preventivi importanti.

NOTA FISCALE
L'aliquota IVA va scelta in base al tipo di intervento, al cliente e alla normativa applicabile. Verificarla prima di emettere il documento. Il PDF generato è un preventivo commerciale, non una fattura elettronica.
