# 更新履歴

 - master/HEAD
   * jarファイルを含めない形のパッケージングに変更
   * E4Xが原因で最近のバージョンのFirefoxで動作しなくなっていたのを修正
 - 0.3.2010070401
   * Firefox 2.0.0.xへの対応を終了
   * Minefield 4.0b2preに対応
 - 0.3.2010062901
   * ロシア語ロケール更新（by L'Autour）
 - 0.3.2010032902
   * フレームから対応するtabbrowserを検索する処理が動作していなかった
 - 0.3.2010032901
   * Minefield 3.7a4preで、一度ページのソースを開くとそれ以後同じページのソースばかりが表示されてしまう問題を修正
 - 0.3.2010032801
   * Minefield 3.7a4pre以降では、外部エディタに渡すパスのエンコーディング変換機能を無効にするようにした
   * es-ESロケール追加（by Rivica）
 - 0.3.2010020301
   * ソースを表示する時、キャッシュの内容を使うようにした（毎回ページの内容を取得しに行ってしまっていたのを修正）
   * リンクがたくさんあるページのソース表示で固まる問題を修正
   * セッション復元時にツリー型タブのツリー構造が壊れる可能性があったのを修正
 - 0.3.2009090201
   * イタリア語ロケール更新 by Godai71
 - 0.3.2009070701
   * [http://例え.テスト/](http://xn--r8jz45g.xn--zckzah/)のようなIDNのページでソース表示が正しく機能していなかったのを修正
   * ハンガリー語ロケール更新 by Mikes Kaszmán István
 - 0.3.2009062301
   * タブでソースを表示する時に、ツールバーを表示しない設定の場合、2つめ以降のタブが全て最初にソースを開いたタブと同じ内容になってしまっていたのを修正
   * タブでソースを表示する時に、decodeURI()でデコードできないURIのページのソースが表示されない問題を修正
   * 外部アプリケーションでソースを表示する時に、アプリケーションに渡すファイルパスのエンコーディングを指定できるようにした（自動判別は諦めた）
   * イタリア語ロケール更新 by Godai71
 - 0.3.2009051101
   * タブでソースを表示する際、「ソースを表示」用のUIを表示しない設定を追加
 - 0.3.2009042901
   * 選択範囲のソース表示がShiretoko 3.5b5pre、Minefieldで正常に動作しなくなっていたのを修正
   * Firefox 3.5からの隠し設定であるview_source.editor.argsのための設定UIを追加
   * view_source.editor.argsに日本語などが含まれていた場合でも正しく動作するようにした
 - 0.3.2009032501
   * タブの中に読み込まれたソース表示用UIの外観を改善
   * タブの中に読み込まれたソース表示用UIで、Mac OS Xの「ウインドウ」メニューが残ったままになっていたのを修正
 - 0.3.2009021201
   * ロシア語ロケール追加（by L'Autour）
 - 0.3.2008120201
   * [Highlander](https://addons.mozilla.org/firefox/addon/4086)との競合を解消
 - 0.3.2008111401
   * メニュー項目の中クリックまたはCtrl-クリック（MacではCommand-クリック）で、設定を反転した動作を行うようにした
   * UIに表示されるURIを人間が読みやすい形式にするようにした
   * Minefield 3.1b2preでのソース内のリンクに対応（ページの移動に合わせてUIを更新、新しいタブを開く時にソース表示タブのUIを付けるなど）
   * タブを開き直せなくなっていたのを修正
   * Webページのフレーム内にview-source-tab:プロトコルを読み込もうとした場合はview-source:にリダイレクトするようにした
   * ハンガリー語ロケール追加 by Mikes Kaszmán István
 - 0.2.2008101501
   * Minefield 3.1b2pre対応
   * 選択範囲のソース表示に失敗することがある問題を修正
   * フレームのソースを開こうとすると常にトップレベルのフレームのソースが開かれていたのを修正
 - 0.2.2008061901
   * Firefox 2で動作しなくなっていたのを修正
 - 0.2.2008061601
   * Firefox 3で動作しない問題を修正
   * タブ中のステータスバーをFirefoxウィンドウ側に統合した
   * view-source-tab: URLで任意のページのソースを開けるようにした
 - 0.1.2008030901
   * Minefield 3.0b5preでの動作を確認
 - 0.1.2008022301
   * Firefox 3 beta3対応
   * ソース表示時に、ロケーションバー風にURIを表示するようにした
   * ページのタイトルを取得できなかった場合、URIを表示するようにした
 - 0.1.2007103001
   * 日本語ロケールで名前が間違っていたのを修正
 - 0.1.2007102501
   * 名前を「View Source in Tab（タブでソース表示）」から「Source Viewer Tab（ソース表示タブ）」に変更した（同名のアドオンがすでに存在したので）
   * 「編集」メニューを隠すようにした
 - 0.1.2007102402
   * Minefieldで動かない問題を修正
 - 0.1.2007102401
   * 公開