# businesscard
Google Drive上で名刺管理を行うためのプログラムです。
大学の研究室にあった、大量の名刺を電子化して整理するために作成しました。

## 使用方法
1. Scansnap等で名刺をスキャンし出力したPDFを'input_files'というフォルダにアップロードする。
2. ipynbファイルを実行すると、名刺の情報をスプレッドシート'personal_info.gsheet'に保存、名刺の画像をフォルダ'card_images'に保存します。

## 実装
OCRとLLMを利用して名刺から名前やメールアドレスの情報を抽出しています。
- businesscard.ipynb
    こちらは
