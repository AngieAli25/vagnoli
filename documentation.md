# LANDING PAGE COPY - VAGNOLI SRL
## Strutture Metalliche su Misura per il Settore Industriale

**Stack Tecnologico:**
- Framer Motion 12 (animazioni)
- Heroicons (icone)
- Tailwind CSS 4.1+ (styling)

**Palette Colori:**
- Primary: #b56749
- Secondary: #8a360f
- Font: Montserrat

---

## SEZIONE 1: NAVIGATION BAR

### Logo
**VAGNOLI**

### Menu Items
- Chi Siamo
- Servizi
- Aree Servite
- Contatti

### CTA Button (desktop)
**Richiedi Sopralluogo**

**Note tecniche:**
- Navbar sticky con backdrop blur (Tailwind: `sticky top-0 backdrop-blur-md bg-white/90`)
- Animazione fade-in al caricamento (Framer Motion: `initial={{ opacity: 0, y: -20 }} animate={{ opacity: 1, y: 0 }}`)
- Hamburger menu su mobile con slide-in animation

---

## SEZIONE 2: HERO SECTION

### Badge Sopra il Titolo
🎯 **Sopralluogo e Preventivo 100% Gratuiti**

### Headline Principale
# Strutture Metalliche su Misura per il Tuo Capannone Industriale

### Sottotitolo
Ristrutturazione e realizzazione di opere metalliche progettate per durare. Esperienza consolidata, soluzioni personalizzate, zero imprevisti.

### CTA Primaria
**→ Richiedi un Sopralluogo Gratuito**

### CTA Secondaria (link testuale)
Oppure richiedi un preventivo senza impegno

### Trust Elements (sotto le CTA)
✓ Oltre 30 anni di esperienza  
✓ Consulenza tecnica gratuita  
✓ Copertura: Lombardia, Veneto, Emilia-Romagna, Toscana

**Note tecniche:**
- Background: immagine hero capannone industriale con gradient overlay (Tailwind: `bg-gradient-to-r from-gray-900/80 to-gray-900/60`)
- Headline: animazione fade-in con delay (Framer Motion: `transition={{ delay: 0.2 }}`)
- CTA primaria: scale effect on hover + ripple animation
- Badge: pulse animation continua (Framer Motion: `animate={{ scale: [1, 1.05, 1] }} transition={{ repeat: Infinity, duration: 2 }}`)
- Icone Heroicons: `CheckCircleIcon` per i trust elements
- Hero image: parallax scroll effect (Framer Motion: `useScroll` hook)

---

## SEZIONE 3: TRUST BAR

### Copy
**Oltre 30 anni di esperienza** • **Progettazione su misura** • **Copertura: Lombardia, Veneto, Emilia-Romagna, Toscana** • **Consulenza tecnica gratuita**

**Note tecniche:**
- Background: `bg-[#8a360f]` con testo bianco
- Animazione marquee infinita per mobile (Framer Motion: `animate={{ x: [0, -1000] }} transition={{ repeat: Infinity, duration: 20, ease: "linear" }}`)
- Desktop: animazione fade-in da sinistra con stagger effect per ogni elemento
- Separatore bullets: Heroicons `ChevronRightIcon` (micro, inline)

---

## SEZIONE 4: PROBLEMA (Empatia)

### Headline
## Gestisci un Capannone Industriale? Conosci Questi Problemi:

### Colonna 1
**Icona:** Heroicons `ExclamationTriangleIcon`

#### Titolo
**Strutture Obsolete o Danneggiate**

#### Descrizione
Coperture che perdono, pilastri corrosi, strutture non a norma che mettono a rischio produzione e sicurezza.

### Colonna 2
**Icona:** Heroicons `ClockIcon`

#### Titolo
**Tempi di Fermo Impianto**

#### Descrizione
Ogni giorno di stop produttivo costa migliaia di euro. Serve un partner affidabile che lavori velocemente e senza intoppi.

### Colonna 3
**Icona:** Heroicons `DocumentTextIcon`

#### Titolo
**Complessità Tecnica e Normativa**

#### Descrizione
Serve un interlocutore unico che gestisca progettazione, autorizzazioni e realizzazione senza scaricare responsabilità.

**Note tecniche:**
- Layout: grid 3 colonne (Tailwind: `grid grid-cols-1 md:grid-cols-3 gap-8`)
- Background: `bg-gray-50`
- Card: hover effect con lift (Framer Motion: `whileHover={{ y: -8, transition: { duration: 0.3 } }}`)
- Icone: dimensione 48px, colore `text-[#b56749]`, animazione bounce on scroll into view
- Animazione entrata: fade-in dal basso con stagger per ogni colonna (Framer Motion: `variants` con `staggerChildren`)
- Cards: `bg-white shadow-md rounded-xl p-8`

---

## SEZIONE 5: SOLUZIONE (Proposta di Valore)

### Headline
## Strutture Metalliche Progettate, Realizzate e Collaudate Senza Pensieri

### Copy Principale
Vagnoli Srl è il partner specializzato per aziende che cercano **soluzioni su misura** per i loro capannoni industriali. Non lavoriamo con progetti standard: ogni intervento è **progettato specificamente** per le tue esigenze strutturali, operative e di budget.

**Dal sopralluogo al collaudo finale, ci occupiamo di tutto noi.**

### Beneficio 1
**Icona:** Heroicons `ShieldCheckIcon`

#### Titolo
**Esperienza Consolidata nel Settore Industriale**

#### Descrizione
Oltre 30 anni di progetti realizzati per aziende di logistica, produzione e magazzinaggio. Conosciamo le sfide del tuo settore.

### Beneficio 2
**Icona:** Heroicons `PencilSquareIcon`

#### Titolo
**Progettazione Su Misura, Zero Improvvisazione**

#### Descrizione
Ogni struttura è calcolata, dimensionata e realizzata secondo le normative vigenti e le tue specifiche esigenze operative.

### Beneficio 3
**Icona:** Heroicons `HandThumbUpIcon`

#### Titolo
**Unico Interlocutore, Massima Affidabilità**

#### Descrizione
Gestiamo internamente progettazione, produzione e posa in opera. Nessun subappalto, nessuna confusione, massima responsabilità.

### Elemento Video/Visual
**Placeholder per video time-lapse o slideshow progetti**
Didascalia: "Dai un'occhiata ad alcuni dei nostri progetti realizzati"

**Note tecniche:**
- Background: `bg-[#b56749]/10` (tinta leggera del primary color)
- Layout: testo centrale + grid 3 colonne sotto per i benefici
- Copy principale: max-w-3xl centrato, animazione fade-in
- Benefici cards: `bg-white rounded-xl shadow-lg p-6`
- Icone: dimensione 64px, colore `text-[#8a360f]`, animazione rotate on scroll into view
- Video/slideshow: lightbox modal con overlay scuro, play button animato (pulse effect)
- Animazione cards: parallax effect leggero su scroll
- Hover sulle cards: glow effect con `shadow-xl shadow-[#b56749]/20`

---

## SEZIONE 6: SERVIZI

### Headline
## Cosa Realizziamo per il Tuo Capannone

### Colonna Sinistra

✓ Ristrutturazione e rinforzo strutturale  
✓ Nuove coperture metalliche e lattonerie  
✓ Ampliamenti e sopraelevazioni  
✓ Carpenteria metallica pesante e leggera  

### Colonna Destra

✓ Scale, passerelle e soppalchi industriali  
✓ Pensiline e tettoie  
✓ Strutture portanti per impianti fotovoltaici  
✓ Manutenzione straordinaria e messa a norma  

### CTA
**→ Parliamo del Tuo Progetto**

**Note tecniche:**
- Background: `bg-white`
- Layout: 2 colonne (Tailwind: `grid grid-cols-1 md:grid-cols-2 gap-6`)
- Checkmark: Heroicons `CheckCircleIcon` colore `text-[#b56749]`
- Animazione lista: fade-in sequenziale con stagger (ogni item appare dopo 100ms)
- Items: hover effect con traslazione a destra (Framer Motion: `whileHover={{ x: 4 }}`)
- CTA: centrata, animazione pulse on hover, `bg-[#b56749] hover:bg-[#8a360f]`
- Ogni servizio: font Montserrat Regular 16px, spacing generoso

---

## SEZIONE 7: PROCESSO (Come Funziona)

### Headline
## Il Nostro Processo in 4 Passi
### Sottotitolo
*Tutto Gratuito Fino alla Firma*

### Step 1
**Numero:** 01

#### Titolo
**Sopralluogo Gratuito**

#### Descrizione
Veniamo in azienda, analizziamo la situazione e raccogliamo tutti i dati tecnici necessari. Zero costi, zero impegno.

### Step 2
**Numero:** 02

#### Titolo
**Progettazione e Preventivo**

#### Descrizione
Elaboriamo la soluzione tecnica su misura e ti presentiamo un preventivo dettagliato. Ancora nessun vincolo.

### Step 3
**Numero:** 03

#### Titolo
**Realizzazione Professionale**

#### Descrizione
Una volta approvato il progetto, gestiamo produzione e posa in opera con tempi certi e aggiornamenti costanti.

### Step 4
**Numero:** 04

#### Titolo
**Collaudo e Documentazione**

#### Descrizione
Consegniamo l'opera completata, collaudata e con tutta la documentazione tecnica e certificazioni necessarie.

### Trust Reinforcement
💬 *"Nessun anticipo richiesto fino all'approvazione del progetto finale"*

**Note tecniche:**
- Background: `bg-gray-100`
- Layout: timeline orizzontale con connettori (linea tratteggiata tra gli step)
- Numeri: cerchi grandi (80px) con `bg-[#b56749]` e testo bianco, font-bold
- Cards step: `bg-white rounded-2xl shadow-md p-8`
- Animazione timeline: linea che si disegna progressivamente on scroll (Framer Motion: `pathLength` animation)
- Steps: fade-in dal basso sequenziale con stagger di 200ms
- Icone connettore: Heroicons `ArrowRightIcon` tra gli step (mobile: `ArrowDownIcon`)
- Hover su card: lift effect + bordo colored (`border-l-4 border-[#b56749]`)
- Trust element: badge con icona Heroicons `ChatBubbleLeftRightIcon`, subtle pulse animation

---

## SEZIONE 8: CREDIBILITÀ

### Headline
## Perché le Aziende Scelgono Vagnoli

### Box 1
**Icona:** Heroicons `CalendarDaysIcon`

#### Numero/Stat
**30+**

#### Label
anni di esperienza nel settore delle strutture metalliche industriali

### Box 2
**Icona:** Heroicons `MapPinIcon`

#### Numero/Stat
**4**

#### Label
regioni servite: Lombardia, Veneto, Emilia-Romagna, Toscana

### Box 3
**Icona:** Heroicons `ShieldCheckIcon`

#### Numero/Stat
**100%**

#### Label
Trasparenza: sopralluogo, consulenza e preventivo completamente gratuiti

**Note tecniche:**
- Background: `bg-white`
- Layout: 3 colonne, cards con bordo superiore colorato
- Cards: `border-t-4 border-[#b56749]`, hover scale effect
- Icone: 56px, colore `text-[#8a360f]`, animazione rotate-in on scroll
- Numeri: font-size 48px, font-bold, colore `text-[#b56749]`, counter animation (da 0 al numero finale)
- Label: font-size 16px, colore `text-gray-600`
- Animazione entrata: fade + scale con stagger per ogni box
- Shadow: `shadow-lg hover:shadow-2xl` con transizione smooth

---

## SEZIONE 9: AREE GEOGRAFICHE

### Headline
## Operiamo in Tutta l'Italia Settentrionale e Centrale

### Copy
Siamo specializzati nell'assistenza alle aziende con sede in:

**Lombardia** • **Veneto** • **Emilia-Romagna** • **Toscana**

Hai un progetto in una di queste regioni? Possiamo essere operativi in tempi rapidi.

**Note tecniche:**
- Background: `bg-gradient-to-br from-[#b56749]/15 to-[#8a360f]/15`
- Layout: centrato con mappa stilizzata dell'Italia
- Mappa: SVG custom con le 4 regioni evidenziate in `fill-[#b56749]`
- Animazione mappa: fade-in delle regioni una alla volta con pulse effect
- Regioni nomi: font-bold, hover effect che fa highlight sulla mappa (Framer Motion: `whileHover` sincronizzato)
- Icona: Heroicons `MapIcon` decorativa
- Copy: max-w-2xl centrato, spacing generoso

---

## SEZIONE 10: FAQ

### Headline
## Domande Frequenti

### FAQ 1
**Icona apertura/chiusura:** Heroicons `ChevronDownIcon` / `ChevronUpIcon`

#### Domanda
**Il sopralluogo è davvero gratuito?**

#### Risposta
Sì, il sopralluogo e la consulenza tecnica iniziale sono sempre gratuiti e senza impegno. Valutiamo insieme la fattibilità del progetto prima di qualsiasi investimento da parte tua.

### FAQ 2
**Icona apertura/chiusura:** Heroicons `ChevronDownIcon` / `ChevronUpIcon`

#### Domanda
**Quanto tempo richiede un progetto di ristrutturazione?**

#### Risposta
Dipende dalla complessità dell'intervento. Durante il sopralluogo ti forniremo una stima precisa dei tempi, dalla progettazione al collaudo finale.

### FAQ 3
**Icona apertura/chiusura:** Heroicons `ChevronDownIcon` / `ChevronUpIcon`

#### Domanda
**Dovete fermare la produzione per lavorare?**

#### Risposta
Organizziamo i cantieri per minimizzare i disagi operativi. Lavoriamo spesso in orari concordati (weekend, turni notturni) o per fasi, permettendoti di continuare l'attività.

### FAQ 4
**Icona apertura/chiusura:** Heroicons `ChevronDownIcon` / `ChevronUpIcon`

#### Domanda
**Chi si occupa delle pratiche e delle autorizzazioni?**

#### Risposta
Noi. Gestiamo tutta la parte burocratica, dalle pratiche comunali alle certificazioni strutturali. Tu ricevi il progetto chiavi in mano.

### FAQ 5
**Icona apertura/chiusura:** Heroicons `ChevronDownIcon` / `ChevronUpIcon`

#### Domanda
**Lavorate solo su grandi progetti?**

#### Risposta
No, seguiamo sia interventi di manutenzione straordinaria che grandi ristrutturazioni. Ogni progetto è importante per noi.

### FAQ 6
**Icona apertura/chiusura:** Heroicons `ChevronDownIcon` / `ChevronUpIcon`

#### Domanda
**Rilasciate garanzie sui lavori?**

#### Risposta
Certamente. Ogni intervento è coperto da garanzia e viene consegnato con tutta la documentazione tecnica e i certificati di conformità.

**Note tecniche:**
- Background: `bg-white`
- Layout: accordion singola colonna, max-width 800px centrata
- Accordion items: `border-b border-gray-200`, ultimo senza bordo
- Domande: font Montserrat SemiBold 18px, colore `text-gray-900`
- Risposte: font Montserrat Regular 16px, colore `text-gray-600`, `pt-4 pb-6`
- Animazione apertura: Framer Motion `AnimatePresence` + `motion.div` con `initial={{ height: 0, opacity: 0 }} animate={{ height: "auto", opacity: 1 }} exit={{ height: 0, opacity: 0 }}`
- Icone: rotazione 180° quando aperto (Framer Motion: `animate={{ rotate: isOpen ? 180 : 0 }}`)
- Hover su domanda: cambio colore background (`hover:bg-gray-50`)
- Active state: bordo sinistro colorato (`border-l-4 border-[#b56749]`)

---

## SEZIONE 11: CTA FINALE + FORM

### Headline
## Hai un Progetto in Mente? Iniziamo da un Sopralluogo Gratuito

### Copy Persuasivo
Compila il form qui sotto e un nostro tecnico ti contatterà entro 24 ore per fissare un appuntamento senza impegno. Analizzeremo insieme la tua situazione e ti proporremo la soluzione più adatta.

### Trust Bullets
✓ **Sopralluogo gratuito**  
✓ **Preventivo senza impegno**  
✓ **Consulenza tecnica inclusa**

---

## FORM CONTATTO

### Campo 1 (Colonna Sinistra)
**Label:** Nome e Cognome *  
**Placeholder:** Mario Rossi  
**Type:** text  
**Required:** true

### Campo 2 (Colonna Sinistra)
**Label:** Azienda *  
**Placeholder:** Nome della tua azienda  
**Type:** text  
**Required:** true

### Campo 3 (Colonna Sinistra)
**Label:** Ruolo  
**Type:** select  
**Opzioni:**
- Titolare/Amministratore
- Responsabile Tecnico
- Geometra/Ingegnere
- Responsabile Manutenzione
- Altro

### Campo 4 (Colonna Destra)
**Label:** Email *  
**Placeholder:** mario.rossi@azienda.it  
**Type:** email  
**Required:** true

### Campo 5 (Colonna Destra)
**Label:** Telefono *  
**Placeholder:** +39 333 1234567  
**Type:** tel  
**Required:** true

### Campo 6 (Colonna Destra)
**Label:** Provincia intervento *  
**Type:** select  
**Opzioni (raggruppate per regione):**
- **Lombardia:** Milano, Bergamo, Brescia, Como, Cremona, Lecco, Lodi, Mantova, Monza e Brianza, Pavia, Sondrio, Varese
- **Veneto:** Venezia, Verona, Padova, Vicenza, Treviso, Rovigo, Belluno
- **Emilia-Romagna:** Bologna, Modena, Parma, Reggio Emilia, Ferrara, Ravenna, Forlì-Cesena, Rimini, Piacenza
- **Toscana:** Firenze, Pisa, Livorno, Arezzo, Siena, Lucca, Pistoia, Prato, Grosseto, Massa-Carrara

### Campo 7 (Full Width)
**Label:** Tipo di progetto  
**Type:** select  
**Opzioni:**
- Ristrutturazione
- Nuova realizzazione
- Ampliamento
- Manutenzione straordinaria
- Rinforzo strutturale
- Altro

### Campo 8 (Full Width)
**Label:** Descrivi brevemente il tuo progetto  
**Placeholder:** Esempio: Necessitiamo di ristrutturazione copertura capannone di 2000 mq con rifacimento lattonerie...  
**Type:** textarea  
**Rows:** 4  
**Maxlength:** 500

### Campo 9 (Checkbox Privacy)
**Label:** Ho letto e accetto l'[informativa privacy](#) *  
**Type:** checkbox  
**Required:** true

### Submit Button
**→ Richiedi Sopralluogo Gratuito**

### Trust Element sotto form
🔒 *I tuoi dati sono al sicuro. Non condividiamo informazioni con terzi.*

**Note tecniche:**
- Background sezione: `bg-gray-50`
- Form container: `bg-white shadow-2xl rounded-2xl p-8 md:p-12`, max-width 900px centrato
- Layout form: 2 colonne su desktop (Tailwind: `grid grid-cols-1 md:grid-cols-2 gap-6`)
- Labels: font Montserrat SemiBold 14px, colore `text-gray-700`, `mb-2`
- Input fields: `border border-gray-300 rounded-lg p-3 focus:ring-2 focus:ring-[#b56749] focus:border-transparent`
- Select: custom styled dropdown con Heroicons `ChevronDownIcon`
- Textarea: `resize-none`
- Validazione: messaggio errore sotto campo con Heroicons `ExclamationCircleIcon`, colore `text-red-600`
- Submit button: `bg-[#b56749] hover:bg-[#8a360f] text-white font-semibold py-4 px-8 rounded-lg w-full md:w-auto`, hover scale effect (1.02)
- Loading state button: spinner animation con "Invio in corso..."
- Success state: modal/toast con Heroicons `CheckCircleIcon` e messaggio di conferma
- Trust bullets: Heroicons `CheckIcon` in cerchi colorati `bg-[#b56749]/10 text-[#b56749]`
- Trust lock icon: Heroicons `LockClosedIcon`, colore `text-gray-500`
- Animazioni input: focus scale leggero, placeholder fade
- Form error shake animation (Framer Motion: `animate={{ x: [-10, 10, -10, 10, 0] }}`)

---

## SEZIONE 12: FOOTER

### Logo e Tagline
**VAGNOLI**  
Strutture Metalliche su Misura

### Contatti
**Icona:** Heroicons `MapPinIcon`  
📍 [Indirizzo completo - da recuperare dal sito]

**Icona:** Heroicons `PhoneIcon`  
📞 [Numero telefono - da recuperare dal sito]

**Icona:** Heroicons `EnvelopeIcon`  
✉️ [Email - da recuperare dal sito]

### Aree Servite
**Icona:** Heroicons `MapIcon`  
**Lombardia** • **Veneto** • **Emilia-Romagna** • **Toscana**

### Link Utili
- [Privacy Policy](#)
- [Cookie Policy](#)
- [Visita il sito completo →](https://www.vagnolisrl.com)

### Copyright
© 2025 Vagnoli Srl. Tutti i diritti riservati. | P.IVA [da recuperare dal sito]

**Note tecniche:**
- Background: `bg-gray-900`
- Testo: `text-gray-300`, link `text-gray-400 hover:text-white`
- Layout: 3-4 colonne su desktop, stack su mobile
- Logo: dimensione maggiore, colore `text-[#b56749]`
- Icone: Heroicons, dimensione 20px, colore `text-[#b56749]`
- Link: hover effect con underline animation (Framer Motion: `whileHover={{ x: 4 }}`)
- Social icons (se disponibili): hover scale + color change
- Separatore visuale sopra copyright: `border-t border-gray-800`
- Link "Visita sito completo": stile evidenziato con `text-[#b56749]` e arrow animation
- Animazione footer: fade-in dal basso quando entra nel viewport

---

## ELEMENTI GLOBALI E MICRO-INTERAZIONI

### Scroll to Top Button
**Icona:** Heroicons `ArrowUpIcon`  
**Posizione:** Fixed bottom-right  
**Comportamento:** Appare dopo 500px di scroll con fade-in  
**Animazione:** Pulse effect on hover, smooth scroll to top

### Loading States
- Skeleton screens per immagini con shimmer effect
- Lazy loading immagini con blur-up animation
- Progress bar top page per navigazione (Framer Motion)

### Hover Effects Globali
- Cards: lift + shadow increase
- Buttons: scale 1.02 + color darken
- Links: underline animation da sinistra
- Images: scale 1.05 su hover (overflow hidden)

### Scroll Animations
- Fade-in dal basso per sezioni principali
- Parallax leggero per background images
- Counter animations per numeri statistiche
- Progress bar che si riempie per liste

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px
- Large desktop: > 1440px

### Performance Optimization
- Lazy loading per tutte le immagini below fold
- WebP format con fallback
- Reduced motion per utenti con preferenze accessibilità
- Preload per font Montserrat

---

## NOTE FINALI PER LO SVILUPPATORE

1. **Accessibilità:**
   - Tutti i form fields con label associati
   - Focus states visibili su tutti gli elementi interattivi
   - Alt text descrittivi per immagini
   - ARIA labels per icone decorative
   - Keyboard navigation completa

2. **SEO:**
   - Heading hierarchy corretta (H1 > H2 > H3)
   - Meta description ottimizzata
   - Schema.org markup per LocalBusiness
   - Open Graph tags per social sharing

3. **Analytics:**
   - Event tracking su ogni CTA click
   - Form submit tracking
   - Scroll depth tracking
   - Time on page tracking

4. **Testing:**
   - Cross-browser testing (Chrome, Firefox, Safari, Edge)
   - Mobile responsiveness su vari device
   - Form validation testing
   - Performance testing (Lighthouse score > 90)

**La landing page è ora completa con tutti i testi ottimizzati per la conversione, strutturati per il template e con indicazioni dettagliate per implementazione tecnica con Framer Motion 12, Heroicons e Tailwind CSS 4.1+.**
