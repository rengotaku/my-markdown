# 参考

* 画面構成
http://dillinger.io/
* 色使い
https://web.any.do/
* 色
http://www.colordic.org/
* アイコン(Bootstrap)
http://www.totec-bs.co.jp/blog/bootsrtap-icon/
* アイコン(Bootstrap)
http://www.totec-bs.co.jp/blog/bootsrtap-icon/
* ACEエディタ
https://ace.c9.io/

# マークの意味
* □・・・未完了のタスク
* ■・・・完了済のタスク
* →・・・補足
* ＊・・・注釈
* ⇒・・・結論

# テンプレ
```
タイトル１
□１
　□１－１
　　■１－１ー１
　　　※注釈１－１ー１－１
　　□１－１


タイトル２
■２
　■２ー１
　　→補足２－１－１
　　　※注釈２－１－１－１
　　　※注釈２－１－１－２
　■２－２改行テスト１２３４５６７８９０１２３４５６７８９０１２３４５６７８９０１２３４５６７８９０１２３４５６７８９０１２３４５６７８９０
　　⇒結論１

タイトル３
■３
　→補足３－１
　　※注釈３－１－１
□３.2
　→補足３.2－１
```

# WANT
* 他の要素への移動(タグ機能)
```
  □[test]タスク１
   ■タスク１－１
  □タスク２
   ■タスク２－１テストに遷移したい ＃test

```
# TODO

●タスクマーク
・変数を入力すると置換してくれる機能を入れたい。

正規表現
{{\s*[a-z_-]+[1-9]*\s*}}

パターン
---不正な形式---
{{}}
{{$}}
{{dev$}}
{{$あ}}
---正しい形式---
{{dev}}
{{dev_}}
{{_dev}}
{{dev1}}
{{ dev}}
{{dev }}
{{ dev }}

# POINT OUT
* TODO記号が□■だと「しかく」と打って変換するので入力に時間がかかる
　→＋、－で表現する？
　　→スペースを入力して＋、－を打つと半角になったりならなかったりする

# DONE
* 要素に折り畳み機能

* 記号なしの場合は強制的にタイトルになっているが、段落がついてるものは通常の文字が出力されるようにする。

* タスク済の要素以下はたためるようにする。
　⇒未or済タスクの以下が補足、注釈の場合

* マークを全部青にするとちかちかする。
　⇒基本黒で、済は色を変える。

* 結論のマークはなんか違う
　⇒以下が打倒
　　・glyphicon-thumbs-up（こっちがしっくりくる）
　　・glyphicon-flag

* URLをアンカーにする（別タブで開く）
