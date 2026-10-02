# JARVIS Conversation Assist — Free Voice Prototype

無料で音声対話のレスポンス速度を確認するための試作版です。

- OpenAI APIなし
- 追加課金なし
- ブラウザの Speech Recognition で日本語音声を文字化
- Speech Synthesis でJARVISの返答を読み上げ
- 短い相づち + ルールベース返答
- 認識内容と応答時間を画面表示
- 連続対話（返答後に自動で聞き取り再開）

## GitHub Pages

Settings → Pages → Build and deployment で `Deploy from a branch` を選択し、
Branch を `main` / `/(root)` にすると公開できます。

この段階は生成AIではありません。目的は、まず音声認識の品質と返答開始の速さを確認することです。
