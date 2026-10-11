# ネクロ・アルケミア

ブラウザで遊べるネクロマンサーのサバイバーライク。スマホ・PC 対応。日本語／英語（端末の言語で自動。タイトルの 🌐 で切り替え）。

A necromancer survivor-like you can play in your browser. Phone & PC. Japanese / English (follows your device language; switch with 🌐 on the title screen).

## 遊ぶ

GitHub Pages で公開したページを開くだけ（インストール不要）。

## GitHub Pages で公開する手順

1. GitHub で新しいリポジトリを作る（例：`necro-alchemia`。Public にする）
2. このフォルダの中身（`index.html`・`en` フォルダ・`ogp.png`・`ogp_en.png`・`.nojekyll`・`README.md`）をリポジトリの一番上に置く
   - ブラウザでやるなら「Add file → Upload files」でドラッグ＆ドロップ
   - `.nojekyll` は名前が「.」で始まるので、パソコンでは隠しファイルになっていることがある
3. リポジトリの「Settings → Pages」を開く
4. 「Build and deployment」の Source を「Deploy from a branch」、Branch を `main` ／ `/ (root)` にして Save
5. 1〜2分待つと `https://（ユーザー名）.github.io/necro-alchemia/` で遊べる

## 更新するとき

新しい版の `index.html` で上書きしてコミットするだけ。数分で反映される（すぐ変わらないときはブラウザで再読み込み）。

## メモ

- セーブデータはブラウザ（localStorage）に保存される。端末・ブラウザごとに別。
- この `index.html` は製品版（デバッグ機能を取り除いた版）。


## 日本語のページと英語のページ

- `https://toyogame.github.io/Necro-alchemia/` … 端末の言語で自動（日本語なら日本語、それ以外は英語）。サムネイルは日本語（`ogp.png`）
- `https://toyogame.github.io/Necro-alchemia/en/` … いつも英語。サムネイルは英語（`ogp_en.png`）
- どちらで遊んでも記録（セーブ）は同じ。タイトルの 🌐 で切り替えると、もう一方のページへ移る

## 共有したときのサムネイル

`ogp.png`（日本語）と `ogp_en.png`（英語）は X などで URL を貼ったときに出る画像です。`index.html` と同じ場所に置いてください（`en` フォルダの中には置かない）。
サムネイルの URL は `https://toyogame.github.io/Necro-alchemia/ogp.png` と `…/ogp_en.png` に決め打ちしています（公開先の URL を変えるときは tools/pages.py の SITE を直して作り直す）。
X はサムネイルを覚えておくため、更新が反映されるまで時間がかかることがあります。
