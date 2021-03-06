![](https://tama-san.com/icon/icon128_FontNameExtractor112.png)

# Font Name Extractor
フォントファイルからフォント名を抜き出すMac用デスクトップアプリ（ドロップレット）

## システム要件
* macOS 10.12以降
* ダウンロードして解凍した直後は、右クリックメニューの［開く］を選択して起動してください。

## 使い方
Font Name Extractorのアプリアイコンにフォントファイルをドラッグ＆ドロップします。

### 仕様
* nameテーブルからフォント名に関する箇所（name IDの1,2,4,6,16,17）のみ抜き出します。
* Unicodeエンコードされている文字をデコードして表示します。
* Mac用のlanguage IDの箇所は除外します。

## 更新履歴
* 1.1.2
	* アプリ名のスペルを間違えていたので直した…。
	* ついでにアイコンをブラッシュアップ。
* 1.1.1
	* 微細な修正。
* 1.1.0
	* ウインドウに保存ボタンを追加。
	* Mac用language IDの除外を改善。
* 1.0.0
	* 公開。
	
## 開発環境
Xojo 2020r1.1（2008r2でもビルドできるのを確認）

## ライセンス
 [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).