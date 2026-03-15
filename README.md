# ProgettoGEP

# Cognome e nome
Roncelli Leonardo

# Titolo
DriveGallery

# Descrizione
Applicazione che offre un catalogo fotografico di automobili. Ogni immagine viene accompagnata da schede dettagliate con informazioni tecniche e storiche del veicolo raffigurato: marca, modello, anno di produzione e altro ancora. L'app consente anche la stampa delle foto in diversi formati e supporti: poster, quadri, cornici… per arredare spazi.

# Problema
Risoluzione del problema di mancanza di idee che alcune persone potrebbero avere riguardo a come arredare uno spazio in modo originale.

# Target
Appassionati di auto che vogliono arredare uno spazio in modo originale.

# Competitors
Photobox, Cheerz, Displate.

# Tagline
Ogni auto ha una storia. Noi la incorniciamo.

# Tecnologie
Frontend & Mobile (Esperienza Utente)
React Native / Flutter: Per avere un'unica base codice che funzioni perfettamente sia su iOS che su Android (riducendo i costi di sviluppo).
Next.js: Per il sito web/e-commerce, garantendo velocità estrema e un ottimo posizionamento su Google (SEO).

Backend & Database (Il Cuore Tecnico)
Node.js / Python: Per gestire l'archiviazione e il recupero delle schede tecniche delle auto in tempo reale.
PostgreSQL / MongoDB: Database robusti per gestire migliaia di modelli di auto, anni di produzione e specifiche tecniche.
Cloud Hosting (AWS o Google Cloud): Per garantire che l'app non vada mai offline, anche con migliaia di utenti simultanei.

Integrazioni & Servizi (Automazione)
Stripe / PayPal: Per la gestione sicura dei pagamenti globali e delle transazioni ricorrenti.
Print-on-Demand API: Integrazione diretta con i laboratori di stampa (es. Prodigi o Gelato). Quando un cliente ordina, il file viene inviato automaticamente alla stampa senza intervento manuale.
Algolia: Un motore di ricerca avanzato interno all'app per permettere agli utenti di trovare la loro auto in millisecondi tra migliaia di versioni.

Intelligenza Artificiale & Immagini
Upscaling AI: Utilizzo di algoritmi per migliorare la risoluzione delle foto storiche, garantendo stampe nitide anche in grandi formati.
CDN (Content Delivery Network): Per caricare le anteprime delle immagini istantaneamente in tutto il mondo.

# Timestamp JWT
1758868211

# Requisiti
Requisiti funzionali (funzionalità che il sistema deve avere, servizi che dovrà offrire agli utenti): il sistema dovrà permettere all’utente di navigare o cercare foto di auto attraverso l’inserimento di marca, modello, anno o categoria. L’app mostra per ogni foto i dettagli tecnici del veicolo raffigurato, l’utente può ingrandire le immagini e visualizzarle in galleria, salvarle o condividerle e sarà possibile filtrare le auto presenti nel catalogo. L’utente può selezionare un’immagine e scegliere il formato e il tipo di stampa, l’app calcola automaticamente il prezzo finale in base alle opzioni scelte, l’utente può aggiungere al carrello il prodotto e procedere all’ordine. L’ordine viene finalizzato con una gestione del pagamento sicuro, l’utente riceverà la conferma d’ordine e il tracciamento di spedizione. É possibile visualizzare la sezione profilo personale attraverso la fase di registrazione e login.
Requisiti non funzionali (vincoli imposti dall’organizzazione e dall’esterno che vanno rispettati): l’interfaccia deve essere intuitiva e responsive, adatta a dispositivi mobili e desktop. I dati utente e i pagamenti dovranno essere crittografati e dovranno essere rispettate le norme GDPR su privacy e gestione dati. L’app deve poter gestire grandi quantità di immagini che dovranno avere un’elevata qualità visiva per garantire stampe nitide.
Requisiti di dominio (dipendenti dal dominio in cui il sistema deve operare): l’app conterrà informazioni relative al dominio automobilistico, fotografia digitale e stampa e-commerce. Ogni foto avrà la relativa descrizione tecnica dell’automobile raffigurata verificata da fonti ufficiali, devono essere supportati vari formati di stampa, i prezzi variano in base a formato, materiale e risoluzione.

# Sito
https://auto-gallery-prints.lovable.app

# Tabella benchmarking
https://docs.google.com/presentation/d/1uxwZdI-Fqq4vuBc3JNru9baPWh5Jcv4iOxynh13BZPE/edit?slide=id.g3d029d9b368_0_0#slide=id.g3d029d9b368_0_0

# UML
<img width="810" height="1273" alt="image" src="https://github.com/user-attachments/assets/c7c73659-adaf-4872-8e8e-16ebea9002d2" />


# Gantt
<img width="536" height="398" alt="image" src="https://github.com/user-attachments/assets/32c4fb53-d918-4a66-a98f-1625a9db1e2f" />
