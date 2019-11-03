# unacast
掲示板のレスをYoutubeコメント風に表示したいという思想の元に開発されるツール

マニュアルは後で作ります・・・

使い方簡易説明(windows版)：

1. zip解凍したら中の「unacast.exe」を実行
2. 掲示板URLに読み込みたい板のURLを入力します（最後は"/"で終わるように）
3. 指定のレス番から表示したい場合は「開始レス番号」にレス番を入れます
4-1. サーバー起動ボタンを押します
4-2. ブラウザで「http://localhost:3000/」と入力してちゃんと表示されることを確認します
　　（この手順はちゃんと起動できているかの確認なので飛ばしてもOK）
5. OBSでブラウザソースを追加して各種項目を設定します（下記参照）
　・URL：http://localhost:3000/
　・幅：配信の解像度の1/4から1/3ぐらい（1280x720の配信なら300～400ぐらいをお好みで）
　・高さ：配信の解像度と同じ（1280x720の配信ならそのまま720）
　・FPS：30のままでOK
　・カスタムCSS：デフォで入っているものは消しておく。好みで記述しても良い
　　　　　　　　　（esources/app/public/css/style-server.css の記載を参考にいじってみてね！！）
         
多分これで表示できるはず。
終了するときは停止ボタン押してから終了しても、停止せずにアプリ直接落としても大丈夫。
あとアンインストールもフォルダごと削除でOK

動かないとかあったらIssuesかもしくは Twitter で @yudeunagi まで

あとmac版はmacないので動作確認できてないです。
