#特別課題  
・URLとは何かについて調べましょう  
Webサイト１つ１つに与えられる住所のようなもの  

・クエリ文字列とは何かについて調べましょう  
URLに含まれるページに渡すパラメータの一部  


・パスパラメーター（パス変数）とは何か  
？や＝で表されている文字列で一意のページを示すもの  

  ・クエリ文字列との違いについて  
特定のwebページを表示するために必要な情報、省略可能かどうか  

・HTTPメソッドとは何か  

GET/POST/PUT/PATCH/DELETEそれぞれの意味を調べましょう  
GET・・・ページの取得    
POST・・・データの送信  
HEAD・・・ヘッダの情報を取得  
PUT・・・データの取得  
DELETE・・・データの削除  
・HTTPステータスコードとは何か  
HTTPレスポンスに含まれるWebサーバの処理結果を表す３桁の数字

下記のHTTPステータスコードの意味を調べましょう。

・2xx・・・通信が成功を示すコード
- 200
リクエスト成功
- 201
リクエスト成功、リソース作成が完了

・3xx・・・リダイレクト（転送）が行われたことを示す

・4xx・・・クライアント側でエラーが起きていることを示す
- 400
リクエストが無効
- 404
リソース・ページが存在しない

・5xx・・・サーバ側でエラーが起きていることを示す
- 500
サーバ内部エラー

・リクエストヘッダーとは何かについて調べてみてください  
HTTPリクエストの構成  
　↳リクエストライン・・・どこに何をするかが記述されている  
　↳リクエストヘッダ・・・データの補足情報が記述されている  
空行  
　↳メッセージボディ・・・データ本体  
HTTPレスポンスの構成  
　↳ステータスライン  
　↳レスポンスヘッダ  
空行  
　↳レスポンスボディ  

・リクエストボディとは何かについて調べてみてください  
リクエストのデータ本体  

・レスポンスヘッダーとは何かについて調べてみてください  
どこに何を返すのか記述されている箇所  

・レスポンスボディとは何か、JSONとは何か  
空行の下にあるデータ本体部分  

JSON（JavaScript Object Notification）・・・JavaScriptで値を取り扱うドキュメント規格  
書式  
{  
"key1": value,  
"key2": value,  
"key3": value  
}
