# TeXonVSCode
VSCodeでLaTeXを使う方法まとめ。


## セットアップ
1. VSCodeのextension `LaTeX Workshop` をインストール。
1. `settings.json`を適切に編集する。
    - このディレクトリにある `settings.json` の中身を追記すればOK。
    - `latex-workshop.latex.recipes` の一番最初のレシピがデフォルトで使われる。
    - レシピの順序を変えたときは、VSCodeを再起動しないとだめかも？
1. 英文のみの場合は `pdflatex`, 日本語の場合は `lualatex` を使う。
1. `Ctrl`+`Alt`+`v`でプレビュー。
1. ときどき再起動しないと自動ビルドしないことがある。

## 英文のタイプセット
`pdflatex`で`sample_en.tex`をビルドする。

## 日本語のタイプセット
`lualatex`で`sample_jp.tex`をビルドする。
