# kameded.exe

![アプリ](https://i.gyazo.com/2a51f26841f3b2e612f728e9c12d5bd1.png)

## 機能

- 画面をOFFにします
- 画面がONになるまでの時間を計測します
- 結果をDiscordのWebhookで送信します

## 特徴

- 画面がOFFになるまで5秒待機します
- 画面がONになったあと、25秒経つと再度8秒カウント後画面がOFFになります
- Escを押すか、かめの画像をクリックするとDiscordに送信後終了します
- ✕ボタンやAlt+F4で終了すると記録されません

## セットアップ

Discord WebhookのURLをアプリの引数として渡すことで結果を記録することができるようになります

- ショートカットを作成します

- ショートカットのプロパティを表示します

- 以下のようにパスを`"`で囲い、スペースの後にDiscord WebhookのURLを`"`で囲ってペーストします

- ```
  "C:\～～～\kameded.exe" "https://discord.com/～～ WebhookのURL"
  ```

- 以上です