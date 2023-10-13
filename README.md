# ASP Converter
Auto Screencapture and PDF Converter．  

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 利用上注意(2023年10月時点) ##
著作権法第30条で  
・Kindleなど合法サイトで電子書籍を私的利用の範囲で複製  
・家族や友人などとの共有  
は認められていますが，他者の著作物を上記以外の他人に譲渡することは違法です．  
ご注意ください．

## 機能
- ページを移動させながら自動でスクリーンショットを撮る．
- スクリーンショットをPDF化する．
- 生成したPDFファイルを圧縮する

## 動作環境
WindowsとMacで動作確認済み．Linuxは未確認．

## 使用方法
### アプリ
- ターミナル（Text Editorと併用を推奨，例：[VS Code](https://code.visualstudio.com/)）
- [GhostScript](https://www.ghostscript.com/)
インストール方法は[公式ドキュメント](https://ghostscript.readthedocs.io/en/latest/Install.html)を参照．  
Windowsの場合は```gswin64c```を用いる．
- 使用言語：[Python](https://www.python.org/)

### ガイド
1. 必要な入力値を入力する．
2. ASP_Converterを実行する
3. ターミナルに表示された指示に従う．

## モジュール
pynput, pillow, pyautogui, natsort, opencv-python, img2pdfx

## Lisence
ASP_Converter is  open-sourced software licensed under the [MIT license](https://opensource.org/license/mit/)
Copyright &copy; 2023 StudyKogaku