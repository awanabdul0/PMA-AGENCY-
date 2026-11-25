# Progetto realizzato da PMA-AGENCY

# Committente: Prof.ssa Villani Valentina e Anna de Vincentiis
Classe 5inc 
Settore 2: Brand di Abbigliamento Sostenibile / Streetwear Etico

# Sito abbigliamento
è un brand di **abbigliamento sostenibile e streetwear etico** nato per unire l'estetica urban contemporanea al rispetto per l'ambiente. Ogni capo è realizzato in cotone organico certificato, tessuti riciclati e tinture a basso impatto ambientale, con collezioni a tiratura limitata pensate per durare nel tempo.

Il sito offre un'esperienza d'acquisto rapida, intuitiva e mobile-first, valorizzando la trasparenza sui materiali e guidando l'utente nella scelta della taglia ideale.

##  Funzionalità Principali
- **Catalogo Dinamico:** Caricamento asincrono/dinamico di 8-12 prodotti tramite struttura dati JavaScript/JSON (senza elementi hardcoded in HTML).
- **Filtri e Ricerca Real-Time:** Filtraggio immediato per categoria (*T-Shirt, Felpe, Pantaloni, Accessori*), barra di ricerca per parola chiave e ordinamento per prezzo (crescente/decrescente).
- **Dettaglio Prodotto (Modale):** Scheda informativa interattiva con composizione tessile, guida alle taglie (`S`, `M`, `L`, `XL`) e aggiunta rapida al carrello.
- **Carrello Interattivo e Persistente:** Pannello laterale (*drawer*) con badge numerico in tempo reale, gestione quantità, calcolo automatico di subtotale, spedizione gratuita sopra i 50€ e salvataggio automatico tramite `localStorage`.
- **Simulazione di Checkout:** Modulo d'ordine con validazione lato cliente dei dati di spedizione/pagamento e schermata di conferma con svuotamento del carrello.
- **Design Responsive:** Layout adattivo realizzato con **CSS Grid** e **Flexbox** per smartphone, tablet e desktop.

##  Stack Tecnologico
HTML5: Struttura semantica e accessibile.
CSS Layout responsive (Grid & Flexbox), variabili CSS e animazioni fluide.
JavaScript  Manipolazione del DOM, gestione dello stato del carrello, filtri dinamici e `localStorage`.
Git & GitHub Controllo versione collaborativo, gestione Pull Request e documentazione.


##  Struttura del Repository
```text
├── html/
│   └── sito.html           # Pagina principale dell'e-commerce
├── css/
│   └── sito.css            # Foglio di stile (layout, componenti, responsive)
├── js/
│   └── sito.js             # Logica applicativa (catalogo, filtri, carrello, checkout)
├── docs/
│   └── verbali/            # Documentazione dei briefing del team (.md)
└── README.md               # Documentazione principale del progetto