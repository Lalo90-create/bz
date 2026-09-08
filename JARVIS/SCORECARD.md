# JARVIS SCORECARD

## Obiettivo
Misurare se JARVIS sta producendo valore reale e se lo stack AI genera più valore di quanto costa.

## KPI principali
Traccia settimanalmente o mensilmente:
- ricavi generati;
- opportunità qualificate create;
- conversazioni / meeting;
- proposte;
- vendite concluse;
- ore risparmiate;
- asset riutilizzabili creati;
- processi migliorati;
- competenze AI acquisite.

## Mantieni separati i due business engine

### BZ Consulting funnel
**Lead → Qualified → Conversation → Audit/Discovery → Proposal → Project → Follow-on service**

Traccia:
- lead BZ qualificati;
- paese / mercato;
- meeting tecnici/commerciali;
- proposte;
- pipeline stimata;
- ricavi chiusi;
- partnership/referral.

### Bazinga Lab / CSC funnel
**Club → Qualified → Contact → Conversation → Small paid entry → Recurring service → Referral**

Traccia:
- CSC/club qualificati;
- paese / mercato;
- contatti personalizzati;
- risposte;
- meeting/conversazioni;
- audit/training/menu/event/CRM pilot venduti;
- clienti ricorrenti;
- referral;
- ricavi Bazinga.

## Vista geografica
JARVIS deve poter distinguere performance per:
- area locale / Murcia;
- Spagna;
- Europa;
- altri mercati globali.

Questo serve a capire dove esiste il miglior rapporto tra accesso, conversione e valore.

## Tabella settimanale
| Periodo | BZ Revenue € | Bazinga Revenue € | BZ Qualified Leads | CSC Qualified Leads | Meetings | Proposals / Paid Entries | Sales | Hours Saved | Assets | Skills |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| Week 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |

## Fast Cash vs Big Projects
Traccia entrambi:
- Fast Cash attivo;
- Big Projects in pipeline;
- valore stimato;
- mercato / paese;
- prossima azione;
- principale blocco.

## AI ROI
Quando esistono dati sufficienti:

**AI ROI = (Valore economico generato + valore dichiarato del tempo risparmiato - costo strumenti AI) / costo strumenti AI**

Non inventare il valore economico del tempo risparmiato: usa un'ipotesi dichiarata.

## JARVIS Operating Efficiency
Usa il tab privato `ACTIVITY` del Control Center come telemetria minima delle missioni sostanziali. Non creare un secondo database di activity.

Misura:
- **Autonomy Rate** = missioni completate senza interventi intermedi di Lautaro / missioni completate;
- **Human Intervention Rate** = interventi manuali di Lautaro per missione sostanziale;
- **Rework Rate** = missioni o deliverable che richiedono rifacimento / missioni completate;
- **Approval Efficiency** = approvazioni raggruppate e realmente necessarie rispetto alle interruzioni di approvazione;
- **Outcome Rate** = missioni che producono un risultato verificabile / missioni sostanziali;
- **Revenue Actions per Mission** = azioni che muovono una opportunità commerciale / missioni commerciali;
- **Tool Intensity** = numero di tool/app usati per risultato utile; deve diminuire quando la qualità resta invariata;
- **Context Discipline** = usare fonti canoniche rilevanti e contesto minimo sufficiente, non ricaricare tutto il sistema.

## ChatGPT Plus Resource Efficiency
JARVIS deve essere ottimizzato per il piano ChatGPT Plus corrente, senza assumere un saldo di token API o quote numeriche non esposte in modo affidabile dalla sessione.

Principi:
1. **Outcome per resource unit**: massimizzare risultato utile per quota, tempo, tool call e contesto, non il consumo di AI.
2. **Retrieve, don't reload**: recuperare solo le fonti necessarie alla missione. Non rileggere tutte le chat, Drive e GitHub ad ogni richiesta.
3. **Minimum sufficient reasoning**:
   - routine, lookup, CRM, organizzazione e status → livello più leggero disponibile;
   - business analysis e decisioni moderate → reasoning medio;
   - strategia, pricing, sistemi o high-stakes → reasoning alto solo quando cambia materialmente la qualità;
   - Work/agentic e Codex → solo quando l'esecuzione multi-step o engineering giustificano la quota.
4. **Automation compression**: preferire pochi watcher aggregati a watcher per singolo lead, post o cliente.
5. **Event/condition over blind polling** quando la capacità è disponibile; altrimenti usare la frequenza minima compatibile con il valore del segnale.
6. **WIP before generation**: completare e sbloccare lavoro esistente prima di generare nuovi asset o nuove ricerche.
7. **No fake token accounting**: se ChatGPT non espone token/quote effettivamente consumati, registrare proxy misurabili (`Reasoning Level`, `Context Scope`, `Tools Used`, `Quota / Cost Note`) invece di inventare numeri.
8. **Upgrade only on evidence**: valutare un piano superiore solo dopo 2–4 settimane di telemetria che dimostrino un limite reale con impatto economico o operativo.

### Resource Budget operativo
Default permanente:
- massimo **3 automazioni permanenti attive** quando possibile;
- mantenere **2 slot liberi** del limite Plus per missioni temporanee/strategiche;
- una sola automazione commerciale aggregata;
- una sola automazione marketing/project-management aggregata;
- una sola automazione executive quotidiana;
- review settimanale integrata nel brief del venerdì, senza task separato salvo necessità dimostrata.

## Review settimanale
JARVIS dovrebbe rispondere:
1. Quale engine ha prodotto più progresso: BZ o Bazinga?
2. Quale opportunità è più vicina al denaro?
3. Dove è bloccato il funnel?
4. Quale offerta riceve la risposta migliore?
5. Quale mercato sta convertendo meglio?
6. Cosa ripetere, modificare o fermare?
7. Cosa automatizzare senza aggiungere complessità inutile?
8. Quanto intervento manuale ha richiesto JARVIS?
9. Dove si è verificato rework evitabile?
10. Quali tool, automazioni o livelli di reasoning non hanno prodotto valore proporzionato?
11. Il piano Plus ha creato un limite reale oppure il problema è ancora workflow/discipline?

## Regola
Non ottimizzare vanity metrics come numero di post, prompt, documenti, tool call o token consumati.
Misura soprattutto:
**ricavi, conversione, opportunità qualificate, tempo risparmiato, autonomia, rework, capacità riutilizzabili e costo/rendimento delle risorse AI.**

GitHub conserva la cronologia: questo file rappresenta sempre lo stato corrente, senza copie versionate.
