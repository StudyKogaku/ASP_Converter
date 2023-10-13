# ASP Converter
Auto Screencapture and PDF Converter の略称．  
電子書籍や資料などを自動で一枚ずつスクリーンショットを撮り，PDF化，PDF圧縮を行うプログラム．  
使用言語: Python

## 利用上注意(2023年10月時点) ##
著作権法第30条で  
・Kindleなど合法サイトで電子書籍を私的利用の範囲で複製  
・家族や友人などとの共有  
は認められていますが，他者の著作物を上記以外の他人に譲渡することは違法です．  
ご注意ください．

## 使用環境
WindowsとMacで動作確認済み．Linuxは未確認．

## 使用するソフトウェア
- ターミナル（Text Editorと併用を推奨，例：VS Code）
- [GhostScript](https://www.ghostscript.com/)
インストール方法は[公式ドキュメント](https://ghostscript.readthedocs.io/en/latest/Install.html)を参照．  
Windowsの場合は```gswin64c```を用いる．

## インストールが必要なモジュール
pynput, pillow, pyautogui, natsort, opencv-python, img2pdfx

## 使い方
1. 必要な入力値を入力する．
2. ASP_Converterを実行する
3. ターミナルに表示された指示に従う．
