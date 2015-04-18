## systemrequirement
#### クライアント側
##### 送信
1. 疑似カメラ（治具）作成
2. FlashAir：送信ロジック試作

##### 受信
1. FlashAir、受信側ロジック試作
2. 受信確認用治具作成

#### サーバ側
※cidがカードのユニークID、groupidがカードのグループID想定です。何も考えず固定で付けてください。  
// ファイル一覧検索  
http://flashpair.azurewebsites.net/filelist.json?cid=11111  

// ファイルダウンロード 
http://flashpair.azurewebsites.net/filedownload.json?cid=11111&fileid=xx  
※xxに1はファイル一覧検索結果のidを設定してください。  

// ファイルアップロード  
http://flashpair.azurewebsites.net/fileupload.json?cid=11111  
上記にname="upfile"でファイルをPOSTする。  

---
## role
- 一階さん：サーバ周り
- shigehiroさん：送信ロジック、送信治具
- 林さん：受信治具／受信ロジック
- 江頭：プレゼン周り／受信ロジック


