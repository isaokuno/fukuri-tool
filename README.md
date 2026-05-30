# 複利の学習ツール（fukuri-tool）

元金・金利・年数を入力すると、複利でお金がどう増えるか（借金がどう膨らむか）をグラフで確認できる学習用Webアプリ。

- AI活用ロードマップ **402-B易** に対応
- 機密データは扱わない（すべてブラウザ内で計算が完結）
- ホスティング: GitHub Pages（無料・`docs/` フォルダを公開）

## 構成
- `docs/index.html` … アプリ本体（HTML/CSS/JS の1ファイル。グラフは Chart.js を利用）

## ローカルで開く
`docs/index.html` をブラウザで開くだけ。

## 公開
GitHub Pages（Settings → Pages → Source: `main` / `/docs`）。
`main` ブランチへ push すると自動で再公開される。
URL: https://isaokuno.github.io/fukuri-tool/

作成: 久野金属工業 / Claude Code 練習プロジェクト
