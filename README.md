## mpv 用 cli でシャッフル再生させるスクリプト

## How to use
0shuffle.sh ファイルをターミナルにドラッグ・アンド・ドロップして Enter を押して再生する。  
![how_to_use.png](https://github.com/matt-note/mpv-shuffle-cli/blob/master/how_to_use.png)  
カレントディレクトリ以下の音楽ファイルを再生する。  
カレントディレクトリ以下のディレクトリの中の音楽ファイルも再生する。  

```bash
$ chmod +x 0shuffle.sh
```
これを上記の方法でターミナルにドラッグ・アンド・ドロップして使う。  

mpv が入っていない場合はインストールする  
```bash
$ sudo apt install mpv
```

## 補足事項
* コマンドとしてではなく、ドラッグ・アンド・ドロップして使うようにした理由は、  
不要なターミナルの起動を減らすため。（不要なターミナルが邪魔になるため）  

* 0shuffle.sh という名前の理由は、  
ディレクトリで先頭に来やすく、見つけやすくするため。
