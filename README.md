# PLUG イベント導入ページ

PLUGイベント向けの導入ページ一式です。

## ファイル構成

- index.html: 入口ページ
- plug_intro.html: コミュニティ紹介
- discord_audio_guide.html: Discord音声設定ガイド
- academy_recap_260313.html: Agent Academy おさらいページ

## 公開先

- GitHub リポジトリ: <https://github.com/minoru365/plug-event-pages>
- GitHub Pages: <https://minoru365.github.io/plug-event-pages/>

## 更新方法

```powershell
git status
git add .
git commit -m "PLUGページを更新"
git push
```

更新後は GitHub Pages の反映に少し時間がかかることがあります。

## 共同編集ルール

- 変更は基本的にファイル単位で分けて行い、目的ごとにコミットを分けます
- 公開URLの導線を変える変更では、index.html のリンク切れ確認も合わせて行います
- 画像は各HTMLに埋め込まれているため、大きな差分になりやすい点に注意します
- 共同編集者は GitHub 上で issue または pull request の説明を残してから変更する運用を推奨します

## 共有テンプレート

以下の文面をそのまま案内に使えます。

```text
PLUGイベント向けの導入ページです。必要に応じて以下を参照してください。

- 入口ページ: https://minoru365.github.io/plug-event-pages/
- コミュニティ紹介: https://minoru365.github.io/plug-event-pages/plug_intro.html
- Discord音声設定ガイド: https://minoru365.github.io/plug-event-pages/discord_audio_guide.html
- Agent Academy おさらい: https://minoru365.github.io/plug-event-pages/academy_recap_260313.html
```
