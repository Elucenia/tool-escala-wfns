<!-- ELUCENIA technical documentation · escala-wfns · zh · no clinical/professional/rights approval -->

# WFNS 分级

[条件、来源与许可](https://elucenia.org/zh/tools/escala-wfns)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 格拉斯哥昏迷评分

`gcs`

分 · 范围: 3–15

### 局灶性神经功能障碍（偏瘫、失语）

`deficit`

- `0` — 无
- `1` — 有

## 方法版本

WFNS/Teasdale 1988：GCS与运动缺损，5级

## 已记录的公式

I：格拉斯哥15，无运动缺损 · II：13至14，无缺损 · III：13至14，有缺损 · IV：7至12，可有或无缺损 · V：3至6，可有或无缺损。

## 限制与适用人群

1988年WFNS结合格拉斯哥昏迷评分和运动缺损对蛛网膜下腔出血分级；来源中的零级表示未破裂动脉瘤，区别于五个出血等级。请使用临床可评估的格拉斯哥评分，并记录干扰检查的因素。原文未描述格拉斯哥15分伴运动缺损的组合；界面保留I级并显示这一限制，不将该组合视为已验证情况。这是原始版本，不是后来的改良WFNS，也不自动提供个人预后。

## 参考文献

- [Teasdale GM et al. A universal subarachnoid hemorrhage scale: report of a committee of the World Federation of Neurosurgical Societies. J Neurol Neurosurg Psychiatry, 1988.](https://doi.org/10.1136/jnnp.51.11.1457)

- [WFNS1988,original JNNPletter,p1457](https://cdn.ncbi.nlm.nih.gov/pmc/blobs/2309/1032822/5084dd0d5156/jnnpsyc00546-0085.png)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
