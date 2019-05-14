# BrainfuckIDE
## これはなに？
Breinf\*ckの統合開発環境を目指して作りました。  
主にデバッグ環境

## 何ができるの？
Brainf\*ckのコードをブレイクポイントで停止しながらデバッグできます。  
メモリの書き換えや　スニペットの実装も予定。  

## 現在の致命的バグ
---  

## 今後の予定(願望)
シンタックスハイライトを向上させたい。 (対応する[]の表示等)  
スニペット(もしくはそれに近いもの)を実装したい。   


## 更新履歴
### 2019/4/27
規定入力からの文字読み込みおよび、結果のテキストの出力を行うように修正。 
### 2019/4/28 
対応する[]がない場合にメッセージボックスを出すだけに修正。  
ブレイクポイントが付けれないバグの修正。  
メモリの現在位置の表示を追加。  
メモリ情報の書き換えを行えるよう変更。  
停止後にコードを書き換えた後に、その位置から実行を再開できるよう変更。   
### 2019/4/29
Ctrl+S, Ctrl+Shift+S によるファイルの保存が可能に。  
ドラッグ＆ドロップでファイル読み出し可能に。  
予約語のシンタックスハイライトが行われるように。  
### 2019/5/1
メインメニューを仮追加  
コードを単純化してクリップボードに張り付けるメニューを追加  
### 2019/5/14
ブレイクポイントの作成を右クリックではなく Ctrl+B または F9 で行うように変更   
右クリックメニューで文字を出力するコードを作成可能に  
また、上記のコード変換をCtrl+Rでできるように変更  


