# test
JavaScriptが使用できるブラウザ（GoogleChrome）にて動作確認を行いました。
それぞれ、テキストボックスにパラメータを入力し、最後に監視ログファイルを読み込むと、処理が始まります。
出力は、

状態：xxxxxxx, アドレス:xxxxxxxx, 期間:YYYYMMDDhhmmss～YYYYMMDDhhmmss, 時間:xx秒

の形式でテキストボックス内に表示されます。
監視ログファイルの途中でタイムアウトし、最新まで応答がない場合には、期間がnoneになります。
