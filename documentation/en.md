<!-- ELUCENIA technical documentation · escala-wfns · en · no clinical/professional/rights approval -->

# WFNS scale

[conditions, sources and permissions](https://elucenia.org/en/tools/escala-wfns)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Glasgow Coma Scale

`gcs`

points · range: 3–15

### Focal motor deficit (hemiparesis, aphasia)

`deficit`

- `0` — Absent
- `1` — Present

## Method edition

WFNS/Teasdale 1988: GCS and motor deficit, 5 grades

## Documented formula

I: Glasgow 15, no motor deficit · II: 13 to 14, no deficit · III: 13 to 14, deficit · IV: 7 to 12, with/without deficit · V: 3 to 6, with/without deficit.

## Limits and population

The 1988 WFNS combines Glasgow and motor deficit to grade subarachnoid hemorrhage; grade zero in the source corresponds to an unruptured aneurysm and is distinct from the five hemorrhage grades. Use a Glasgow score that can be assessed clinically and document factors that interfere with the examination. The article does not describe the combination of Glasgow 15 with motor deficit; the interface retains grade I and displays this caveat, without presenting it as a validated combination. This is the original edition, not a later modified WFNS, and it does not provide an automatic individual prognosis.

## References

- [Teasdale GM et al. A universal subarachnoid hemorrhage scale: report of a committee of the World Federation of Neurosurgical Societies. J Neurol Neurosurg Psychiatry, 1988.](https://doi.org/10.1136/jnnp.51.11.1457)

- [WFNS1988,original JNNPletter,p1457](https://cdn.ncbi.nlm.nih.gov/pmc/blobs/2309/1032822/5084dd0d5156/jnnpsyc00546-0085.png)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
