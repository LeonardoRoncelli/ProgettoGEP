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

# Tabella di benchmarking
<img width="882" height="380" alt="image" src="https://github.com/user-attachments/assets/9cbcee3b-48ba-4b12-ae2f-da381845bfdb" />

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

# Elenco riassuntivo dei requisiti
REQUISITI FUNZIONALI
- Ricerca e navigazione foto auto per:
marca
modello
anno
categoria
- Visualizzazione dettagli tecnici del veicolo associato a ogni immagine
- Galleria immagini con:
zoom
visualizzazione a schermo intero
- Possibilità di:
salvare immagini
condividere immagini
- Filtri avanzati per il catalogo auto
- Selezione immagine per acquisto stampa
- Scelta opzioni di stampa:
formato
tipo/materiale
- Calcolo automatico del prezzo finale
- Aggiunta prodotti al carrello
- Gestione ordine e checkout
- Sistema di pagamento sicuro
- Invio conferma ordine
- Tracciamento spedizione
- Registrazione e login utente
- Accesso e gestione profilo personale

REQUISITI NON FUNZIONALI
- Interfaccia:
intuitiva
responsive (mobile e desktop)
- Sicurezza:
crittografia dati utente
crittografia pagamenti
- Conformità normativa:
rispetto GDPR (privacy e gestione dati)
- Prestazioni:
gestione grandi quantità di immagini
- Qualità:
immagini ad alta risoluzione per stampa

REQUISITI DI DOMINIO
- Ambiti coperti:
settore automobilistico
fotografia digitale
e-commerce di stampe
- Ogni immagine deve includere:
descrizione tecnica verificata da fonti ufficiali
- Supporto a diversi formati di stampa
- Prezzi variabili in base a:
formato
materiale
risoluzione

# User story
In questa sezione vengono dettagliate le necessità degli utenti attraverso il formato standard delle User Stories:

| Attore (Come...) | Requisito / Azione (Voglio...) | Beneficio (In modo da...) |
|------------------|--------------------------------|----------------------------|
| Utente | registrarmi alla piattaforma | creare un account e accedere ai servizi |
| Utente | effettuare il login | accedere al mio profilo e alle funzionalità riservate |
| Utente | recuperare la password | ripristinare l’accesso in caso di smarrimento |
| Utente | gestire il mio profilo | aggiornare i dati personali e le preferenze |
| Utente | cercare un’auto nel catalogo | trovare rapidamente immagini tramite filtri (marca, modello, anno, categoria) |
| Utente | visualizzare i dettagli di un’auto | conoscere specifiche tecniche e informazioni storiche |
| Utente | esplorare la galleria immagini | vedere le foto in alta qualità e a schermo intero |
| Utente | ingrandire un’immagine | osservare i dettagli dell’auto |
| Utente | salvare un’immagine | conservarla tra i preferiti |
| Utente | condividere un’immagine | mostrarla ad altri utenti o amici |
| Utente | filtrare le auto | restringere i risultati secondo preferenze specifiche |
| Utente | selezionare una foto | prepararla per la stampa |
| Utente | scegliere formato e materiale di stampa | personalizzare il prodotto (poster, quadro, cornice, ecc.) |
| Utente | visualizzare il prezzo finale | conoscere il costo in base alle opzioni scelte |
| Utente | aggiungere un prodotto al carrello | preparare l’acquisto |
| Utente | gestire il carrello | modificare o rimuovere prodotti prima dell’acquisto |
| Utente → Sistema di pagamento | effettuare il checkout | completare la transazione in modo sicuro |
| Utente | ricevere conferma ordine | avere una prova dell’acquisto effettuato |
| Utente | tracciare la spedizione | monitorare lo stato della consegna |
| Utente | visualizzare i miei ordini | controllare lo storico acquisti |
| Amministratore | effettuare il login con privilegi | accedere alle funzionalità amministrative |
| Amministratore | gestire il catalogo auto | aggiungere, modificare o rimuovere immagini e dati tecnici |
| Amministratore | verificare le informazioni tecniche | garantire l’accuratezza dei dati delle auto |
| Amministratore | gestire gli ordini | monitorare acquisti e spedizioni |
| Sistema → Servizio di stampa | inviare automaticamente i file | avviare la produzione senza intervento manuale |

# Elevator pitch e business model
Slide 1: Opening Slide

Nome Compagnia: DriveGallery
Progetto: Catalogo fotografico automobilistico & stampa personalizzata
Contatto: Leonardo Roncelli
Tagline: "Ogni auto è arte. Noi la stampiamo."

Slide 2: Il Problema

Molte persone vogliono arredare i propri spazi in modo originale, ma faticano a trovare decorazioni uniche e personalizzate
le stampe disponibili online sono spesso generiche e poco curate
manca un collegamento tra passione (auto) e arredamento.

Slide 3: La Soluzione

DriveGallery è una piattaforma che unisce:

passione per le automobili
fotografia di alta qualità
stampa personalizzata
Permette agli utenti di scegliere immagini di auto iconiche e trasformarle in elementi di design per i propri spazi.

Slide 4: Cosa Offriamo

Catalogo fotografico di auto (marca, modello, anno)
Schede tecniche dettagliate
Galleria immagini in alta qualità
Personalizzazione stampa:
formato
materiale
Sistema e-commerce completo
Spedizione e tracciamento ordine

Slide 5: Dimensione del Mercato

Mercato automotive globale: miliardi di appassionati
Mercato stampa decorativa in crescita
E-commerce in continua espansione

DriveGallery si posiziona tra:

automotive passion
home decor
digital commerce

Slide 6: Competitors
Photobox
Cheerz
Displate

Questi offrono stampe, ma:
non sono focalizzati sulle auto
non offrono schede tecniche
non creano un’esperienza tematica

Slide 7: Tabella Benchmarking

Esposizione della tabella di benchmarking

Slide 9: Modello di Business

Marketplace e-commerce:
vendita stampe personalizzate
margine su ogni ordine

Possibili evoluzioni:
contenuti premium
collezioni esclusive

Slide 10: Fatturato

Fonti di ricavo:
vendita stampe

Obiettivo:
crescita progressiva con aumento utenti e ordini

Slide 11: Cosa Chiediamo

Cerchiamo:
investimento iniziale
supporto nello sviluppo
partnership strategiche

Slide 12: Percentuale della Società

Offriamo:
una percentuale della società
in cambio dell’investimento

Slide 13: Divisione dei Fondi

I fondi saranno utilizzati per:
sviluppo tecnologico (app e sito)
marketing e acquisizione utenti
integrazione servizi stampa
infrastruttura cloud

<img width="512" height="291" alt="image" src="https://github.com/user-attachments/assets/2f867121-bbd3-4b26-b731-1f29ced2be6a" />
<img width="512" height="287" alt="image" src="https://github.com/user-attachments/assets/4a750497-e46e-4c98-8484-7baf9e6f2cf1" />
<img width="513" height="287" alt="image" src="https://github.com/user-attachments/assets/9b5ac293-c5ca-40b3-aeb5-1d3d61e2a1d8" />
<img width="510" height="292" alt="image" src="https://github.com/user-attachments/assets/a7d28939-cc31-498e-aec7-e93e13873238" />
<img width="508" height="288" alt="image" src="https://github.com/user-attachments/assets/3896aa10-0e02-4032-a2be-207a244cf707" />
<img width="512" height="288" alt="image" src="https://github.com/user-attachments/assets/8aaa8ef3-4a39-4b31-af63-908ebb76e138" />
<img width="507" height="291" alt="image" src="https://github.com/user-attachments/assets/ca6dc6dd-4e7e-48d0-ad6f-52c0d6dc9c1d" />
<img width="507" height="288" alt="image" src="https://github.com/user-attachments/assets/3d8d5208-22f7-403e-b167-b7d6cb005500" />
<img width="508" height="287" alt="image" src="https://github.com/user-attachments/assets/e84ff482-0a3c-4ffb-822b-15befe8732fb" />
<img width="512" height="290" alt="image" src="https://github.com/user-attachments/assets/a4557c1b-669e-445b-bb15-6c79d8852232" />
<img width="507" height="287" alt="image" src="https://github.com/user-attachments/assets/0af2e70e-45cb-44e9-8013-a3ecd85a9842" />
<img width="507" height="287" alt="image" src="https://github.com/user-attachments/assets/b94588e5-e5ed-4be4-9959-279adb7899d8" />
<img width="510" height="286" alt="image" src="https://github.com/user-attachments/assets/97fda8ff-7bf9-4eb8-99e1-08ec3cd07de9" />


# Sito
https://auto-gallery-prints.lovable.app

# UML
<img width="810" height="1273" alt="image" src="https://github.com/user-attachments/assets/c7c73659-adaf-4872-8e8e-16ebea9002d2" />


# Gantt
<img width="536" height="398" alt="image" src="https://github.com/user-attachments/assets/32c4fb53-d918-4a66-a98f-1625a9db1e2f" />
