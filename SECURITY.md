# Sicurezza e segnalazioni di vulnerabilità

Questo documento descrive come segnalare vulnerabilità di sicurezza relative ai progetti dell'organizzazione **fubit-dev** e come gestiamo la divulgazione responsabile.

---

## Contatto per segnalazioni riservate

**Metodo preferito**: invia una segnalazione privata a  
**Email**: `fubit-dev@protonmail.com`

Se non vuoi usare email, puoi aprire una segnalazione privata seguendo le istruzioni fornite dai maintainer (contatto disponibile nella pagina del repository).

---

## Cosa non pubblicare in una issue pubblica

**Non pubblicare** exploit completi, chiavi private, password, dati personali sensibili o PoC che consentono l'abuso immediato del sistema. Se la segnalazione contiene informazioni sensibili, usa il canale privato indicato sopra.

---

## Informazioni da includere nella segnalazione

Per aiutarci a valutare e riprodurre la vulnerabilità, includi quanto segue quando possibile:

- **Titolo sintetico** della vulnerabilità.  
- **Descrizione** dell'impatto e del comportamento osservato.  
- **Versioni interessate** (es. `v1.2.3`, range di versioni o commit SHA).  
- **Passi per riprodurre** (comandi, input, condizioni ambientali).  
- **Esempio minimo riproducibile** o PoC (se non sensibile; altrimenti invialo in privato).  
- **Log, stack trace, output** rilevanti.  
- **Eventuali workaround** o mitigazioni temporanee già provate.  
- **Contatto** per comunicazioni riservate (email o canale alternativo).

---

## Come gestiamo le segnalazioni

1. **Ricezione**: confermiamo la ricezione entro **72 ore** all'indirizzo fornito.  
2. **Valutazione**: classifichiamo la gravità e la riproducibilità; potremmo chiedere dettagli aggiuntivi.  
3. **Mitigazione**: lavoriamo su una correzione o mitigazione e coordiniamo la divulgazione responsabile.  
4. **Divulgazione**: concordiamo con il segnalante la tempistica della divulgazione pubblica; rilasciamo patch e advisory.  
5. **CVE**: se applicabile, richiediamo o assegniamo un identificatore CVE e pubblichiamo un advisory.

---

## Tempi di risposta e riservatezza

- **Prima risposta**: entro **72 ore**.  
- **Aggiornamenti**: forniremo aggiornamenti regolari fino alla risoluzione.  
- **Riservatezza**: trattiamo le segnalazioni in modo confidenziale fino alla divulgazione concordata.

---

## Processo di divulgazione responsabile

- Lavoriamo con il segnalante per risolvere il problema prima della divulgazione pubblica.  
- Non pubblicheremo dettagli tecnici completi fino a quando non sarà disponibile una correzione o una mitigazione adeguata.  
- Se il segnalante desidera la divulgazione coordinata, concordiamo una data e un advisory congiunto.

---

## Cosa succede se la segnalazione è pubblica

Se una vulnerabilità viene pubblicata pubblicamente prima che sia stata risolta, la priorità di intervento può aumentare e potremmo accelerare la mitigazione. Contattaci immediatamente tramite il canale privato.

---

## Ringraziamenti e riconoscimenti

Apprezziamo i contributi della community. Se desideri essere riconosciuto pubblicamente per la segnalazione, indicacelo; altrimenti rispetteremo l'anonimato su richiesta.

---

## Domande frequenti rapide

- **Posso inviare PoC?** Sì, ma preferibilmente tramite canale privato se il PoC è exploitabile.  
- **Assegnate CVE?** Sì, quando appropriato.  
- **Tempi di patch?** Dipendono dalla gravità e dalla complessità; forniremo stime dopo la valutazione iniziale.
