Markdown Outline

使い方
1. index.html をChromeまたはEdgeで開きます。
2. 「開く」でMarkdown（.md）を読み込みます。
3. 左のトピックを選択して右側で編集します。
4. ＋=同じ階層、子=子トピック、↑↓=移動、←→=階層変更、×=削除。
5. ドラッグ＆ドロップでも移動できます。
6. 「保存」でMarkdownとして保存します。

注意
- ドラッグ＆ドロップにはSortableJS 1.15.7をCDNから読み込みます。
- File System Access API対応ブラウザでは開いたファイルへ上書き保存できます。
- 非対応環境では通常のファイル選択・ダウンロードにフォールバックします。
- 完全オフライン利用には Sortable.min.js を同じフォルダに置き、index.html のCDN scriptを
  <script src="Sortable.min.js"></script>
  に変更してください。
