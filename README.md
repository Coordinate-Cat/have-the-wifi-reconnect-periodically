# have-the-wifi-reconnect-periodically
perfect ver.

1. ローカルにwifire`.bat`と`.vbs`を同階層に突っ込む
2. タスクスケジューラーで、一回限りで基本タスク適当に組んでとりあえず作成(これは.bat)
3. 作成できたら作ったタスクのプロパティからトリガーを新規作成  
  3-1. 一回、5分間隔、無期限
4. 操作タブで.bat->.vbsの順番になっていることを確認する
5. 一度手動で実行しておく

[Old ver.] https://github.com/Coordinate-Cat/reWi-Fi-connect
(Archived)
