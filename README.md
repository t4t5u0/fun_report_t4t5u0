# lualatexTemplate
funpro.sty のlualatex版です。フォークしたり、submodule add してつかてください

## usage
`latexmk` でPDFが`/output`に作られます。

## GitHubとの連携
- タグをつけてプッシュすると、PDFが生成されます


## bibtexの使い方
- [BibTeX entry from URL - Chrome ウェブストア](https://chrome.google.com/webstore/detail/bibtex-entry-from-url/mgpmgkhhbjgkpnanlmlhibjfgpdpgjec?hl=ja)を追加します
- 参考文献にしたいページに飛んで、このアドオンを起動します
- `reference.bib` に貼り付けます
- 引用するときは、`\cite{tag_name}` です