# Index

- [English](#security-and-vulnerability-reporting)
- [Italiano](#segnalazione-di-vulnerabilità-e-problemi-di-sicurezza)

---

## Security and Vulnerability Reporting

**Effective Date:** 2026-06-01  
**Primary language:** English  
**Organization:** fubit-dev

---

## Purpose

This document describes how to report security vulnerabilities affecting fubit-dev projects and how we handle responsible disclosure. It defines required reporting channels, encryption and signing requirements, response timelines, data retention, and access controls.

---

## Scope

- **Applies to:** all interactions related to fubit-dev repositories, services, and assets.
- **Repository visibility:** repositories are private and accessible only to authorized personnel. Opening an issue inside a private repository implies you are authorized personnel. External reporters who discover code or issues in public locations (mirrors, paste sites, forks, public leaks) must report privately via the email below.

---

## Reporting contact (private)

- **Preferred method:** email to **<fubit-dev@protonmail.com>**.
- **Do not** post vulnerability details in public issues, comments, or forums.

---

## Mandatory encryption and signing requirements

To protect sensitive information, **all vulnerability reports must be submitted already encrypted and signed** as follows:

1. **Sign the report** with your personal PGP/GPG private key so Team Admins can verify the reporter identity.
2. **Encrypt the signed report** to the Team Admins’ PGP public key so only Team Admins can decrypt it.
3. **Include your PGP public key** (or a link to it) with the submission so Team Admins can verify the signature.
4. If you cannot perform signing and encryption, contact us by email first to arrange an alternative secure channel before sending sensitive details.

> Note: If you are an authorized internal reporter and cannot use PGP for technical reasons, contact Team Admins to arrange an alternative secure method prior to sending sensitive data.

**How to submit:** attach the encrypted file to an email to **<fubit-dev@protonmail.com>**. In the email subject line include: `Security report — [short title]`. In the email body include only non-sensitive metadata (reporter contact, preferred encrypted attachment filename, and whether you request anonymity).

---

## What not to publish publicly

Do **not** publish exploit code, private keys, passwords, personally identifiable information, or proof-of-concept exploits in public issues, comments, or repositories. If your report contains sensitive material, use the encrypted email channel above.

---

## Information to include (non-sensitive metadata)

When possible, include the following (safely, and encrypted if sensitive):

- **Short title** of the issue.
- **Description** of impact and observed behavior.
- **Affected versions** (e.g., `v1.2.3`, commit SHA, or range).
- **Steps to reproduce** (commands, inputs, environment).
- **Minimal reproducible example** or PoC (encrypted if exploitative).
- **Logs, stack traces, outputs** (encrypted if sensitive).
- **Workarounds** or mitigations tried.
- **Preferred contact** for private follow-up.
- **Reporter PGP public key** or link to it (for signature verification).

---

## Handling and response times

- **Acknowledgement:** Team Admins will acknowledge receipt within **5 business days**.
- **Initial assessment:** we will classify severity and reproducibility and may request additional details.
- **Updates:** we will provide regular updates until resolution.
- **Coordination:** we will coordinate remediation and disclosure with the reporter.

---

## Responsible team and access control

- **Who handles reports:** Team Admins are the only group authorized to receive, decrypt, and handle vulnerability reports.
- **Access to report data:** strictly limited to Team Admins. No other personnel will access report contents unless explicitly required for remediation and approved by Team Admins.
- **Private repositories:** only authorized personnel may view private repositories. Opening an issue inside a private repository indicates you are authorized personnel. External reporters must use the private email channel.

---

## Retention and data protection

- **Retention period:** report data and related materials will be retained for up to **2 years** from the date of resolution, unless legal obligations require longer retention.
- **Storage:** all report data will be stored encrypted.
- **Access:** only Team Admins may access stored report data.
- **Deletion:** after the retention period (or earlier if requested and not legally constrained), data will be securely deleted.

---

## CVE, advisories, and disclosure

- When appropriate, we will coordinate with the reporter to request or assign a **CVE** and publish a joint advisory after a fix is available.
- We will not publish technical details before a fix or mitigation is available, except by mutual agreement with the reporter.
- If a vulnerability is publicly disclosed before a fix, we will prioritize mitigation and may accelerate disclosure. Unauthorized public disclosure may lead to enforcement actions as described in **LICENSE.md**.

---

## Interaction with other policies

- See **LICENSE.md** for licensing and legal restrictions.
- See **CODE_OF_CONDUCT.md** for expected behavior when interacting with the project and reporting processes.
- See **CONTRIBUTING.md** for contribution rules and PR review requirements.

---

## Reporting workflow (summary)

1. Prepare a signed report and encrypt it to the Team Admins PGP public key.
2. Email the encrypted attachment to **<fubit-dev@protonmail.com>** with subject `Security report — [short title]`.
3. Team Admins acknowledge within **5 business days** and begin triage.
4. Team Admins coordinate remediation, CVE/advisory (if applicable), and disclosure timeline with the reporter.
5. After resolution, report data is retained up to **2 years**, then securely deleted unless legal reasons require otherwise.

---

## If you are an external reporter

If you are not authorized personnel and you discover code or issues in public locations (mirrors, paste sites, forks, or other public disclosures), **do not** open public issues. Report privately by encrypting and emailing the details to **<fubit-dev@protonmail.com>**.

---

## Contact and escalation

- **Primary contact:** <fubit-dev@protonmail.com>
- **Responsible group:** Team Admins

---

**Effective Date:** 2026-06-01  
**Version:** 1.0

---

## Segnalazione di vulnerabilità e problemi di sicurezza

**Data di entrata in vigore:** 01/06/2026  
**Lingua principale:** inglese  
**Organizzazione:** fubit-dev

---

## Scopo

Il presente documento descrive le modalità di segnalazione delle vulnerabilità di sicurezza che interessano i progetti fubit-dev e le nostre procedure di divulgazione responsabile. Definisce i canali di segnalazione obbligatori, i requisiti di crittografia e firma, i tempi di risposta, la conservazione dei dati e i controlli di accesso.

---

## Ambito di applicazione

- **Si applica a:** tutte le interazioni relative ai repository, ai servizi e alle risorse di fubit-dev.
- **Visibilità del repository:** i repository sono privati e accessibili solo al personale autorizzato. L'apertura di un ticket all'interno di un repository privato implica che tu sia personale autorizzato. I segnalatori esterni che scoprono codice o problemi in luoghi pubblici (mirror, siti di paste, fork, fughe di notizie pubbliche) devono segnalarli in privato tramite l'indirizzo e-mail riportato di seguito.

---

## Contatti per la segnalazione (riservati)

- **Metodo preferito:** inviare un'e-mail a **<fubit-dev@protonmail.com>**.
- **Non** pubblicare i dettagli delle vulnerabilità in ticket pubblici, commenti o forum.

---

## Requisiti obbligatori di crittografia e firma

Per proteggere le informazioni sensibili, **tutte le segnalazioni di vulnerabilità devono essere inviate già crittografate e firmate** come segue:

1. **Firmare la segnalazione** con la propria chiave privata PGP/GPG in modo che gli amministratori del team possano verificare l'identità del segnalante.
2. **Crittografare la segnalazione firmata** con la chiave pubblica PGP degli amministratori del team in modo che solo loro possano decrittografarla.
3. **Includi la tua chiave pubblica PGP** (o un link ad essa) con l'invio in modo che gli amministratori del team possano verificare la firma.
4. Se non riesci a eseguire la firma e la crittografia, contattaci prima via e-mail per concordare un canale sicuro alternativo prima di inviare dettagli sensibili.

> Nota: se sei un segnalatore interno autorizzato e non puoi utilizzare PGP per motivi tecnici, contatta gli amministratori del team per concordare un metodo sicuro alternativo prima di inviare dati sensibili.

**Come inviare la segnalazione:** allega il file crittografato a un'e-mail indirizzata a **<fubit-dev@protonmail.com>**. Nell'oggetto dell'e-mail includi: `Segnalazione di sicurezza — [titolo breve]`. Nel corpo dell'e-mail includi solo metadati non sensibili (contatti del segnalante, nome file preferito per l'allegato crittografato e se richiedi l'anonimato).

---

## Cosa non pubblicare pubblicamente

**Non** pubblicare codice di exploit, chiavi private, password, informazioni di identificazione personale o exploit proof-of-concept in segnalazioni pubbliche, commenti o repository. Se la tua segnalazione contiene materiale sensibile, utilizza il canale di posta elettronica crittografata indicato sopra.

---

## Informazioni da includere (metadati non sensibili)

Quando possibile, includi quanto segue (in modo sicuro e crittografato se sensibile):

- **Titolo breve** del problema.
- **Descrizione** dell'impatto e del comportamento osservato.
- **Versioni interessate** (ad es., `v1.2.3`, SHA del commit o intervallo).
- **Passaggi per riprodurre il problema** (comandi, input, ambiente).
- **Esempio minimo riproducibile** o PoC (crittografato se sfruttabile).
- **Log, tracce dello stack, output** (crittografati se sensibili).
- **Soluzioni alternative** o misure di mitigazione provate.
- **Contatto preferito** per un follow-up privato.
- **Chiave pubblica PGP del segnalante** o link ad essa (per la verifica della firma).

---

## Gestione e tempi di risposta

- **Conferma di ricezione:** gli amministratori del team confermeranno la ricezione entro **5 giorni lavorativi**.
- **Valutazione iniziale:** classificheremo la gravità e la riproducibilità e potremmo richiedere ulteriori dettagli.
- **Aggiornamenti:** forniremo aggiornamenti regolari fino alla risoluzione del problema.
- **Coordinamento:** coordineremo la risoluzione del problema e la divulgazione con il segnalante.

---

## Team responsabile e controllo degli accessi

- **Chi gestisce le segnalazioni:** gli amministratori del team sono l'unico gruppo autorizzato a ricevere, decriptare e gestire le segnalazioni di vulnerabilità.
- **Accesso ai dati delle segnalazioni:** strettamente limitato agli amministratori del team. Nessun altro membro del personale avrà accesso ai contenuti delle segnalazioni, a meno che non sia esplicitamente richiesto per la correzione e approvato dagli amministratori del team.
- **Repository privati:** solo il personale autorizzato può visualizzare i repository privati. L'apertura di un ticket all'interno di un repository privato indica che sei personale autorizzato. I segnalatori esterni devono utilizzare il canale e-mail privato.

---

## Conservazione e protezione dei dati

- **Periodo di conservazione:** i dati dei rapporti e i materiali correlati saranno conservati per un massimo di **2 anni** dalla data di risoluzione, a meno che obblighi di legge non richiedano una conservazione più lunga.
- **Archiviazione:** tutti i dati dei rapporti saranno archiviati in forma crittografata.
- **Accesso:** solo gli amministratori del team potranno accedere ai dati dei rapporti archiviati.
- **Cancellazione:** al termine del periodo di conservazione (o prima, se richiesto e non vincolato da obblighi legali), i dati saranno cancellati in modo sicuro.

---

## CVE, avvisi e divulgazione

- Se opportuno, ci coordineremo con il segnalante per richiedere o assegnare un **CVE** e pubblicheremo un avviso congiunto una volta che sarà disponibile una correzione.
- Non pubblicheremo dettagli tecnici prima che sia disponibile una correzione o una misura di mitigazione, salvo accordo reciproco con il segnalante.
- Se una vulnerabilità viene divulgata pubblicamente prima di una correzione, daremo priorità alla mitigazione e potremo accelerare la divulgazione. La divulgazione pubblica non autorizzata può comportare azioni coercitive come descritto in **LICENSE.md**.

---

## Interazione con altre politiche

- Consulta **LICENSE.md** per le licenze e le restrizioni legali.
- Consulta **CODE_OF_CONDUCT.md** per conoscere il comportamento previsto nell'interazione con il progetto e le procedure di segnalazione.
- Consulta **CONTRIBUTING.md** per le regole di contribuzione e i requisiti di revisione delle PR.

---

## Flusso di lavoro per le segnalazioni (sintesi)

1. Preparare una segnalazione firmata e crittografarla con la chiave pubblica PGP degli amministratori del team.
2. Inviare l'allegato crittografato via e-mail a **<fubit-dev@protonmail.com>** con oggetto `Segnalazione di sicurezza — [titolo breve]`.
3. Gli amministratori del team confermeranno la ricezione entro **5 giorni lavorativi** e inizieranno la valutazione.
4. Gli amministratori del team coordinano con il segnalante le misure correttive, il CVE/avviso (se applicabile) e i tempi di divulgazione.
5. Dopo la risoluzione, i dati della segnalazione vengono conservati per un massimo di **2 anni**, quindi cancellati in modo sicuro, salvo diversamente richiesto da motivi legali.

---

## Se sei un segnalatore esterno

Se non fai parte del personale autorizzato e individui codice o problemi in spazi pubblici (mirror, siti di paste, fork o altre pubblicazioni pubbliche), **non** aprire ticket pubblici. Segnalali in privato inviando i dettagli crittografati via e-mail a **<fubit-dev@protonmail.com>**.

---

## Contatti ed escalation

- **Contatto principale:** <fubit-dev@protonmail.com>
- **Gruppo responsabile:** Amministratori del team

---

**Data di entrata in vigore:** 01/06/2026  
**Versione:** 1.0
