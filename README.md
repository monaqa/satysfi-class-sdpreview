# SATySFi class SDpreview

## セットアップ方法

- SATySFi 処理系をインストール
- `src/sdpreview.satysfi-md` を `~/.satysfi/dist/md/sdpreview.satysfi-md` にコピー
- `src/class-sdpreview.satyh` を `~/.satysfi/dist/packages/class-sdpreview.satyh` にコピー
- 適当な Markdown 文書を書いて以下コードで PDF 生成

  ```bash
  satysfi satysfi --markdown sdpreview doc/example.md
  ```

## 参考

- [SATySFi インストール手引き 2021年5月版](https://qiita.com/na4zagin3/items/a6e025c17ef991a4c923)
- [SATySFiによるMarkdown文書からのPDF出力](https://github.com/gfngfn/SATySFi/wiki/SATySFi%E3%81%AB%E3%82%88%E3%82%8BMarkdown%E6%96%87%E6%9B%B8%E3%81%8B%E3%82%89%E3%81%AEPDF%E5%87%BA%E5%8A%9B)
