![](https://tama-san.com/icon/icon128_FontNameExtracter.png)

# Font-Name-Extracter
フォントファイルからフォント名を抜き出すMac用デスクトップアプリ（ドロップレット）

## システム要件
* macOS 10.12以降
* ダウンロードして解凍した直後は、右クリックメニューの［開く］を選択して起動してください。

## 使い方
Font Name Extracterのアプリアイコンにフォントファイルをドラッグ＆ドロップします。

### 仕様
* nameテーブルからフォント名に関する箇所（name IDの1,2,4,6,16,17）のみ抜き出します。
* Mac用のlanguageIdは除外します。
* Unicodeエンコードされている文字をデコードして表示します。

## 更新履歴
* 1.0.0
	* 公開。
	
## 開発環境
Xojo 2020r1.1（2008r2でもビルドできるのを確認）

## ライセンス
 [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).