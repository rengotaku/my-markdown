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

# マークの意味
* □・・・未完了のタスク
* ■・・・完了済のタスク
* →・・・補足
* ＊・・・注釈
* ⇒・・・結論

# テンプレ
---
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
　■２－２
　　⇒結論１

タイトル３
■３
　→補足３－１
　　※注釈３－１－１
□３.2
　→補足３.2－１
---

# WANT
* タスク済の要素以下はたためるようにする。
　⇒未or済タスクの以下が補足、注釈の場合

* 他の要素への移動(タグ機能)
```
  □[test]タスク１
   ■タスク１－１
  □タスク２
   ■タスク２－１テストに遷移したい ＃test

```
* URLをアンカーにする（別タブで開く）


# POINT OUT
* マークを全部青にするとちかちかする。
　⇒基本黒で、済は色を変える。

* 結論のマークはなんか違う
　⇒以下が打倒
　　・glyphicon-thumbs-up（こっちがしっくりくる）
　　・glyphicon-flag