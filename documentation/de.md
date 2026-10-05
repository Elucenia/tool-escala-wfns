<!-- ELUCENIA technical documentation · escala-wfns · de · no clinical/professional/rights approval -->

# WFNS-Skala

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escala-wfns)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Glasgow-Koma-Skala

`gcs`

Punkte · Bereich: 3–15

### Fokales motorisches Defizit (Hemiparese, Aphasie)

`deficit`

- `0` — Nicht vorhanden
- `1` — Vorhanden

## Fassung der Methode

WFNS/Teasdale 1988: GCS und motorisches Defizit, 5 Grade

## Dokumentierte Formel

I: Glasgow 15, kein motorisches Defizit · II: 13 bis 14, kein Defizit · III: 13 bis 14, mit Defizit · IV: 7 bis 12, mit/ohne Defizit · V: 3 bis 6, mit/ohne Defizit.

## Grenzen und Population

Die WFNS von 1988 kombiniert Glasgow und motorisches Defizit zur Graduierung einer Subarachnoidalblutung; Grad null in der Quelle entspricht einem nicht rupturierten Aneurysma und ist von den fünf Blutungsgraden zu unterscheiden. Verwenden Sie einen klinisch beurteilbaren Glasgow-Wert und dokumentieren Sie Faktoren, die die Untersuchung beeinträchtigen. Der Artikel beschreibt die Kombination von Glasgow 15 mit motorischem Defizit nicht; die Oberfläche behält Grad I bei und zeigt diesen Vorbehalt an, ohne sie als validierte Kombination darzustellen. Dies ist die Originaledition, keine spätere modifizierte WFNS, und sie liefert keine automatische individuelle Prognose.

## Referenzen

- [Teasdale GM et al. A universal subarachnoid hemorrhage scale: report of a committee of the World Federation of Neurosurgical Societies. J Neurol Neurosurg Psychiatry, 1988.](https://doi.org/10.1136/jnnp.51.11.1457)

- [WFNS1988,original JNNPletter,p1457](https://cdn.ncbi.nlm.nih.gov/pmc/blobs/2309/1032822/5084dd0d5156/jnnpsyc00546-0085.png)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
