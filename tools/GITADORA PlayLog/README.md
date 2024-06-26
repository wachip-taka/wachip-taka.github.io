# GITADORA PlayLog

## ダウンロードリンク
<[GITADORA PlayLog.zip](https://wachip-taka.github.io/tools/GITADORA%20PlayLog/GITADORA%20PlayLog.zip)>

## 概要
- コナステの画面を監視し、リザルトをリストに表示するツールです。  
- 楽曲情報、達成率や詳細リザルトを記録します。
- 設定は終了時に「GITADORA PlayLog.exe.config」に保存されます。

## 使い方
- フォルダを展開したら「GITADORA PlayLog.exe」を起動してください。
- 以下を参考に必要に応じて設定を変更したら通常通りコナステをプレイしてください。
- 不具合や要望があればご連絡ください。

## 機能説明
- **Clear**: リストをクリアします。
- **監視**: チェックがONの時、コナステを監視します。
- **監視間隔**: 画面を監視する間隔を設定します。あまり間隔が長いと記録が遅くなります。短すぎるとPCの負担が増加します。
- **閾値**: 画面遷移を判別する精度です。高すぎると反応しないし、低すぎると関係ない画面でキャプチャされます。基本デフォルトで、反応しない場合は少しずつ小さくしてみてください。
- **達成率更新のみ**: チェックをONにすると達成率を更新したレコードのみを絞り込みます。
- **SaveImage**: 現在表示されているリストを画像ファイルに保存します。
- **リザルトスクショを保存**: リザルトの原画をGITADORA PlayLog.exeの下のresultフォルダに自動保存します。

## 注意
- ツールの仕様は予告なく変更する可能性があります。
- リザルト画面でStartを連打していると記録されないことがあります。
- ウィンドウモードには現在対応していません。
- アプリを終了するとリストはクリアされます。

## お堅いこと
- 本ツールを使用した結果、ユーザーのPCに何らかの不具合が発生した場合でも開発者は一切の責任を負いません。  
- 本ツールの再配布はご遠慮ください。  
- 本ツールは非公式のツールです。ツールに関してKONAMIに問い合わせないでください。  

## 更新履歴
### 20240406
- リザルトの取得を少しだけ高速化
- 取得間隔制限を変更

### 20240303
- リザルトスクショの保存機能を追加

### 20240212_2
- リストのClear時にメモリが解放されない問題を修正
- 画面右端をドラッグしてウィンドウをリサイズできないことがある問題を修正

### 20240212_1
- Debug中の半端な資産を配置するという致命的なミスを修正

### 20240211
- Clearボタンを押した時に確認ダイアログを表示
- SaveImage機能を追加
- 達成率更新のみで絞り込んだ状態でスクロール時にエラーが発生することがあるバグを修正

### 20240210_2
- 画面端の描画をきれいにした
- 曲タイトルに表示されていた白い点に対応
- 達成率更新のみのオプションをフィルター方式に変更

### 20240210_1
- GITADORAを起動しているがウィンドウのキャプチャに失敗したケースに対応
- 監視を停止し、状態の確認を促すダイアログを表示

### 20240209
- メモリリークを修正
- GitHubに公開

### 20240208
- レイアウトを変更
- 途中終了したときに正しく動かなくなる問題を修正
- スクロールが機能しない問題を修正
- パフォーマンスを向上

### 20240206
- ウィンドウの移動/リサイズ中は処理を中断するよう変更
- 各種設定を保存するよう変更
- ウィンドウの変更サイズに制限を設定

### 20240205
- 粗削りだがとりあえず作った



