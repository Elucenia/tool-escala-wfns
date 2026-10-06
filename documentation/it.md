<!-- ELUCENIA technical documentation · escala-wfns · it · no clinical/professional/rights approval -->

# Scala WFNS

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/escala-wfns)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Scala del coma di Glasgow

`gcs`

punti · intervallo: 3–15

### Deficit motorio focale (emiparesi, afasia)

`deficit`

- `0` — Assente
- `1` — Presente

## Edizione del metodo

WFNS/Teasdale 1988: GCS e deficit motorio, 5 gradi

## Formula documentata

I: Glasgow 15, senza deficit motorio · II: 13 a 14, senza deficit · III: 13 a 14, con deficit · IV: 7 a 12, con/senza deficit · V: 3 a 6, con/senza deficit.

## Limiti e popolazione

La WFNS del 1988 combina Glasgow e deficit motorio per graduare l’emorragia subaracnoidea; il grado zero della fonte corrisponde a un aneurisma non rotto ed è distinto dai cinque gradi di emorragia. Usare un punteggio di Glasgow clinicamente valutabile e documentare i fattori che interferiscono con l’esame. L’articolo non descrive la combinazione di Glasgow 15 con deficit motorio; l’interfaccia mantiene il grado I e mostra questa riserva, senza presentarla come una combinazione validata. Questa è l’edizione originale, non una WFNS modificata successiva, e non fornisce una prognosi individuale automatica.

## Riferimenti

- [Teasdale GM et al. A universal subarachnoid hemorrhage scale: report of a committee of the World Federation of Neurosurgical Societies. J Neurol Neurosurg Psychiatry, 1988.](https://doi.org/10.1136/jnnp.51.11.1457)

- [WFNS1988,original JNNPletter,p1457](https://cdn.ncbi.nlm.nih.gov/pmc/blobs/2309/1032822/5084dd0d5156/jnnpsyc00546-0085.png)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Risultati documentati

Le informazioni seguenti conservano gli output del metodo per esempi sintetici. Non costituiscono una validazione clinica indipendente.

### 1

ESA di buon grado clinico (WFNS I a III)

| Dettagli del risultato | |
| --- | --- |
| Glasgow | 15 |
| Deficit motorio focale | assente |


### 2

ESA di buon grado clinico (WFNS I a III)

| Dettagli del risultato | |
| --- | --- |
| Glasgow | 13 |
| Deficit motorio focale | assente |


### 3

ESA di buon grado clinico (WFNS I a III)

| Dettagli del risultato | |
| --- | --- |
| Glasgow | 14 |
| Deficit motorio focale | presente |


### 4

ESA di cattivo grado clinico (WFNS IV e V)

| Dettagli del risultato | |
| --- | --- |
| Glasgow | 7 |
| Deficit motorio focale | assente |


### 5

ESA di cattivo grado clinico (WFNS IV e V)

| Dettagli del risultato | |
| --- | --- |
| Glasgow | 6 |
| Deficit motorio focale | presente |

