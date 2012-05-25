### 概要

[[Twitter|http://twitter.com/]] のサイドメニューで[[ふぁぼったー|http://favotter.net/]]のふぁぼられを表示できるようにします

* 新UI対応（旧UI非対応）
* Side Favotter 2 では５分間隔で自動更新するようになっています
* タイトル部をクリックするとリスト部分が非表示になります（折り畳まれます）
* 非表示したときには自動更新されません
* 再度表示したときにはすぐに更新されます（ただし前回更新より30秒未満の場合は更新せず）
* ふぁぼったーは  [[@ono_matope|http://twitter.com/ono_matope]] さんによる Twitter で Favorite された発言を収集するサービスです
* JSONP の生成には  [[Yahoo!Pipes|http://pipes.yahoo.com/pipes/]] を使用しています

### 更新履歴

 [2011-08-05] 1.0.4

 * Y!Pipes の（たぶん）仕様変更のためタグがそのまま表示されてしまう問題を修正

 [2010-11-05] 1.0.3

 * Twitterの変更のためか自分以外のプロフィール表示でただしく表示されない問題を修正

 [2010-10-13] 1.0.2

 * 1.0.1の修正で赤ふぁぼ他がなくなってしまった問題を修正

 [2010-10-13] 1.0.1

 * 文字色を環境設定と同じものになるように修正
 * http: で Twitter にアクセスすると実行されない問題を修正（Safari Extensionのみ）

 [2010-10-12] 1.0

 * Twitterの新Web UIに対応

### Safari Extension

* [[ダウンロードページ|http://github.com/gnue/Side-Favotter-2/downloads]]よりダウンロードしてダブルクリックでSafari 5にインストール

### Safari 4/Firefox

* GreaseKit/Greasemonkeyが必要
* ソースから side_favotter2.user.js の raw を表示してインストール [ [[link|http://github.com/gnue/Side-Favotter-2/raw/master/Side%20Favotter%202.safariextension/side_favotter2.user.js]] ]
