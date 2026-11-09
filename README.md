# Hi, I’m Ryu Koda 👋

医学 × 機械学習に関心があります。Webの小さな実験や、手元で試せるコードを「りゅうのらぼ」で公開しています。

Interested in medicine × machine learning. I share web experiments and practical code on my personal website.

## まずはこちらから

- **[りゅうのらぼ](https://ryu-koda.com/)** — CSS・JavaScriptのデモ、Macの活用、ブログ制作の実践記録。
- **[Webの実験室](https://ryu-koda.com/playground/)** — ブラウザで動かして試せるデモ。
- **[サイトのソースコード](https://github.com/R-Koda/ryu-koda.com)** — Astroで制作した個人サイト。動かし方はREADMEにまとめています。

## Featured project — SplitTrace

**[SplitTrace](https://github.com/R-Koda/splittrace)** — EEG・センサーデータの機械学習向けに、既存のデータ分割を点検するPythonライブラリです。派生サンプルの元データをたどり、被験者や区間の混入を原因の経路とともに示します。情報不足は「検査不能」として扱います。

A provenance-aware Python toolkit for auditing EEG and sensor-data splits. Trace derived samples back to shared sources and inspect subject and interval overlap, with explicit coverage limits.

Experimental · MIT licensed · Synthetic examples and reproducible tests included.

[コード・使い方 / Repository & quickstart](https://github.com/R-Koda/splittrace#readme) · [PyPI](https://pypi.org/project/splittrace/) · [ステップ別ガイド / Tutorial](https://ryu-koda.com/blog/splittrace-data-leakage-check/)

## More developer tools

### [EventScore Explorer](https://github.com/R-Koda/eventscore-explorer)

時系列の正解・予測イベントを対応づけ、見逃し・誤検出・検出時刻のずれを可視化。許容時間を切り替え、スコアが変わる理由を確認できます。

Explain event-level evaluation with one-to-one matching, interactive tolerance comparisons, and local HTML reports.

[使い方 / Quickstart](https://github.com/R-Koda/eventscore-explorer#readme) · [PyPI](https://pypi.org/project/eventscore-explorer/) · [ステップ別ガイド / Tutorial](https://ryu-koda.com/blog/eventscore-explorer-event-evaluation/) · [Synthetic examples](https://github.com/R-Koda/eventscore-explorer/tree/main/examples)

### [Notebook Publish Check](https://github.com/R-Koda/notebook-publish-check)

Jupyter Notebookの公開前に、秘密情報らしい文字列・絶対パス・巨大な出力を点検。図を残しながら不要な出力を選んで除去し、元ファイルを変更せず別のコピーに保存できます。

Review notebooks without executing code. Inspect cell-level findings, keep useful figures, and export a separate copy with selected outputs removed.

[使い方 / Quickstart](https://github.com/R-Koda/notebook-publish-check#readme) · [PyPI](https://pypi.org/project/notebook-publish-check/) · [ステップ別ガイド / Tutorial](https://ryu-koda.com/blog/notebook-publish-check-guide/) · [Synthetic examples](https://github.com/R-Koda/notebook-publish-check/tree/main/examples)

Both tools are experimental, MIT licensed, and include synthetic demos and tests. Notebook checks are heuristic; local reports contain the original notebook and should be kept private.

## 関心のあること

- Medicine × machine learning
- Web development with hands-on examples
- 日々の作業を助ける小さなツールと自動化

---

[Website](https://ryu-koda.com/) · [Public repositories](https://github.com/R-Koda?tab=repositories&type=public)
