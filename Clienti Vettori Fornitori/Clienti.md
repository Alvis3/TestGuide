

# **Clienti**

## Introduzione:

Clienti è l’anagrafica fondamentale per cominciare a lavorare sul programma. E’ importante compilarla correttamente soprattutto ai fini della fatturazione elettronica.

Il modulo è un contenitore che raccoglie Clienti / Vettori / Fornitori, quindi ad ogni anagrafica aggiuntiva viene creato un Codice Anagrafica (Campo CODICE a sinistra) univoco. Ogni anagrafica quindi sarà a sé stante. Nel caso in cui un Cliente sia anche Vettore o Fornitore si dovrà creare una anagrafica nuova.

Regole per la fatturazione Elettronica:

 1. Non utilizzare caratteri speciali sia per Ragione Sociale che negli altri campi.
 2. Se il Codice Fiscale è uguale alla Partita Iva inserire solo Partita Iva.
 3. Inserire sempre CAP anche se non lo si conosce. Inserire 00000. Dev’essere di 5 cifre.
 4. Cliente Estero UE: indicare Partita Iva per intero, indicare nel campo Stato anche il codice identificativo Paese, mentre Codice SDI: XXXXXXX
 5. Cliente Estero Extra UE: Partita iva: 99999999999 e Codice SDI: XXXXXXX
 6. Cliente come Persona Fisica: Codice SDI: 0000000 e userà la PEC ("PEC x FE")
 7. Cliente Pubblica Amministrazione: Attivare il flag “Split” che indica “Split Payment”
 
 ![clienti1](https://user-images.githubusercontent.com/107242420/176886131-e6dc304a-ef42-4b63-ab76-376452e73ac7.jpg)


Altre Sedi: la parte in basso dell’anagrafica vi permette di inserire altre sedi di Fatturazione. Come filiali. La partita iva rimane la stessa, ma permette di creare due fatture distinte per sede.

## Per chi ha multiaziendale

Se si lascia vuoto il campo “Assegnato ad azienda”, si visualizzeranno tutti i clienti nei moduli operativi. Al contrario, se si attribuisce un’azienda, solo quell’azienda potrà lavorare con quel cliente. (Vale per tutte le altre anagrafiche)

## “Banca per stampa fattura”: (Modulo Banche)

Cliccare sul quadratino per aprire il modulo BANCHE (che trovate anche sul menu Anagrafiche). Fornirsi dell’IBAN e inserirlo nel campo. Poi cliccare il tasto
![Immagine1](https://user-images.githubusercontent.com/107242420/176431875-cafe9757-d1c2-4524-9261-20a1060acf7d.png) questo vi permetterà di compilare già tutti i campi grazie al nostro database. In caso contrario, compilare a mano.  IMPORTANTE: il modulo BANCHE è un contenitore dove è possibile registrare qualsiasi banche, quindi anche di fornitori. Per distinguerle, in alto basta mettere il flag “Propria”.

IMPORTANTE : *si intende LA BANCA CHE VOLETE IL VOSTRO CLIENTE VISUALIZZI POI IN FATTURA*

## Spese / Scadenze / Note

Troverete su “Spese Fattura”, le righe aggiuntive di fattura. Se impostate, per quel cliente vi usciranno sempre sulla fattura di default. Ricordarsi di compilare sempre tutti i campi di aggiunta.

01 – Aggiunta: Qualsiasi aggiunta ma se c’è, inserire BOLLO (SCRIVERE la parola BOLLO). Nel caso in cui non sia a carico del cliente usare la dicitura: BOLLO "(2simbolo euro)" e importo 0.

02 – Aggiunta: se c’è, inserire Lettera d’Intento

03 – Aggiunta: se c’è, CONTRATTO - CIG - CUP (seguire l’ordine e mantenere i trattini quando manca uno dei codici) es. - CIG - , se mancano CONTRATTO e CUP)

“Spostamento Scadenze” vi permette di impostare lo spostamento della scadenza della fattura in modo automatico.

Note Avviso può essere molto utile per la gestione interna, si possono impostare dei messaggi che verranno visualizzati tramite un pop up nel momento che si eseguono le azioni selezionate.

![CLIENTI2](https://user-images.githubusercontent.com/107242420/176892262-689baf67-0601-4d39-b037-e33c67199f93.png)

## Dati aggiuntivi:

![CLIENTI3](https://user-images.githubusercontent.com/107242420/176892313-9fa0b82a-feea-47c1-9a06-29d866ec450a.png)

Si possono inserire dei dati aggiuntivi, si sottolinea l'importanza dei campi: Polizza Vettoriale e iscrizione all’albo fondamentali perché possono generare la scadenza. Per le altre scadenze di cliente (anche Vettori Fornitori) si possono inserire dentro al pulsante ![Agenda](https://user-images.githubusercontent.com/107242420/176893376-5c7b6ddf-678c-4844-8984-b4bb16eb4c16.PNG) nonché l' AGENDA, lo stesso modulo che trovate in SCADENZE nel menu principale.

Sulla schermata troverete anche il collegamento al modulo Agenti. Seguire i seguenti passaggi per inserire gli Agenti:

1. Nuovo agente e inserire i dati.
2. Configurare la provvigione, quindi cliccare per aprire il pannello. Inserire la provvigione, o le provvigioni in base al fatturato (Spunta RANGE). Successivamente selezionarsi la provvigione e salvare. (Primo Riquadro da sinistra)
3. Lo stesso Agente abbinarlo al cliente o ai clienti in tendina. (riquadro TASTO ABBINA)
4. Riportare la provvigione al cliente selezionandolo nel riquadro di elenco e mettendo il pallino su "Riporta Provvigione". (terzo riquadro)
![AGENTI](https://user-images.githubusercontent.com/107242420/176897629-2bbf786d-eb14-40a2-b007-20b1207e4a85.png)

