BULK DIARIO 3.0 — PACCHETTO FIREFOX / PWA

COSA CONTIENE
- index.html: Bulk Diario 3.0 ottimizzato per schermi mobili.
- manifest.webmanifest: nome, icona e modalità app.
- sw.js: cache offline dei file dell'app.
- icons/: icone 192 e 512 px.

IMPORTANTE: Firefox Android può aggiungere alla Home anche alcuni siti web, ma per una PWA installabile e affidabile l'app va servita tramite HTTPS. Aprire index.html direttamente da Download/file:// non basta per attivare il service worker e può non mostrare l'opzione di aggiunta alla Home.

PUBBLICAZIONE SEMPLICE CON GITHUB PAGES (gratuito, richiede account GitHub)
1. Crea un repository GitHub nuovo.
2. Carica TUTTI i file e le cartelle di questo pacchetto nella radice del repository (non solo lo ZIP).
3. Nelle impostazioni del repository, vai a Pages.
4. Seleziona Deploy from a branch, scegli main e /(root), quindi salva.
5. Attendi la pubblicazione e apri l'indirizzo HTTPS fornito da GitHub Pages in Firefox sul telefono.
6. In Firefox Android, apri menu ⋮ e seleziona “Aggiungi alla schermata Home” o “Installa” se disponibile, quindi conferma. Le voci variano in base alla versione di Firefox/Android.

PRIVACY E DATI
- I dati sono salvati nel localStorage del browser e restano sul dispositivo/origine web.
- Passare dal file locale a un sito HTTPS crea un archivio locale separato: i dati precedenti non vengono trasferiti automaticamente. Prima del passaggio, esporta un backup JSON da Bulk Diario e, una volta aperta la nuova versione, usa la funzione di importazione per ripristinarlo.
- Conserva una copia di backup. La cancellazione dei dati del sito/browser può eliminare il diario.
- Questa versione è il Bulk Diario 3.0 con stima guidata dalla foto; non include riconoscimento AI automatico.

USO SOLO LOCALE
Il file bulk_diario_firefox.html incluso separatamente può essere aperto nel browser per l'uso normale, ma non può offrire l'installazione PWA completa via file://.
