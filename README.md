# TeXonVSCode
VSCodeでLaTeXを使う方法まとめ。

1. VSCodeのextension `LaTeX Workshop` をインストール。
1. `settings.json`を適切に編集する。
  - `latex-workshop.latex.recipes` の一番最初のレシピがデフォルトで使われる。
  - レシピの順序を変えたときは、VSCodeを再起動しないとだめかも？
1. 英文のみの場合は `pdflatex`, 日本語の場合は `lualatex` を使う。
