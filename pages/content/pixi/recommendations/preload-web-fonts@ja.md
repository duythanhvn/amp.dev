---
$title: ウェブフォントのプリロード
$order: 140
tags:
- lcp
---

プリロードを行うことで、重要なリソースをできるだけ早期に読み込むようにブラウザに指示することができます。HTML 内で検出される前でもです！この機能は、最初のビューポートとページ全体で使用されるフォントなどのリソースにおいて特に有用です。こういったリソースには、以下のコードのように `rel="preload"` 属性を追加することで、プリロードが可能となります。

```
<link href="font.woff2" rel="preload">
```
