<!-- ELUCENIA technical documentation · escala-wfns · fr · no clinical/professional/rights approval -->

# Échelle WFNS

[conditions, sources et autorisations](https://elucenia.org/fr/outils/escala-wfns)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Échelle de coma de Glasgow

`gcs`

points · intervalle: 3–15

### Déficit moteur focal (hémiparésie, aphasie)

`deficit`

- `0` — Absent
- `1` — Présent

## Édition de la méthode

WFNS/Teasdale 1988 : GCS et déficit moteur, 5 degrés

## Formule documentée

I : Glasgow 15, sans déficit moteur · II : 13 à 14, sans déficit · III : 13 à 14, avec déficit · IV : 7 à 12, avec/sans déficit · V : 3 à 6, avec/sans déficit.

## Limites et population

La WFNS de 1988 combine Glasgow et déficit moteur pour grader l’hémorragie sous-arachnoïdienne ; le grade zéro de la source correspond à un anévrisme non rompu et se distingue des cinq grades d’hémorragie. Utilisez un score de Glasgow évaluable cliniquement et documentez les facteurs qui perturbent l’examen. L’article ne décrit pas la combinaison Glasgow 15 avec déficit moteur ; l’interface conserve le grade I et affiche cette réserve, sans la présenter comme une combinaison validée. Il s’agit de l’édition originale, et non d’une WFNS modifiée ultérieure, et elle ne fournit pas de pronostic individuel automatique.

## Références

- [Teasdale GM et al. A universal subarachnoid hemorrhage scale: report of a committee of the World Federation of Neurosurgical Societies. J Neurol Neurosurg Psychiatry, 1988.](https://doi.org/10.1136/jnnp.51.11.1457)

- [WFNS1988,original JNNPletter,p1457](https://cdn.ncbi.nlm.nih.gov/pmc/blobs/2309/1032822/5084dd0d5156/jnnpsyc00546-0085.png)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

HSA de bon grade clinique (WFNS I à III)

| Détails du résultat | |
| --- | --- |
| Glasgow | 15 |
| Déficit moteur focal | absent |


### 2

HSA de bon grade clinique (WFNS I à III)

| Détails du résultat | |
| --- | --- |
| Glasgow | 13 |
| Déficit moteur focal | absent |


### 3

HSA de bon grade clinique (WFNS I à III)

| Détails du résultat | |
| --- | --- |
| Glasgow | 14 |
| Déficit moteur focal | présent |


### 4

HSA de mauvais grade clinique (WFNS IV et V)

| Détails du résultat | |
| --- | --- |
| Glasgow | 7 |
| Déficit moteur focal | absent |


### 5

HSA de mauvais grade clinique (WFNS IV et V)

| Détails du résultat | |
| --- | --- |
| Glasgow | 6 |
| Déficit moteur focal | présent |

