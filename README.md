# QtDraw チュートリアル

## 執筆ガイドライン

* Markdownのセルで、数式の記述には`$$`, `$$ $$` 環境を用いる。
* 文献は、ノートブックの末尾のmarkdownセルに、リストで掲載。
* 文献は`references.bib`に追加可。
* Jupyter notebookの全ての出力は除く。

## GitHub Pagesの環境設定

```bash
pip3 install jupyter-book ghp-import jupytext
```
## 記事の更新　(ローカルのmainブランチで)
- src内に記事ファイルを作成。
- _toc.ymlを適切に更新。
- GitHubの更新 (gh-pagesへcommit, push)
```bash
make upload
```

## トラブル・シューティング
* https://github.com/executablebooks/jupyter-book/issues/1541
