<!-- ELUCENIA technical documentation · escala-wfns · es · no clinical/professional/rights approval -->

# Escala WFNS

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/escala-wfns)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Escala de coma de Glasgow

`gcs`

puntos · intervalo: 3–15

### Déficit motor focal (hemiparesia, afasia)

`deficit`

- `0` — Ausente
- `1` — Presente

## Edición del método

WFNS/Teasdale 1988: GCS y déficit motor, 5 grados

## Fórmula documentada

I: Glasgow 15, sin déficit motor · II: 13 a 14, sin déficit · III: 13 a 14, con déficit · IV: 7 a 12, con/sin déficit · V: 3 a 6, con/sin déficit.

## Límites y población

La WFNS de 1988 combina Glasgow y déficit motor para graduar la hemorragia subaracnoidea; el grado cero de la fuente corresponde a un aneurisma no roto y es distinto de los cinco grados de hemorragia. Use una puntuación de Glasgow clínicamente evaluable y documente los factores que interfieran en el examen. El artículo no describe la combinación de Glasgow 15 con déficit motor; la interfaz mantiene el grado I y muestra esta salvedad, sin presentarla como una combinación validada. Esta es la edición original, no una WFNS modificada posterior, y no proporciona un pronóstico individual automático.

## Referencias

- [Teasdale GM et al. A universal subarachnoid hemorrhage scale: report of a committee of the World Federation of Neurosurgical Societies. J Neurol Neurosurg Psychiatry, 1988.](https://doi.org/10.1136/jnnp.51.11.1457)

- [WFNS1988,original JNNPletter,p1457](https://cdn.ncbi.nlm.nih.gov/pmc/blobs/2309/1032822/5084dd0d5156/jnnpsyc00546-0085.png)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

La información siguiente conserva las salidas del método para ejemplos sintéticos. No constituye una validación clínica independiente.

### 1

HSA de buen grado clínico (WFNS I a III)

| Detalles del resultado | |
| --- | --- |
| Glasgow | 15 |
| Déficit motor focal | ausente |


### 2

HSA de buen grado clínico (WFNS I a III)

| Detalles del resultado | |
| --- | --- |
| Glasgow | 13 |
| Déficit motor focal | ausente |


### 3

HSA de buen grado clínico (WFNS I a III)

| Detalles del resultado | |
| --- | --- |
| Glasgow | 14 |
| Déficit motor focal | presente |


### 4

HSA de mal grado clínico (WFNS IV y V)

| Detalles del resultado | |
| --- | --- |
| Glasgow | 7 |
| Déficit motor focal | ausente |


### 5

HSA de mal grado clínico (WFNS IV y V)

| Detalles del resultado | |
| --- | --- |
| Glasgow | 6 |
| Déficit motor focal | presente |

