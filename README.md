NES-Dual-Words-Map
==================

This repository puts NES sprites for NES programmer. Dual Words is a sprite map including 2 words in each sprite. The functions are enabled by utilizing 2 plattes in each sprite.

NES用の1つのスプライトにつき2つのパレットを使って複数の文字列を入れた.chrファイルを配布しています．
英数記号ひらがなカタカナは全部でFF文字種あります．
これを1つのスプライトにつき，1つのパレットを使うのは容量の無駄なので，
1つのスプライトにつき，2つのパレットを利用することで容量を半分程度に抑えています．

## 技術的な概要
ファミコンはスプライトのドットを表現するのに2ビットの値が使われています．
この値がパレットの中でどの色を使うのか指定しています．