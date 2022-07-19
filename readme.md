# CupCake Lite


## ファームウェアの書き込み

ファームウェアはQMKを使用して作成しています。

[トップ](https://github.com/nnaa0504/cupcake_liteV2) から複製のZIPファイルダウンロードを行います。

![img](https://imgur.com/ZONXZ9T.jpg)

ファイルを解凍し、中にあるcupcakeliteと名前の付いたフォルダをqmk_firmware/keyboards内に移動させます。


## キーマップ

デフォルトのキーの配置は次のようになっています（KEY3はロータリーエンコーダ）。

（Liteの場合はロータリーエンコーダのボタンがありません。）

![img](https://imgur.com/w4HKdTP.jpg)


### DEFAULTレイヤー

 KEY1 : タップでミュート

 KEY2 : タップでスクリーンショット

 KEY3 : なし


## キーマップの変更

cupcakelite/keymaps/defaultを複製し、任意の名前を付けます。

フォルダ内のkeymap.cを編集することでキーマップの変更が可能です。

（キーコードは[QMKのリファレンス](https://docs.qmk.fm/#/keycodes)を参照）

その際書き込みのコマンドは次のようになります。

    make cupcakelite:フォルダ名:avrdude

QMKの書き込み関する詳しい内容は、[Helixのファームウェアガイド](https://github.com/MakotoKurauchi/helix/blob/master/Doc/firmware_jp.md)が参考になります。
