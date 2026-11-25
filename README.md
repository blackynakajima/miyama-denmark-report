# 美山 × デンマーク 教育調査（Web版）

「子どもたちの未来と持続可能な学校づくりをともに考える」
日本（京都府南丹市美山町）・デンマーク（グリブスコウ市）教育環境比較調査のWebサイトです。

発行：NPO法人 森の教育プロジェクト　／　調査・執筆：古北咲恵莉・加地優咲希　／　発行日：2026年10月20日

## ファイル構成

| ファイル | 内容 |
|---|---|
| `index.html` | サイト本体・日本語版（1ファイル完結。データ・CSS・JSをすべて含む） |
| `en/index.html` | 英語版（English edition）。写真は親フォルダの画像を共有 |
| `group.jpg` | 「はじめに」ページ上部の集合写真（日本語版・英語版で共用） |
| `furukita.jpg` / `kaji.jpg` | 「はじめに」ページの執筆者写真（日本語版・英語版で共用） |
| `.nojekyll` | GitHub Pages で Jekyll 処理を無効にするための空ファイル |

フォントは Google Fonts（Zen Maru Gothic / Zen Kaku Gothic New / Outfit）を読み込みます。ビルド作業は不要です。

## GitHub Pages での公開手順

1. GitHub で新しいリポジトリを作成（例：`miyama-denmark-report`、Public）
2. このフォルダの中身（`index.html`・`en`フォルダ・画像3点・`.nojekyll`・`README.md`）をリポジトリ直下にアップロード
   - ブラウザの場合：リポジトリの「Add file → Upload files」にドラッグ＆ドロップ
   - `.nojekyll` は隠しファイルのため、表示されない場合はなくても動作します
3. 「Settings → Pages」で Source を「Deploy from a branch」、Branch を `main` ／ `/(root)` にして Save
4. 数分後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます
   - 英語版は `https://<ユーザー名>.github.io/<リポジトリ名>/en/`（ヘッダーの「English／日本語」で相互に切り替え可能。表示中のページを保ったまま移動します）

独自ドメイン（例：edu-project.jp のサブドメイン）を使う場合は、Settings → Pages の「Custom domain」で設定してください。

## ページの構成（URL の # で切り替え）

- `#top` 概要（入口）
- `#yutori` `#chikara` `#taiwa` `#chiiki` `#ko` 5つのテーマ
- `#report`、`#ch1`〜`#ch7` 本編
- `#data` 付録A 集計データ ／ `#voices` 付録B 自由記述 ／ `#interview` 付録C インタビュー ／ `#glossary` 付録D 用語解説 ／ `#about` はじめに

## 公開前の確認事項

- 自由記述（付録B）は全文掲載です。個人が特定される記述がないか最終確認してください。
- デンマークの回答の日本語は調査者による「仮訳」です。
- 英語版の本文・テーマ・美山町の自由記述は日本語版からの翻訳です（デンマーク側の回答とインタビューは英語原文）。
- 本文中の数値は付録Aの集計に合わせて修正済みです（印刷版PDFの本編とは一部異なります）。
