# NOTE-app

[URL](https://mynote-first.herokuapp.com)

独学エンジニアで作った。

定期的に初期化されます。散らかしっぱなしでも大丈夫。

## 使ったもの

* VSCode
* Docker
* PHP
 * composer
 * [phpdotenv](https://github.com/vlucas/phpdotenv.git)
* [scssphp](https://scssphp.github.io/scssphp/)
* HTML
* CSS
* bootstrap
* Heroku

## 主な機能（できること）
* 登録
* 登録した内容の変更/削除
* 絞り込み検索

## 見えないところでやっていること
* XSS対策
* バリデーション
  * 空欄を許すところと許さないところがある
  * かなり緩い

## プチ機能
* ダミーを登録できる（絞り込みを試すときなどに便利に使って欲しい）
* テーマの切り替え（わざわざHTMLとCSSとPHPだけでやることではない）

## あった方が良さそう
* 全削除
