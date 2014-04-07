Japanese font settings for Project Zomboid
================

[Project Zomboid](http://projectzomboid.com/) の日本語フォント（アウトラインフォントを画像化したテクスチャアトラス）作成時の設定ファイルです。

作成に使ったもの
----------------

### ソフトウェア
- [BMFont (Bitmap Font Generator)](http://www.angelcode.com/products/bmfont/)

実際に使用した BMFont は v1.14 beta 2014/02/05。

### フォント
- [M+ OUTLINE FONTS](http://mplus-fonts.sourceforge.jp/mplus-outline-fonts/index.html)
- [PixelMplus](http://itouhiro.hatenablog.com/entry/20130602/font)

大フォントと中フォントには mplus-1m-regular.ttf （[M+ TESTFLIGHT 058, 2014年2月26日版](http://mplus-fonts.sourceforge.jp/cgi-bin/blosxom.cgi/mplus_fonts/mplus_fonts-140226-2.html)）を使用し、小フォントには PixelMplus12-Regular.ttf を使った。これらのフォントは[フリーソフトウェア](http://ja.wikipedia.org/wiki/%E3%83%95%E3%83%AA%E3%83%BC%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2)で、ゲームに使ってもライセンス上の問題はない。

フォントを作成した時の手順
----------------

Project Zomboid フォルダ内 media/fonts/ に、ゲームに使われているラテン文字フォントの作成に使用した設定ファイルがある（zomboidLarge.bmfc、zomboidMedium.bmfc、zomboidSmall.bmfc）。これらの設定ファイルを流用して、日本語フォントは作成された。小フォントにビットマップフォントを使用したため、小フォントの設定のみフォントスムージングを解除している。

ラスタライズするフォントの選択には、同梱のテキストファイルを用いた。

使用したフォントをシステムにインストールした後に、zomboid(フォントサイズ)Japanese.bmfc を読み込んで出力するとフォントができます。

注意
----------------

フォントのライセンスによっては、画像化したものをゲームに使用できず、配布もできない。注意が必要。参照： [ゲームに使えるフォント - game-develop.com wiki](http://wiki.game-develop.com/index.php?%A5%B2%A1%BC%A5%E0%A4%CB%BB%C8%A4%A8%A4%EB%A5%D5%A5%A9%A5%F3%A5%C8)
