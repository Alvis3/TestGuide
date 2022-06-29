

# **Clienti**

## Introduzione:

Clienti è l’anagrafica fondamentale per cominciare a lavorare sul programma. E’ importante compilarla correttamente soprattutto ai fini della fatturazione elettronica.

Il modulo è un contenitore che raccoglie Clienti / Vettori / Fornitori, quindi ad ogni anagrafica aggiuntiva viene creato un Codice Anagrafica (Campo CODICE a sinistra) univoco. Ogni anagrafica quindi sarà a sé stante. Nel caso in cui un Cliente sia anche Vettore o Fornitore si dovrà creare una anagrafica nuova.

Regole per la fatturazione Elettronica:

 - Non utilizzare caratteri speciali sia per Ragione Sociale che negli altri campi.
 - Se il Codice Fiscale è uguale alla Partita Iva inserire solo Partita Iva.
 - Inserire sempre CAP anche se non lo si conosce. Inserire 00000. Dev’essere di 5 cifre.
 - Cliente Estero UE: indicare Partita Iva per intero, indicare nel campo Stato anche il codice identificativo Paese, mentre Codice SDI: XXXXXXX
 - Cliente Estero Extra UE: Partita iva: 99999999999 e Codice SDI: XXXXXXX
 - Cliente come Persona Fisica: Codice SDI: 0000000 e userà la PEC
 - Cliente Pubblica Amministrazione: Attivare il flag “Split” che indica “Split Payment”

Altre Sedi: la parte in basso dell’anagrafica vi permette di inserire altre sedi di Fatturazione. Come filiali. La partita iva rimane la stessa, ma permette di creare due fatture distinte per sede.

## Per chi ha multiaziendale

Se si lascia vuoto il campo “Assegnato ad azienda”, si visualizzeranno tutti i clienti nei moduli operativi. Al contrario, se si attribuisce un’azienda, solo quell’azienda potrà lavorare con quel cliente. (Vale per tutte le altre anagrafiche)

## “Banca per stampa fattura”: (Modulo Banche)

Cliccare sul quadratino per aprire il modulo BANCHE (che trovate anche sul menu Anagrafiche). Fornirsi dell’IBAN e inserirlo nel campo. Poi cliccare il tasto
![Immagine1](https://user-images.githubusercontent.com/107242420/176431875-cafe9757-d1c2-4524-9261-20a1060acf7d.png) questo vi permetterà di compilare già tutti i campi grazie al nostro database. In caso contrario, compilare a mano.  IMPORTANTE: _il modulo BANCHE è un contenitore dove è possibile registrare qualsiasi banche, quindi anche di fornitori. Per distinguerle, in alto basta mettere il flag “Propria”.

## Spese / Scadenze / Note

Troverete su “Spese Fattura”, le righe aggiuntive di fattura. Se impostate, per quel cliente vi usciranno sempre sulla fattura di default. Ricordarsi di compilare sempre tutti i campi di aggiunta.

01 – Aggiunta: Qualsiasi aggiunta ma se c’è, inserire BOLLO (SCRIVERE la parola BOLLO). Nel caso in cui non sia a carico del cliente usare la dicitura: BOLLO "(2simbolo euro)" e importo 0.

02 – Aggiunta: se c’è, inserire Lettera d’Intento

03 – Aggiunta: se c’è, CONTRATTO - CIG - CUP (seguire l’ordine e mantenere i trattini quando manca uno dei codici) es. - CIG - , se mancano CONTRATTO e CUP)

“Spostamento Scadenze” vi permette di impostare lo spostamento della scadenza della fattura in modo automatico.

Note Avviso può essere molto utile per la gestione interna, si possono impostare dei messaggi che verranno visualizzati tramite un pop up nel momento che si eseguono le azioni selezionate.

## Dati aggiuntivi:

Campi importanti-> Polizza Vettoriale e iscrizione all’albo.
