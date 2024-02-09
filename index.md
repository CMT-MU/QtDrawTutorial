# QtDraw チュートリアル

## はじめに

3D描画ツール[QtDraw](https://github.com/CMT-MU/QtDraw)の使用法に関するチュートリアルです。
描きたい項目や求めたい情報を具体的に掲げて、それに答える形で操作方法を例示しています。

``MultiPie``ボタンをクリックすることで表示される対称操作パネルを用いると、対称操作を利用した様々な描画を行うことができます。
対称操作には[MultiPie](https://github.com/CMT-MU/MultiPie)ライブラリを使用しています。

MultiPieのチュートリアルは、[こちら](https://cmt-mu.github.io/MultiPieTutorial/)。

## 引用に関して

科学研究でQtDrawやMultiPieを用いた場合には、我々の仕事{cite}`PhysRevB.107.195118`を引用していただければ幸いです。

## その他の事項

### 執筆ガイドライン

* Markdownのセルで、数式の記述には`$$`, `$$ $$` 環境を用いる。
* 文献は、ノートブックの末尾のmarkdownセルに、リストで掲載。
* 文献は`references.bib`に追加可。

### GitHub Pagesの環境設定

```bash
pip3 install jupyter-book ghp-import jupytext
```
## 内容の更新
- ローカルのmainブランチで行う。
- src内に記事ファイルを作成。
- _toc.ymlを適切に更新。
- GitHubの更新 (gh-pagesへcommit, push)
```bash
make upload
```

### トラブル・シューティング
* https://github.com/executablebooks/jupyter-book/issues/1541


## 参考文献

```{bibliography}
```
