<!-- ELUCENIA technical documentation · escala-wfns · ja · no clinical/professional/rights approval -->

# WFNS分類

[条件・出典・許諾](https://elucenia.org/ja/tools/escala-wfns)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### グラスゴー昏睡尺度

`gcs`

点 · 範囲: 3–15

### 局所神経障害（不全片麻痺、失語）

`deficit`

- `0` — なし
- `1` — あり

## 方法の版

WFNS/Teasdale 1988：GCSと運動障害、5段階

## 記載された計算式

I：Glasgow15、運動障害なし、II：13～14・障害なし、III：13～14・障害あり、IV：7～12・障害有無を問わず、V：3～6・障害有無を問わず。

## 限界・対象集団

1988年WFNSはGlasgow昏睡尺度と運動障害を組み合わせてくも膜下出血を分類します。原資料の0級は未破裂動脈瘤であり、出血の五段階とは別です。臨床的に評価可能なGlasgow値を使用し、診察を妨げる因子を記録してください。論文はGlasgow 15と運動障害の組み合わせを記載していません。画面ではI級を維持してこの留保を表示し、検証済みの組み合わせとは示しません。これは原版であり、その後の修正版WFNSではなく、個人の予後を自動的に示すものでもありません。

## 参考文献

- [Teasdale GM et al. A universal subarachnoid hemorrhage scale: report of a committee of the World Federation of Neurosurgical Societies. J Neurol Neurosurg Psychiatry, 1988.](https://doi.org/10.1136/jnnp.51.11.1457)

- [WFNS1988,original JNNPletter,p1457](https://cdn.ncbi.nlm.nih.gov/pmc/blobs/2309/1032822/5084dd0d5156/jnnpsyc00546-0085.png)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
