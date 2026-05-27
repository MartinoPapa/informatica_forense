# Note del Relatore – La raccolta illecita di dati tramite *form* online
**Presentazione Informatica Forense – Università degli Studi di Firenze**
**Durata prevista: ~10 minuti**

---

## SLIDE 1 – Titolo

Buongiorno a tutti. Siamo Martino Papa e Alessio Minati e oggi vi presenteremo il nostro elaborato dal titolo **"La raccolta illecita di dati tramite form online"**, prodotto nell'ambito del corso di Informatica Forense.

Il tema che affrontiamo riguarda un fenomeno molto diffuso ma spesso sottovalutato: la raccolta di dati personali attraverso moduli web — i cosiddetti *form* — che viene effettuata in modo non conforme alla normativa vigente. Analizzeremo i profili sia amministrativi che penali di questo fenomeno.

---

## SLIDE 2 – Riferimenti normativi

Prima di entrare nel merito, è fondamentale definire il quadro normativo di riferimento. La disciplina della protezione dei dati personali è articolata su più livelli.

Il principale strumento normativo è il **GDPR**, acronimo di *General Data Protection Regulation*, ovvero il **Regolamento (UE) 2016/679** del Parlamento europeo e del Consiglio, del 27 aprile 2016. Si tratta di un regolamento europeo, quindi direttamente applicabile in tutti gli Stati membri senza necessità di recepimento.

A livello nazionale, il GDPR si affianca al **D.Lgs. 196/2003**, il cosiddetto **Codice Privacy**, ovvero il Codice in materia di protezione dei dati personali. Questo è stato profondamente modificato dal **D.Lgs. 101/2018** per essere adeguato alle disposizioni del GDPR.

Sul piano dei diritti fondamentali, rilevano l'**art. 8 della CDFUE**, cioè la *Carta dei Diritti Fondamentali dell'Unione Europea*, nota anche come Carta di Nizza, e l'**art. 8 della CEDU**, la *Convenzione Europea per la Salvaguardia dei Diritti dell'Uomo e delle Libertà Fondamentali*. Entrambi tutelano il diritto alla protezione dei dati personali come diritto fondamentale della persona.

---

## SLIDE 3 – Dati personali e dati particolari

Vediamo ora le definizioni chiave. Il **GDPR**, all'articolo 4, paragrafo 1, definisce **dato personale** come qualsiasi informazione riguardante una persona fisica identificata o identificabile. Si tratta quindi di una definizione molto ampia, che include non solo nome e cognome, ma anche indirizzi email, numeri di telefono, dati di geolocalizzazione, ecc.

Esiste poi una categoria di dati che richiede una tutela rafforzata: i **dati particolari**, definiti dall'**articolo 9 del GDPR**, corrispondenti ai cosiddetti **dati sensibili** nel linguaggio del Codice Privacy. Per questi dati vige un **divieto generale di trattamento**, salvo casi tassativamente previsti dalla legge. La regola è il divieto; l'eccezione, il consenso esplicito.

Un *form* online che contenga campi relativi a questi dati — anche solo come campi facoltativi — senza una base giuridica appropriata è già, di per sé, in violazione del Regolamento.

---

## SLIDE 4 – Norme per la creazione di form online

L'**articolo 5 del GDPR** enuncia i principi fondamentali che devono guidare qualsiasi trattamento di dati personali. Questi principi devono essere rispettati già nella fase di progettazione del *form*, secondo il principio della *privacy by design*.

Vediamo brevemente i sei principi:

- **(a) Liceità, correttezza e trasparenza**: la raccolta di dati deve fondarsi su una base giuridica valida tra quelle elencate dall'art. 6 GDPR: il consenso dell'utente, un contratto, un obbligo legale, la tutela di interessi vitali, un compito di interesse pubblico, oppure il legittimo interesse del titolare.

- **(b) Limitazione della finalità**: i dati raccolti tramite il *form* devono essere usati solo per gli scopi dichiarati nell'informativa; non possono essere riutilizzati per finalità diverse.

- **(c) Minimizzazione dei dati**: il *form* deve raccogliere solo i dati strettamente necessari. Un campo superfluo integra già una violazione del Regolamento.

- **(d) Esattezza**: il titolare deve garantire che i dati siano corretti e aggiornati.

- **(e) Limitazione della conservazione**: i dati non possono essere conservati a tempo indeterminato; devono essere cancellati una volta raggiunte le finalità del trattamento.

- **(f) Integrità e riservatezza**: il *form* deve essere protetto tecnicamente, con connessioni cifrate tramite il protocollo HTTPS/TLS e misure di sicurezza adeguate.

---

## SLIDE 5 – Obbligo di informativa e consenso

L'**articolo 13 del GDPR** impone al titolare del trattamento di fornire all'interessato, nel momento in cui i dati vengono raccolti, un'informativa chiara, accessibile e comprensibile. Un *form* privo di informativa, o che rimanda a un documento generico nascosto nel footer del sito, viola questo obbligo.

Quando la base giuridica è il **consenso** dell'utente — ai sensi dell'art. 6, par. 1, lett. (a) — l'**articolo 7 del GDPR** stabilisce che tale consenso debba essere:

- **Libero**: non si può subordinare l'accesso a un servizio alla prestazione del consenso per trattamenti non strettamente necessari.
- **Specifico**: un unico checkbox per più finalità diverse non è ammissibile; occorrono consensi separati per ogni finalità.
- **Informato**: il consenso deve essere prestato dopo aver letto un'informativa adeguata.
- **Inequivocabile**: le cosiddette *pre-ticked boxes* — caselle già spuntate di default — non costituiscono un consenso valido. L'utente deve compiere un'azione attiva.

---

## SLIDE 6 – Presunzione di responsabilità civile (Art. 82)

L'**articolo 82 del GDPR** introduce un meccanismo di responsabilità civile molto incisivo. Chiunque subisca un danno — materiale o immateriale — a causa di una violazione del Regolamento ha diritto al risarcimento da parte del titolare del trattamento.

Il punto cruciale è l'**inversione dell'onere della prova**: il titolare del trattamento non si presume innocente. Al contrario, deve essere lui a dimostrare che l'evento dannoso non gli è in alcun modo imputabile. In mancanza di tale prova liberatoria, la responsabilità è accertata.

Questa presunzione di responsabilità rende la conformità al GDPR non solo un obbligo legale, ma anche uno scudo contro le azioni risarcitorie degli utenti.

---

## SLIDE 7 – Sanzioni amministrative (Art. 83)

Le sanzioni amministrative previste dall'**articolo 83 del GDPR** sono irrogate in Italia dal **Garante per la protezione dei dati personali** e sono articolate su due livelli:

- **Sanzione ordinaria** (par. 4): fino a **10 milioni di euro**, oppure il **2%** del fatturato mondiale annuo dell'impresa — si applica il maggiore dei due. Riguarda violazioni come la mancata informativa o le irregolarità nel consenso.

- **Sanzione aggravata** (par. 5): fino a **20 milioni di euro**, oppure il **4%** del fatturato mondiale annuo. Si applica per violazioni più gravi, come il mancato rispetto dei principi fondamentali dell'art. 5 o il trattamento di dati particolari senza una valida base giuridica.

---

## SLIDE 8 – Profilo penale: Art. 167 – Trattamento illecito di dati

Passiamo ora al **profilo penalistico**. Il **D.Lgs. 196/2003** (Codice Privacy), nella versione aggiornata dal D.Lgs. 101/2018, contiene alcune norme penali specifiche.

L'**articolo 167** punisce il trattamento illecito di dati personali. Perché si configuri il reato occorrono:
1. il **fine di profitto** o il **fine di danno** verso altri;
2. il **nocumento** — ovvero un pregiudizio concretamente causato all'interessato;
3. la violazione di specifiche disposizioni del Codice.

La **pena base** è la **reclusione da sei mesi a un anno e sei mesi**. Se il trattamento illecito riguarda **dati particolari** (salute, biometria, orientamento sessuale, ecc.), la pena sale a **uno a tre anni** di reclusione.

La giurisprudenza ha chiarito che il danno può essere anche solo di natura morale — come la perdita del controllo sui propri dati — e che il profitto può essere qualsiasi tipo di beneficio, anche non economico.

---

## SLIDE 9 – Profilo penale: Art. 167-bis – Comunicazione e diffusione illecita su larga scala

L'**articolo 167-bis** del Codice Privacy, introdotto dal D.Lgs. 101/2018, riguarda un caso specifico e particolarmente grave: la **comunicazione o diffusione illecita** di dati personali su **larga scala**.

Il reato si configura quando qualcuno — al fine di trarne profitto o arrecare danno — comunica o diffonde un archivio di dati personali trattati su larga scala, in violazione delle disposizioni del GDPR. È il caso tipico del cosiddetto **data breach deliberato**: i dati raccolti tramite *form* vengono ceduti a terzi o pubblicati online senza autorizzazione.

La pena prevista è la **reclusione da uno a sei anni**, significativamente più severa rispetto all'art. 167.

---

## SLIDE 10 – Profilo penale: Art. 167-ter – Acquisizione fraudolenta su larga scala

L'**articolo 167-ter** del Codice Privacy completa il quadro penalistico. Punisce chiunque **acquisisca con mezzi fraudolenti** un archivio di dati personali trattati su larga scala.

Questa norma ha un'applicazione diretta ai *form* online: riguarda i cosiddetti **dark patterns**, ovvero moduli web progettati in modo ingannevole per indurre l'utente a fornire dati senza esserne pienamente consapevole. Si pensi a linguaggi ambigui, caselle oscure, falsi opt-out.

La pena è la **reclusione da uno a quattro anni**.

---

## SLIDE 11 – Caso pratico amministrativo

Illustriamo ora un caso pratico tratto dalla prassi del Garante Privacy italiano.

Nel **provvedimento del 29 aprile 2021**, il Garante ha sanzionato un ente pubblico che aveva predisposto sul proprio sito un *form* di contatto per raccogliere nome, cognome, email e telefono degli utenti, **senza alcuna informativa** ai sensi dell'art. 13 GDPR.

Il Garante ha accertato la violazione del principio di **liceità, correttezza e trasparenza** (art. 5, par. 1, lett. a GDPR) e ha irrogato una sanzione amministrativa pecuniaria, ordinando altresì la rettifica del modulo.

Questo caso rappresenta la violazione più comune: l'ente inserisce il *form* nel sito credendo che un generico rimando alla privacy policy nel footer del sito sia sufficiente. Non lo è.

---

## SLIDE 12 – Caso pratico penale

Sul fronte penale, la **Corte di Cassazione, Seconda Sezione penale, con la sentenza n. 1285 del 15 gennaio 2019**, ha confermato la condanna di un operatore che aveva raccolto sistematicamente dati personali degli utenti tramite un servizio web, senza il loro consenso, e li aveva ceduti a terzi a fini commerciali.

I punti chiave stabiliti dalla Corte:
- Il **fine di profitto** non richiede un guadagno effettivo: è sufficiente la **prospettiva di un vantaggio economico indiretto**.
- Il **nocumento** può consistere anche nella sola **perdita del controllo sui propri dati personali**, senza necessità di dimostrare un danno patrimoniale concreto.

Questa pronuncia è fondamentale per i *form* di profilazione commerciale.

---

## SLIDE 13 – Grazie per l'attenzione

Ringraziamo per l'attenzione. Siamo a disposizione per domande.

In sintesi, la predisposizione di un *form* online non è un'operazione neutra: chi raccoglie dati personali assume precisi obblighi di legge, la cui violazione può comportare sanzioni amministrative fino a 20 milioni di euro e conseguenze penali fino a sei anni di reclusione.

La conformità al GDPR non è quindi solo un adempimento burocratico, ma una misura concreta di tutela — tanto per gli utenti quanto per chi gestisce i servizi online.

Grazie.
