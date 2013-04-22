_s（アンダースコアーズ）
===

このテーマは`_s`（`アンダースコアーズ`）からフォークされたスターター・テーマです。
<em>親テーマ用ではなく、</em>改変のベースとなるテーマとして作られています。
これをもとに変更を加えて、次世代のすばらしい WordPress テーマを作るためのコードの参考にしてください。
オリジナルは http://underscores.me/ にあります。
ライセンスはオリジナルと同じ、GPL v2です。

詳しい説明はオリジナル https://github.com/Automattic/_s をご覧ください。

オリジナルと異なる点
---------------
* 日本語翻訳ファイル付き
* <code>&lt;head&gt;</code>タグ内に<code>&lt;meta http-equiv="X-UA-Compatible" content="IE=Edge"&gt;</code> を追記。

始め方
---------------

簡単に始めるなら、http://underscores.me のジェネレーターで `_s` ベースのテーマを作ることができます。
作りたいテーマの名前を入力し、"Generate"をクリックすると、あなた用のスターターテーマを取得できます。

マニュアルで作りたいなら、githubから `_s` をダウンロードしてください。
最初に `_s` ディレクトリーをコピーし、オリジナルの名前 - 例えば `megatherium` に変更してください。
次の順番でテンプレートファイル内のテキストの検索と置換を行ってください。

1. テキストドメインから `'_s'` (シングルクォーテーションを含む) を検索、オリジナルの名前に置換。
2. 全ての関数（function）名から `_s_` を検索、オリジナルの名前に置換。
3. コメントブロックから ` _s` (先頭に半角スペースを含む) を検索、オリジナルの名前に置換。
4. 接頭辞から `_s-` を検索、オリジナルの名前に置換。

あるいは

1. `'_s'` を `'megatherium'` に置換
2. `_s_` を `megatherium_` に置換
3. <code>&nbsp;_s</code> を <code>&nbsp;Megatherium</code> に置換
4. `_s-` を `megatherium-` に置換

その後、style.css 内にスタイルシート・ヘッダーの情報（テーマ名や作者名など）と、footer.php内のリンクを変更します。次に、カスタマイズしたり、このReadmeを削除します。

これで準備は整いました。
次のステップでは、言うことは簡単ですが、やるのが難しいです：素晴らしいWordPressのテーマを作る。 :)

Good luck!
