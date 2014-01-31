入金アドレス表示＆確認サンプル
================================

http://www.monacoin.com

Copyright (c) 2014      Monacoin Developers

なにこれ？
----------------

Monacoin で物を販売するときなどに、お客さん毎に入金先アドレスを作ってあげることで  
どの人から入金されたのかを特定・確認する手段を、可能な限りシンプルに実装したサンプルです。


ライセンス
-------

jsonRPCClient.phpのみGPLとなっております。  
(Copyright 2007 Sergio Vaccaro)  
その他は好きにしてください。


実行方法
-------------------

１．PHPの動作するwebサーバーを建てます。  
２．サンプルのmonacoin.confに書かれた内容で、Monacoin-qtかmonacoindを実行します。  
３．sample.phpの  
　　$host = 'localhost';  
　　を各自の実行環境に合わせて変更してください。  
４．ブラウザからindex.htmlにアクセスしてください。  
５．任意のユーザー名を入れて、そのユーザー用の入金アドレスを取得したり、そのユーザーの入金履歴が確認できます。  


Windows上でMonacoin-qt.exeとXAMPPで動作確認しました。  
Windowsからgitにコミットしたので、パーミッションとかはお察し。  
急ごしらえなのでおかしいところがあったら教えてください。  
リクエストはGETじゃなくてPOSTにすべきです。
