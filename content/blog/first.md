+++
title = "たいとる-1-00001"
date = 2000-01-01T00:00:00+09:00
tags = ["test-image","markdown"]
+++

テスト投稿。

たいとる-1-00001のページ。

![イメージ 画像1](../../images/1920x1080.jpg)


## ドラフト

公開する
draft = false

下書き
draft = true

bash dummy-toml.sh

ここまで


## 見出し

# 見出し壱

## 見出し弐

### 見出し参

#### 見出し四

##### 見出し五

###### 見出し六



## 引用 (Blockquote) テスト

一行の引用。

> ハングリーであれ、愚かであれ。

`cite` 参照を含む複数行の引用。

> これは言語みたいなものだ。アルファベットすなわち音階を学び、文すなわちコードを学ぶ。そしてやがてホーンと即興で会話するようになる。即興で話すのはすばらしいことだと思うが、私には決して会得できないだろう。しかし音楽ともなれば、私は即座によろこんで会話する。そう、それがジャズ音楽のすべてだ。
> 
> <cite>スタン・ゲッツ</cite>



## テーブル

<table>
<tr>
<th>
社員
</th>

<th>
給料
</th>

<th>
</th>
</tr>

<tr>
<th>
<a href="http://example.org/" target="_blank" rel="nofollow noopener noreferrer">山田太郎</a>
</th>

<td>
1ドル
</td>

<td>
スティーブ・ジョブズが必要なサラリーと同じ額。
</td>
</tr>

<tr>
<th>
<a href="http://example.org/" target="_blank" rel="nofollow noopener noreferrer">田中花子</a>
</th>

<td>
1,000万円
</td>

<td>
ブログを書くために必要になる資金。
</td>
</tr>

<tr>
<th>
<a href="http://example.org/" target="_blank" rel="nofollow noopener noreferrer">山本次郎</a>
</th>

<td>
1億円
</td>

<td>
百聞は一見にしかず、ということで、カメラマンはブロガーの100倍。
</td>
</tr>

<tr>
<th>
<a href="http://example.org/" target="_blank" rel="nofollow noopener noreferrer">中山愛子</a>
</th>

<td>
10億円
</td>

<td>
特に理由は要りません。
</td>
</tr>
</table>



## 定義リスト

<dl>
<dt>定義リストタイトル</dt>
<dd>これは定義リストです。</dd>
<dt>定義</dt>
<dd>物事、領域、何かについての意味の正確な文章や説明: <em>詩を構成するものの定義。</em></dd>
<dt>ギャラリー</dt>
<dd>WordPress 2.5 から導入された、投稿に添付された画像を展示するための機能です。同じように、投稿を編集中にアップロードすると、そのファイルは「投稿に添付」されます。</dd>
<dt>Gravatar (グラバター)</dt>
<dd>グラバターとはグローバルに認識されるアバター (あるユーザーを表すグラフィックイメージや写真) です。グラバターはメールアドレスと紐づいていて、Gravatar.com サービスによって管理されています。このサービスを利用すると、ブログ所有者は自分のブログを設定することによりコメント欄にユーザーのグラバターを表示させることができます。</dd>
</dl>



## 非順序リスト (ネスト化)

  * リスト項目 1
      * リスト項目 1
          * リスト項目 1
          * リスト項目 2
          * リスト項目 3
          * リスト項目 4
      * リスト項目 2
      * リスト項目 3
      * リスト項目 4
  * リスト項目 2
  * リスト項目 3
  * リスト項目 4



## 順序リスト (ネスト化)

  1. リスト項目 1
      1. リスト項目 1
          1. リスト項目 1
          2. リスト項目 2
          3. リスト項目 3
          4. リスト項目 4
      2. リスト項目 2
      3. リスト項目 3
      4. リスト項目 4
  2. リスト項目 2
  3. リスト項目 3
  4. リスト項目 4



## HTML 要素タグテスト

他の HTML タグは <a href="http://ja.support.wordpress.com/code/" target="_blank" rel="nofollow noopener noreferrer">FAQ</a> をご覧ください。

**住所タグ**

以下は住所の例です。`<address>` タグを使用しています:

<address>

〒100-0000  
東京都千代田区1-1-1  
日本

</address>

**anchor タグ (リンク)**

これは <a href="http://example.com/" target="_blank" rel="nofollow noopener noreferrer"><code>&lt;anchor&gt;</code></a> (もしくはリンクとも呼ばれます) の例です。

**abbr タグ**

この <abbr title="abbreviation">abbr</abbr> は文章の中にある `<abbr>` タグの例です。

**Acronym タグ (_HTML5 では非推奨_)**

これは `<acronym>` タグを使用した <acronym title="three-letter acronym">TLA</acronym> です。

**Big タグ(_HTML5 では非推奨_)**

このテストは<big>大きな</big>文字を表す `<big>` タグの例ですが、このタグは HTML5 ではサポートされていません。

**Cite タグ**

&#8220;Code is poetry.&#8221; &#8212;<cite>WordPress</cite>

**Code タグ**

`<code>` タグはこのように使います: `word-wrap: break-word;`

**Delete タグ**

`<del>` タグは<del>打ち消し線</del>などで表現されますが、このタグは HTML5 ではサポートされていません (代わりに `<strike>` を使ってください)。

**Emphasize タグ**

`<em>` タグは*文章の強調*に使われます。欧文では斜体になっていることがよくあります。

**Insert タグ**

`<ins>` タグは<ins>挿入されたコンテンツ</ins>を意味します。

**Keyboard タグ**

このあまり知られていない `<kbd>` タグは <kbd>Ctrl</kbd> のようにキーボードテキストをエミュレートします。通常、`<code>` タグと同じようにスタイリングされます。

**Preformatted タグ**

`<pre>` タグは複数行のコードのスタイリングに使います。

<pre>.post-title {
  margin: 0 0 5px;
  font-weight: bold;
  font-size: 38px;
  line-height: 1.2;
  and here's a line of some really, really, really, really long text, just to see how the PRE tag handles it and to find out how it overflows;
}</pre>

**Quote タグ**

<q>デベロッパーズ、デベロッパーズ, デベロッパーズ&#8230;</q> &#8211;スティーブ・バルマー

**Strike タグ (_HTML5 では非推奨_)**

このタグは<span style="text-decoration: line-through;">打ち消し線</span>を表しています。

**Strong タグ**

このタグは**太字**テキストを表しています。

**Subscript タグ**

Subscript タグ `<sub>` を使うと H<sub>2</sub>O のような表示の際に「2」が下付きになります。

**Superscript タグ**

Superscript タグ `<sup>` を使うと E = MC<sup>2</sup> のような表示の際に「2」が上付きになります。

**Teletype タグ (_HTML5 では非推奨_)**

`<tt>` はあまり使われないタグですが、<tt>テレタイプテキスト</tt> として通常 `<code>` タグのようにスタイル

**Variable タグ**

変数や引数を表す <var>variables</var> タグです。
