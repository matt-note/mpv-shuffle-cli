## cli で音楽ファイルをシャッフル再生させるスクリプト

## How to use
```bash
$ chmod +x 0shuffle.sh
```
0shuffle.sh ファイルをターミナルにドラッグ・アンド・ドロップして Enter を押して再生する。  
![how_to_use.png](https://github.com/matt-note/mpv-shuffle-cli/blob/master/how_to_use.png)  
これでカレントディレクトリ以下の音楽ファイルを再生する。  
カレントディレクトリ以下のディレクトリの中の音楽ファイルも再生する。  
そのため、0shuffle.sh ファイルは、再生したい音楽ファイルがあるディレクトリにコピーして配置させておく。  

mpv が入っていない場合はインストールする  
```bash
$ sudo apt install mpv
```

## 補足事項
* コマンドとしてではなく、ドラッグ・アンド・ドロップして使うようにした理由は、  
不要なターミナルの起動を減らすため。（不要なターミナルが邪魔になるため）  
Ctrl + Shift + T でタブを追加して、そこにドラッグ・アンド・ドロップするとスッキリと使える。  

* 0shuffle.sh という名前の理由は、  
ディレクトリで先頭に来やすく、見つけやすくするため。
