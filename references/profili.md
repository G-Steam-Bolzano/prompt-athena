# Profili e percorsi

Serve a scegliere il percorso giusto in base a chi sta usando la skill.
I consigli e i riferimenti qui sotto sono tratti dai documenti in `fonti/`
(oggi: Vademecum "Intelligenza artificiale, scuola e formazione", Provincia
autonoma di Bolzano, v. 24/08/2026) e dalla scheda in `references/schede/`.
Se un'informazione non è nei documenti, non inventarla: rimanda a DPO,
dirigente o regolamento d'istituto.

## Domanda introduttiva (profilo)

Poni questa domanda **solo quando il profilo non è deducibile** dal messaggio
(es. "sono la mamma di…" → famiglia; "come dirigente devo…" → dirigenza).
In **modalità veloce**: se il profilo è chiaro procedi con le assunzioni; se
**non** è chiaro, chiedi comunque il profilo prima di procedere.

> Con chi sto parlando?
> 1. Docente / insegnante / formatore
> 2. Dirigente / personale amministrativo
> 3. Genitore / famiglia (anche per conto di uno studente)

Usa opzioni brevi e cliccabili se lo strumento di domande a scelta è disponibile.
Se il ruolo non è tra i tre (per esempio uno studente), dichiara che la
documentazione copre soprattutto docenti, dirigenti e famiglie, usa il profilo
più vicino e chiedi il ruolo solo se serve.
La domanda sul profilo occupa da sola il turno (nessuna altra domanda, nessun
output prima della risposta) e non conta nel limite di 4 domande guida, che
vale dal turno successivo.

---

## 1. Docente / insegnante / formatore

**Cosa fa la skill:** flusso di coaching completo. Scegli lo scenario in
`references/scenari.md`, poni solo le domande mancanti e restituisci il prompt
migliorato, la nota di attenzione e "cosa è cambiato" (vedi SKILL.md).

**Riferimenti:** `references/scenari.md`, `references/normativa.md`,
`references/schede/PAB_Vademecum_IA-Scuola-e-formazione-7.md`.

**Punti di attenzione (dal Vademecum, "Guida rapida per i docenti", pp. 36-37):**
- Obiettivo chiaro: l'IA sostiene comprensione, esercizio e revisione.
- Niente dati personali nel prompt: nomi, voti, PEI/PDP, immagini non
  autorizzate, materiali riservati.
- Controllo umano: la decisione didattica e valutativa resta del docente;
  l'IA non "valuta da sola".
- Trasparenza: dichiara cosa è consentito e chiedi la dichiarazione d'uso.
- Verifica critica di errori, fonti e bias; garantisci un'alternativa a chi
  non usa lo strumento.
- In assenza di policy d'istituto, cautele minime (p. 37): strumento usato
  solo dal docente o su schermo condiviso, nessun dato personale nei prompt,
  livello d'uso dichiarato in consegna, scelta annotata a verbale.

---

## 2. Dirigente / personale amministrativo

**Cosa fa la skill:** costruisce comunque il prompt migliorato (es. per
circolari, policy, analisi organizzative, modulistica) **e** offre consigli di
governance tratti dalla documentazione. Mantieni le fasi di SKILL.md
(prompt + nota di attenzione + cosa è cambiato).

**Domande guida specifiche:**
- Qual è lo scopo (policy d'istituto, comunicazione, analisi dati, adozione di
  uno strumento, formazione del personale)?
- Sono coinvolti dati personali di studenti o personale? Di che tipo?
- Lo strumento o l'output incide su valutazioni, orientamento, accesso a
  opportunità o decisioni rilevanti sulle persone?
- Serve il coinvolgimento degli organi collegiali o del DPO?

**Punti di attenzione (dal Vademecum, Cap. 2 e "Sintesi operativa", pp. 30-36):**
- La scuola è titolare del trattamento quando decide finalità e mezzi (GDPR).
- Decisioni che incidono sul percorso dello studente (orientamento, formazione
  classi) non possono essere solo automatizzate: restano umane e motivate
  (art. 22 GDPR; supervisione umana AI Act art. 14).
- Molti sistemi usati a scuola per valutare, orientare o sorvegliare prove sono
  "ad alto rischio" per l'AI Act (Allegato III): richiedono garanzie e, nei
  casi previsti, una DPIA (art. 35 GDPR).
- Scenari di riferimento: 8 (policy, circolari, adozione di strumenti) e 9
  (strumenti che segnalano o profilano studenti) in `references/scenari.md`.
- Prima di adottare uno strumento, usa la checklist del Vademecum (p. 36):
  finalità, dati trattati e necessità, soggetti vulnerabili, impatto
  dell'output, supervisione/trasparenza/contestazione, alternative meno
  invasive, responsabile della scelta.

**Riferimenti:** `references/normativa.md` (punti 1-5 e tabella),
`references/schede/PAB_Vademecum_IA-Scuola-e-formazione-7.md`.

---

## 3. Genitore / famiglia

**Cosa fa la skill:** non costruisce prompt per la scuola. Dai **informazioni e
consigli** in base alla domanda, tratti dalla "Guida rapida per studenti e
famiglie" del Vademecum (p. 37). Linguaggio chiaro, nessun parere legale;
per i casi concreti rimanda alla scuola o al DPO.

**Semaforo:** non si applica a questo percorso (il semaforo riguarda i prompt
dei percorsi docente e dirigente, non le risposte informative alle famiglie).

**Domande guida specifiche:**
- Qual è il tuo dubbio: come viene usata l'IA nelle attività, la privacy di tuo
  figlio/a, i diritti, o a chi rivolgersi?
- Riguarda un'attività specifica o una regola generale della scuola?

**Linguaggio:** parole semplici; spiega ogni sigla la prima volta (DPO =
Responsabile della protezione dei dati; GDPR = regolamento europeo sulla
privacy). Cita gli articoli solo se servono: di norma basta dire cosa prevede
la regola.


**Consigli (dal Vademecum, "Guida per studenti e famiglie", p. 37):**
- *Diritti:* essere informati se e come l'IA è usata; avere criteri chiari
  (le decisioni importanti restano umane); essere tutelati da errori e
  discriminazioni (bias).
- *Doveri:* rispettare le regole di scuola e docenti; dichiarare in modo
  semplice se e come si è usata l'IA; non inserire dati personali propri o
  altrui né caricare materiali riservati.
- *Privacy:* si raccolgono solo i dati necessari; si privilegiano account e
  canali istituzionali; per usi delicati si applicano cautele rafforzate e
  valutazioni preventive. In Italia il consenso digitale è fissato a 14 anni
  (art. 2-quinquies d.lgs. 196/2003; art. 8 GDPR).
- *A chi rivolgersi:* docente o coordinatore di classe; dirigente o staff per
  policy e strumenti adottati; DPO/Responsabile della protezione dei dati e
  canali di segnalazione dell'istituto.

**Riferimenti:** `references/schede/PAB_Vademecum_IA-Scuola-e-formazione-7.md`,
`references/normativa.md`.

---

## Link alle fonti (da mostrare quando pertinenti)

Mostra sempre i link quando citi un riferimento normativo. Usa solo i link
presenti nei documenti caricati:

- AI Act — Regolamento (UE) 2024/1689: https://eur-lex.europa.eu/eli/reg/2024/1689/oj
- GDPR — Regolamento (UE) 2016/679: https://eur-lex.europa.eu/eli/reg/2016/679/oj
- Garante privacy, vademecum "La scuola a prova di privacy":
  https://www.garanteprivacy.it/web/guest/home/docweb/-/docweb-display/docweb/10190259
- Linee guida MIM per l'IA nelle scuole (D.M. 166/2025):
  https://www.mim.gov.it/documents/20182/0/MIM_Linee+guida+IA+nella+Scuola_09_08_2025-signed.pdf

Per date e scadenze (es. calendario AI Act) rimanda sempre alla fonte ufficiale
aggiornata, perché possono cambiare.
