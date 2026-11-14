# Family Investor — Libera il denaro

Una skill per Claude che ti aiuta a trovare gli sprechi invisibili del bilancio familiare e a calcolare il tuo **risparmio annuo stimato**, voce per voce.

È tratta dal **Pilastro 1** del libro *Family Investor* di Daniele Di Gregorio ([familyinvestor.it](https://familyinvestor.it)).

**Zero promesse di rendimento. Solo metodo.**

## Cosa fa

Claude passa con te in rassegna fino a 7 aree, una alla volta:

1. Conto corrente e servizi bancari
2. Utenze luce e gas
3. Abbonamenti e sospensioni
4. Acquisti non urgenti: usato e ricondizionato
5. Farmacia: prodotti ricorrenti
6. Esami specialistici privati
7. Spesa con i figli

Per ogni area ricevi il costo annuo attuale, il risparmio stimato e una mossa concreta da 10 minuti. Alla fine trovi una tabella riepilogativa che separa i risparmi certi da quelli potenziali.

Lavora sui **tuoi** numeri: puoi caricare un estratto conto (oscura prima IBAN e numeri di carta) oppure rispondere a qualche domanda.

## Cosa NON fa

- Non dà consigli di investimento.
- Non dà consigli medici: per farmacia ed esami parla solo di prezzo e canale d'acquisto.
- Non ti indica un fornitore "migliore" in assoluto.

## Come installarla

### Prima di iniziare

- Serve un piano Claude **a pagamento** (Pro, Max, Team o Enterprise): con il piano gratuito l'opzione per caricare skill non compare.
- Nelle Impostazioni, sezione **Funzionalità**, l'esecuzione del codice deve essere attiva.
- Fai l'installazione **da computer** (sito claude.ai o app desktop). Una volta installata, la skill funziona anche dall'app sul telefono.

### Su claude.ai o sull'app desktop (la strada per tutti)

1. Scarica lo zip della skill: **[familyinvestor-sprechi.zip](https://github.com/dandigregorio/familyinvestor-sprechi/raw/main/familyinvestor-sprechi.zip)**
   ⚠️ **Non aprirlo e non estrarlo**: va caricato così com'è.
2. Apri Claude e vai in **Impostazioni → Personalizzazione → Skills**.
3. Clicca **+ Aggiungi**, scegli **Carica Skill** e seleziona lo zip.
4. Controlla che la skill compaia nell'elenco e che il suo interruttore sia **acceso**.
5. Apri una nuova chat e scrivi: *"Aiutami a trovare i miei sprechi"*.

### Su Claude Code (per utenti tecnici)

Scrivi questi due comandi:

```
/plugin marketplace add dandigregorio/familyinvestor-sprechi
/plugin install familyinvestor-sprechi@familyinvestor
```

## Aggiornamenti

Ogni tanto la skill viene migliorata. L'ultima versione è sempre il file zip qui sopra.

- **claude.ai / app desktop:** non si aggiorna da sola. Scarica di nuovo lo zip e caricalo al posto di quello vecchio.
- **Claude Code:** basta il comando `/plugin marketplace update`.

Il file della skill si può leggere anche direttamente qui: [`familyinvestor-sprechi/SKILL.md`](familyinvestor-sprechi/SKILL.md).

## E dopo?

Un risparmio su carta non è ancora denaro in più. Dargli un posto è il tema dei pilastri successivi del libro *Family Investor*, disponibile su Amazon. Trovi tutto su [familyinvestor.it](https://familyinvestor.it).

## Licenza

Uso libero e gratuito per uso personale. Il metodo e i testi sono © Daniele Di Gregorio.
