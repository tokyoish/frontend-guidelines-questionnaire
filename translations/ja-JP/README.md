# フロントエンドガイドラインについてのアンケート
この1ページのアンケート（チェックリスト）は、あなたのチームが効果的なフロントエンドガイドラインをつくり一貫性とまとまりのあるコードを共に書けるようにする為の補助ツールである。

## HTML
### HTMLの方針
- **あなたのチームがHTMLを書く時に従うべき基本方針は何か？** *(例： セマンティックなHTML5マークアップを書く, アクセシビリティ, 等。 [これらの](http://www.yellowshoe.com.au/standards/#html) [資料を](http://codeguide.co/#html) for [参照](http://manuals.gravitydept.com/code/html))*


### HTML Tools
- **HTML プリプロセッサーを使用しているか？** *(例： [HAML](http://haml.info/), [Jade](http://jade-lang.com/), など)*?
- **テンプレートエンジンを使用しいるか？** *([Mustache](https://mustache.github.io/), [Handlebars](http://handlebarsjs.com/), など)*?
- **バックエンドの構成はフロントエンドに影響するか？** (例： WordPress はマークアップのクラスに`wp-paginate`を加える)? もしあれば, そうしたルールをについてさらに説明できるか？

### HTML 記述のスタイル
- **スペースかタブか?**
- **コメントルールはどういうものか？** 

---------------

## CSS 

### CSSの方針
- **CSSを書く上でのあなたのチームでの基本方針は何か？** *(例, モジュール方式, 長いセレクターの禁止, 等。 [これら](http://cssguidelin.es/)の [資料](http://www.yellowshoe.com.au/standards/#css) [を](http://manuals.gravitydept.com/code/css) [参照](http://codeguide.co/#css))*

### CSSの方法論
- **アナタのチームはCSSメソロジーを使用しいるか？** *(例： [SMACSS](https://smacss.com/), [BEM](https://en.bem.info/method/), or [OOCSS](http://oocss.org/))*? 使用する場合, その方法論に関する文章はどこにあるか?
- **その方法論から逸脱しした実装をしているか？** その場合, その手法を説明することは可能か?

### CSSツール
- **プリプロセッサーを使用しているか？** *([Sass](http://sass-lang.com/) や [Less](http://lesscss.org/))*?
- **プリプロセッサーを使用する上でのガイドラインはあるか** *([Sass Guidelines](https://sass-guidelin.es/) を参照)*?
- **ベースCSSを使用しているか？** *(例： [Normalize](https://necolas.github.io/normalize.css/) や [reset](http://meyerweb.com/eric/tools/css/reset/))*?
- **ポストプロフェッサーを使用しているか？** *(例： [Prefixfree](https://leaverou.github.io/prefixfree/) や [Autoprefixer](https://github.com/postcss/autoprefixer))*?
- **その他、特殊なCSSテクニックを使用しているか？** *(例： [critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/))*?

### CSS フレームワーク
- **チームで使用しているCSSフレームワークはあるか** *(例： [Bootstrap](https://getbootstrap.com/) や [Foundation](http://foundation.zurb.com/))*？ その場合, そのフレームワークの仕様書はどこあるか？
- **フレームワークから何かしら逸脱した実装はしいるか？** その手法を説明することは可能か?

### CSSのコーディングスタイルについて
- **スペースかタブか？**
- **CSSのルールにスペースを含めるか？**
- **プロパティの[グルーピング](https://smacss.com/book/formatting#grouping) ルールはありますか?**
- **コメントルールはどういうものか？** 

---------------

## JavaScript

### 基本方針
- **JavaScriptを書く上でのチームとして踏襲すべき基本方針はあるか？** *( [これらの](https://github.com/airbnb/javascript) [資料](https://github.com/rwaldron/idiomatic.js) を [参考](https://github.com/styleguide/javascript))*


### ツール
- **JSフレームワークをしようしているか？** *(例： [jQuery](https://jquery.com/), [Ember](http://emberjs.com/), [Angular](https://angularjs.org/), 等)*?
- **それらのフレームワークの仕様書はどこにあるか？**
- **polyfills や shimsを何か使用しているか？** *(例： [以下のいずれか](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills))*?
- **プロジェクトで依存している3rdパーティのスクリプトは何か？** *(例えば フォームバリデーションやグラフやアニメーション等)*?
- **JavaScriptのテストは実施しているか？** その場合, 使用しているツールは何か？ *(例： [Jasmine](https://jasmine.github.io/), [Karma](https://github.com/karma-runner/karma), [Selenium](http://docs.seleniumhq.org/), 等)*?

### JavaScript の記述スタイルについて 
*( [これら](https://github.com/airbnb/javascript) [資料](https://github.com/rwaldron/idiomatic.js) を [参照](https://github.com/styleguide/javascript))*
- **スペースかタブか？**
- **コメントルールはどのようなものか？** 
- **踏襲すべきデザインパターンはどのようなものか？** *(See [these](https://addyosmani.com/resources/essentialjsdesignpatterns/book/) [resources](https://shichuan.github.io/javascript-patterns/))*

---------------

## メディアについて
- **アイコンの実装法はどのようなものか？** *(SVG, アイコンフォント, 等)*?
- **レスポンシブ画像はどうのように扱っているか？** *(`srcset` と `<picture />`を使用する等)*?
- **画像最適化の為に [ツール](https://addyosmani.com/blog/image-optimization-tools/) を使用しているか**?

---------------

## フォントについて
- **カスタムフォントをどのようにロードしているか？**
- **ウェブフォントを実装するために何かツールを使用しているか？** *(例： [Font Squirrel](https://www.fontsquirrel.com/), など)*?
- **カスタムフォントの為のサービスを利用しているか？** *(例： [Fonts.com](https://www.fonts.com/), [Typekit](https://typekit.com/), 等)*?


---------------

## パフォーマンスについて
- **パフォーマンスの目標値はあるか？** ある場合, どのような [計算方法](https://timkadlec.com/2014/11/performance-budget-metrics/) を使用してその目標値を決定しているか？
- **プロジェクトのスピードをどのように計測しているか？** *(例： [Pingdom Speed Test](http://tools.pingdom.com/) や [Google PageSpeed](https://developers.google.com/speed/pagespeed/))*?
- **ファイルサイズを圧縮する為に何か特別な方法を採用しているか？** *(例： [Gzip](https://css-tricks.com/snippets/htaccess/active-gzip-compression/), [画像最適化](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization))*?
- **ワークフローの中でパフォーマンスに関連したツールを使用しているか？** *(例：[WebPagetest](http://www.webpagetest.org/), [BigRig](https://aerotwist.com/blog/bigrig/) [Speedcurve](https://speedcurve.com/))*?


---------------

## アクセシビリティについて
- **[このチェックリスト](http://a11yproject.com/checklist.html)に記載されているアクセシビリティに関する勧告にしたがっているか?**
- **ワークフローの中でアクセシビリティに関連した [ツール](http://a11yproject.com/resources.html) を使用しているか？**

---------------

## その他ツールについて
- **タスクランナーを使用しているか？** *(例： [Grunt](http://gruntjs.com/) や [Gulp](http://gulpjs.com/))*?
- **依存関係を管理するツールを使用しているか？** *(例： [Bower](http://bower.io/) or [Composer](https://getcomposer.org/))*?
- **スキャフォールディングツールを使用しているか？** *(例： [Yeoman](http://yeoman.io/))*?
- **フロントエンドのスタイルを強化するための何かしらのツールを使用しているか？** *(例： [Editor Config](http://editorconfig.org/) or [linters](https://github.com/CSSLint/csslint))*?
- **このプロジェクトに従事するに辺り何か特定のその他のソフトウェアを使用する必要があるか？**

---------------

## バージョン管理について
- **どのバージョン管理ツールを使用しているか？** *( 例：[Git](https://git-scm.com/) や [Subversion](https://subversion.apache.org/))*?
- **バージョン管理されたコードはどこにホストされているか？** *(例： [Github](https://github.com/) or [Bitbucket](https://bitbucket.org/))*?
- **バージョン管理ワークフローを採用しているか？** *(例： [gitflow](http://nvie.com/posts/a-successful-git-branching-model/), [centralized](https://www.atlassian.com/git/tutorials/comparing-workflows/centralized-workflow), [feature-branch](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow), etc)*?
- **バージョン管理されたコードを管理、統制している人は誰か？**
- **課題管理はどこでされているか？**

-----------

## 「サポート と 最適化」について
["サポート" と "最適化"](http://bradfrost.com/blog/mobile/support-vs-optimization/)の違いについて認識することは重要です。アナタのビジネスとユーザーにとって最も理にかなった環境に最適化するのと同時に一方で、できるだけ多くの環境をサポートする事にベストをつくすべきです。

- ***最適化*対象のブラウザーはどれか？** 
- ***最適化*対象のデバイスはどれか？** 
- **[グレードブラウザーサポート](https://github.com/yui/yui3/wiki/Graded-Browser-Support) システムを採用しているか？**
- **[さらに具体的な格付け（グレーディング）](https://www.filamentgroup.com/lab/grade-the-components.html)を必要とする特定のコンポーネントはあるか？** 

-----------

## ローカライズに関して
- **ウェブサイトは別の言語対応か？** その場合、別の言語にローカライズする時にどのような配慮がされるべきか？

-----------

## 開発/実装について
- **プロダクション環境にフロントエンドのコードはどのように実装されるか？**

-----------

## ドキュメンテーションについて
- **フロントエンドの機構を文書化するために[パターンライブラリーツール](http://styleguides.io/tools.html) を使用しているか？**
- **文書化された仕様書の所在はどこか？** リンクはあるか？
- **メンテナンスと管理は誰の責任範囲か？**
- **ガイドラインがアップデートされた場合どうするか？**

-----------

*Feel free to modify or extend (such as adding specific sections for performance, accessibility, etc) this document for your own organization's needs. For questions, comments, additions, and corrections, please open an issue on Github and/or reach out to [@brad_frost](https://twitter.com/brad_frost) on Twitter.*
