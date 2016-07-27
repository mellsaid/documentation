# テキストメッセージ

Mautic 1.4.0では新しいチャネルが追加されました。これにより、MauticによりキャンペーンからSMSが送信できるようになります。

## テキストメッセージの設定

MauticからSMSを送信する前に、SMSを送信できるサービスと接続する必要があります。最初のそしてデフォルトの実装サービスは[Twilio](https://www.twilio.com)です。このテキストメッセージを正しく設定するには次のステップに従ってください:

1. Twilio.comのアカウントを作成します。
2. *アカウント設定*を開きます。ここに*API認証情報*があります
3. ブラウザの別のタブでMautic設定画面を開き、歯車アイコン > 設定 > テキストメッセージ設定を開きます。
4. Twilioアカウントから*AccountSID*をコピーして*テキストメッセージプロバイダーユーザー名*にペーストします。
5. *AuthToken*をアンロックしてコピーし、*テキストメッセージプロバイダーパスワード*にペーストします。
6. Twilioの*Products* > *Phone Numbers*を開きます。このナンバーをMauticの*送信する電話番号*にペーストします。
7. *テキストメッセージを有効化しますか?*スイッチを*Yes*にしてMautic設定を保存します。

## 新しいテキストメッセージの作成

テキストメッセージはキャンペーンビルダー経由でのみ作成/編集が可能です。

1. *キャンペーン*を開きます。
2. 既存のキャンペーンを編集するか新たに作成します。
3. キャンペーンビルダーを開きます。
4. *テキストメッセージ送信*アクションをドラッグしてキャンバスにドロップします。5. *新規テキストメッセージ*ボタンをクリックします。新しいブラウザウィンドウにフォームが表示されます。
6. *内部名*、*テキストメッセージ*を入力し、必要に応じて言語を変更して保存します。

新しいテキストメッセージがあらかじめ選択されるので、*テキストメッセージ送信*アクションを同様に保存することができます。