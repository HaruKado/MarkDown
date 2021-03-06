# MarkDown
基本的なマークダウン記法のまとめ　中に書いてあるリンクを片っ端から試してまとめただけ。
* 自分がまとめたものではない。　途中に貼ってあるリンクを参考に自分がまとめただけ。
* まだ探り探りなのであまり参考にしないでください。

# MarkDownの基本的な書き方

## 段落
空行を作る　1段落目→(空行)→2段落目
1段落目

2段落目

## 改行
行末に2つのスペースを入れる 　　ぶっちゃけ段落と改行の違ってなんだろ…？
　　　[](行頭にスペース2つ有り)
あいうえお　　※ひとつ前の行頭にスペース2つ有り
  　[](行頭にスペース2つ)
かきくけこ　　※ひとつ前の行頭にスペース2つ有り

さしすせそ　　※ひとつ前の行頭にスペースなし

## 強調
ちょっと太文字になる 　アスタリスク(*)またはアンダーバー(_)で囲う
*大事*   または　　_大事_  ※アスタリスクの後にスペースは付けちゃダメ！別物になっちゃう！
2つにするとさらに強調される
**大事**  または　　__大事__

## リスト
行頭にアスタリスク(*)か、番号ピリオド(1.)
* リスト１ ※1スペース開けるの忘れずに
* リスト2
  
1. リスト1　　※こっちちょっとよくわかんない。こーゆーもんなんかな？
2. リスト2

## 見出し
行頭の#の個数でH1～6を表す。
# H1見出し
## H2見出し
### H3見出し
#### H4見出し
##### H5見出し
###### H6見出し
#######　H7見出しｗ

または、イコール行を挿入　または　ハイフン行を挿入。
H1見出し  ※次の行にイコール行挿入
===============

H2見出し　※次の行にハイフン行を挿入
------------------------------

## 引用
メールの引用の感じ　>を最初にいれればいい。改行効かない
>あいうえお
かきくけこ

## リンク
* 自動リンク
アングルブラケット<>でURLを囲う
GithubFlavoredMarkdown  マークダウン記法まとめ
<http://codechord.com/2012/01/readme-markdown/>

* 通常のインライン記法
[リンクの名前](リンクのアドレス)  ※こっちはどこにもつながってない
[わかりやすいREADME.mdを書く](http://deeeet.com/writing/2014/07/31/readme/)

>Name  [](名前)
>====
>
>Overview [](概説)
>
>## Description [](説明)
>
>## Demo  [](デモ版)
>
>## VS. [](VS.)
>
>## Requirement  [](要件)
>
>## Usage [](使用方法)
>
>## Install  [](インストール)
>
>## Contribution  [](貢献)
>
>## Licence  [](ライセンス)
>
>[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)  [](参考アドレス)
>
>## Author  [](著者)
>
>[tcnksm](https://github.com/tcnksm)  [](参考アドレス)


## 画像
先頭にビックリマーク　　またはドロップする
![nsmhjv9](https://cloud.githubusercontent.com/assets/14175217/10359096/11544940-6dd0-11e5-846a-88a2eaf45344.jpg)

## 水平線
アスタリスクとかハイフンとスペースを交互とかにする
*****
- - - 

## コメントアウト
四角かっこ[]とまるかっこ()をつなげてまるかっこのなかにコメントを入れる
[](コメントアウト)

複数行コメントアウトしたい場合は改行直前に(\)をいれて改行する
[](あいうえお　　
かきくけこ
さしすせそ)  ※ここコメントアウトしてる

[](あいうえお\
かきくけこ)  ※ここコメントアウトしてる

複数行のときはHTMLのコメントアウトのやり方のほうが楽らしい。
「<!--」 コメント　「--->」
この場合は何にもしなくても改行してくれる

<!-- コメントアウト -->  ※ここコメントアウトしてる スペース開けるの忘れないようにする！
HTMLやってないからちょっちよくわからん。

# 注意
* 自分がまとめたものではない。　途中に貼ってあるリンクを参考に自分がまとめただけ。
* まだ探り探りなのであまり参考にしないでください。
* とにかくスペース開けなきゃのとこは気を付ける！全角じゃなくて半角！
* リポジトリのREADME.mdの変更の仕方がわからないから、とりあえずGistで書いて出来たらそれをコピペしてリポジトリにのせるようにする。
* GistはEdit？で変更できる
* リポジトリは一つのファイルにつきREADMEは一つずつっぽいからリポジトリをするときはファイル名を気を付ける！
* 頑張る。 2015/10/08
