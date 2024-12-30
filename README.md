# ビルド

```shell-session
latexmk thesis -pdfdvi
```

## GitHub Actionsで生成されたPDFの確認方法

GitHub Actionsが実行されると、`thesis.tex`から生成された`thesis.pdf`がアーティファクトとしてアップロードされます。以下の手順でPDFを確認できます。

1. GitHubリポジトリのページに移動します。
1. `Actions`タブをクリックします。
1. 実行された最新のワークフローを選択します。
1. `Artifacts`セクションから`PDF`をクリックしてダウンロードします。

# 執筆ファイル

- thesis.tex：タイトル・氏名はここに書く
- chapter/\*.tex：本文
- reference.bib：参考文献の bibtex
- figs/：図用だが入れても特別なことは何もない

# textlint

```shell-session
npm run lint
```
