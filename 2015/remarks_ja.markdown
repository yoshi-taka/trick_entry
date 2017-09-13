###解説
標準出力にremarks.markdownの内容を出力します。ws.rbを含めて4067バイトです。

###実行方法

    ruby -r./ws entry.rb
    
RubyとWhitespaceのバイリンガルの方は、下記の方法でも大丈夫です。

    wspace entry.rb
    
###推奨環境
Ruby 2.xで確認しています。1.9ならmagic commentをつければ多分動きます。

###構造
ASCIIからUnicodeまで、空白記号のみんなが集まってくれました！BWT(Blank-White Transform)とRLE(Right-to-Left Embedding)を利用しています。