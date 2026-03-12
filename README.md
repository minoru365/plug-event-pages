# PLUG イベント導入ページ

PLUGイベント向けの導入ページ一式です。

## ファイル構成

- index.html: 入口ページ
- plug_intro.html: コミュニティ紹介
- discord_audio_guide.html: Discord音声設定ガイド
- academy_recap_260313.html: Agent Academy おさらいページ

## 公開先

- GitHub リポジトリ: https://github.com/minoru365/plug-event-pages
- GitHub Pages: https://minoru365.github.io/plug-event-pages/

## 更新方法

このフォルダは DailyUseRepository 親リポジトリとは独立した Git リポジトリです。

```powershell
git status
git add .
git commit -m "PLUGページを更新"
git push
```

更新後は GitHub Pages の反映に少し時間がかかることがあります。

## 補足

- 画像は各HTMLに埋め込まれているため、単体ファイルのまま公開できます
- 親リポジトリ側では tasks/PLUG/ を .gitignore で除外しています
