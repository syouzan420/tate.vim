# tate.vim
virtical insert in vim

for VIM version 8.2 later

start virtical mode with 't' and Enter in normal mode  

end virtical mode with 'q' and Enter in normal mode  

write the virtical text to the buffer, press 'w' and Enter in normal mode  

in Nihongo from here  

縦書きを實現したプラグインです  
まだ改良すべき箇所は多いですが 一應動きます  
t に續いて Enter で 縦書きモードに移行し  
通常どおり iなどを押して 挿入モードで文字を挿入できます  
挿入中のEnterや BSも機能するはずです  
保存したい場合は ノーマルモードで wに續き Enterを押し 横書きモードに戻してから 通常通り保存します  
最新のVIMでないと charcol関数がないことによりエラーが出ます  
このプラグインを使ふ場合は VIMを最新にすることをお勧めします  
プラグインの使用は tate.vim を フォルダ .vim の plugin ディレクトリに入れてください  
