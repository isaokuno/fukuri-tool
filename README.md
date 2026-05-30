# 複利の学習ツール（fukuri-tool）

元金・金利・年数を入力すると、複利でお金がどう増えるか（借金がどう膨らむか）をグラフで確認できる学習用Webアプリ。

- AI活用ロードマップ **402-B易** に対応
- 機密データは扱わない（すべてブラウザ内で計算が完結）
- ホスティング: Firebase Hosting

## 構成
- `public/index.html` … アプリ本体（HTML/CSS/JS の1ファイル。グラフは Chart.js を利用）
- `firebase.json` … Firebase Hosting の設定

## ローカルで開く
`public/index.html` をブラウザで開くだけ。

## 公開
```
firebase deploy
```

作成: 久野金属工業 / Claude Code 練習プロジェクト
