<!-- ELUCENIA technical documentation · escala-wfns · pt-BR · no clinical/professional/rights approval -->

# Escala WFNS

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/escala-wfns)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Escala de coma de Glasgow

`gcs`

pontos · intervalo: 3–15

### Déficit motor focal (hemiparesia, afasia)

`deficit`

- `0` — Ausente
- `1` — Presente

## Edição do método

WFNS/Teasdale 1988:GCS edéficitmotor,5 graus

## Fórmula documentada

Grau I: Glasgow 15, sem déficit motor · Grau II: Glasgow 13 a 14, sem déficit · Grau III: Glasgow 13 a 14, com déficit · Grau IV: Glasgow 7 a 12, com ou sem déficit · Grau V: Glasgow 3 a 6, com ou sem déficit.

## Limites e população

A WFNS de 1988 combina Glasgow e déficit motor para graduar hemorragia subaracnóidea; o grau zero da fonte corresponde a aneurisma não roto e é distinto dos cinco graus de hemorragia. Use Glasgow clinicamente avaliável e documente fatores que interfiram no exame. O artigo não descreve a combinação Glasgow 15 com déficit motor; a interface mantém grau I e exibe essa ressalva, sem apresentá-la como combinação validada. Esta é a edição original, não uma WFNS modificada posterior, e não fornece prognóstico individual automático.

## Referências

- [Teasdale GM et al. A universal subarachnoid hemorrhage scale: report of a committee of the World Federation of Neurosurgical Societies. J Neurol Neurosurg Psychiatry, 1988.](https://doi.org/10.1136/jnnp.51.11.1457)

- [WFNS1988,original JNNPletter,p1457](https://cdn.ncbi.nlm.nih.gov/pmc/blobs/2309/1032822/5084dd0d5156/jnnpsyc00546-0085.png)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
