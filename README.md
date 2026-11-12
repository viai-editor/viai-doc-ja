# viai-doc-ja

[![Generate viai help](https://github.com/viai-editor/viai-doc-ja-working/actions/workflows/generate.yml/badge.svg)](https://github.com/viai-editor/viai-doc-ja-working/actions/workflows/generate.yml)

日本語に翻訳した ViAI 付属のヘルプを配布するためのプロジェクトです。

## 導入方法

[vim-plug](https://github.com/junegunn/vim-plug) を使う場合は、vimrc (または viairc) に以下の行を追加して `:PlugInstall` を実行してください。

最新の翻訳に更新するには `:PlugUpdate` を実行してください。

```vim
Plug 'viai-editor/viai-doc-ja'
```

vimrc を Vim と共有している場合は、以下のように処理を振り分けるといいでしょう。

```vim
if has('viai')
  Plug 'viai-editor/viai-doc-ja'
else
  Plug 'vim-jp/vimdoc-ja'
endif
```

日本語のヘルプが優先されない場合は、vimrc (または viairc) で `'helplang'` を設定してください。

```vim
set helplang=ja
```

英語のヘルプを見たいときは `:help usr_toc@en` のように `@en` を付けてください。

## Web ブラウザで読む

HTML 版は <https://viai-editor.github.io/viai-doc-ja/> から参照できます。

英語版は <https://viai-editor.github.io/viai-doc-en/> にあります。

## ライセンス

ViAI 付属のヘルプ (原文) と同じく、Open Publication License v1.0 以降の条件に従って配布できます。
詳しくは `:help manual-copyright` を参照してください。

## 間違いを見付けた場合

[issueトラッカー](https://github.com/viai-editor/viai-doc-ja-working/issues) でお知らせください。

---

[vim-jp/vimdoc-ja](https://github.com/vim-jp/vimdoc-ja) の翻訳を取り込んで始めたプロジェクトです。
