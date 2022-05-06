# NOTE-app

[https://mynote-first.herokuapp.com](https://mynote-first.herokuapp.com)

独学エンジニアで作った。演習用の課題なのでURLだけ。

リストは定期的に初期化される。散らかしっぱなしでも大丈夫。

## 使ったもの

* VSCode
* Docker（localでcontainer使った。DockerfileごとHerokuにデプロイした。）
* PHP
 * composer
 * [phpdotenv](https://github.com/vlucas/phpdotenv.git)（localで環境変数使うため。最後は使っていない。）
* [scssphp](https://scssphp.github.io/scssphp/)
* HTML
* CSS
* Bootstrap
* Heroku

## 主な機能（できること）
* 登録
* 登録した内容の変更/削除
* 絞り込み検索

## 見えないところでやっていること
* 環境変数を使うことで、ソースコードを直接覗き見てデータベースへ侵入することを対策
* XSS対策
* バリデーション
  * 空欄を許すところと許さないところがある
  * かなり緩い

## プチ機能（本来必要なかったり、もっといいやり方があったりする）
* ダミーを登録できる（絞り込みを試すときなどに便利に使って欲しい）
* テーマの切り替え（わざわざHTMLとCSSとPHPだけでやることではない）
* 全削除

## あった方が良さそう
* ~~全削除（プチ機能として）~~
