<h1 align="center">
<br>
  <a href="https://github.com/thedaviddias/Front-End-Performance-Checklist"><img src="https://raw.githubusercontent.com/thedaviddias/Front-End-Performance-Checklist/master/images/logo-front-end-performance-checklist.jpg" alt="Front-End Performance Checklist" width="170"></a>
  <br>
    <br>
  Front-End Performance Checklist
  <br>
</h1>

<h4 align="center">🎮 何よりも早く動作するための唯一のフロントエンドパフォーマンスチェックリストです。</h4>
<p align="center">シンプルなルール: "パフォーマンスを考慮してデザイン・コーディングすること"</p>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
  <a href="https://discord.gg/btHQRkm">
    <img src="https://img.shields.io/badge/chat-on_discord-4837E2.svg?style=flat-square" alt="Discord">
  </a>
    <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="Licence MIT">
  </a>
</p>

<p align="center">
  <a href="#使い方">使い方</a> • <a href="#contributing">Contributing</a> • <a href="http://feedback.frontendchecklist.io/">ロードマップ</a> • <a href="https://www.producthunt.com/posts/front-end-performance-checklist">Product Hunt</a>
</p>

<p align="center">
  <a href="https://github.com/JohnsenZhou/Front-End-Performance-Checklist">🇨🇳</a>
  <a href="https://github.com/WilliamDASILVA/Front-End-Performance-Checklist">🇫🇷</a>
  <a href="https://github.com/ParkSB/Front-End-Performance-Checklist">🇰🇷</a>  
  <a href="https://github.com/fernandofawkes/Front-End-Performance-Checklist">🇵🇹</a>
  <a href="https://github.com/lex111/Front-End-Performance-Checklist">🇷🇺</a>
</p>

<p align="center">
    <span>Other Checklists:</span>
    <br>
  🗂 <a href="https://github.com/thedaviddias/Front-End-Checklist#---------front-end-checklist-">Front-End Checklist</a> • 💎 <a href="https://github.com/thedaviddias/Front-End-Design-Checklist#front-end-design-checklist">Front-End Design Checklist</a>
</p>

## Table of Contents

1. **[HTML](#html)**
2. **[CSS](#css)**
3. **[Fonts](#fonts)**
4. **[Images](#images)**
5. **[JavaScript](#javascript)**
6. **[サーバ](#サーバ) （作成中）**
7. **[JS Frameworks](#performances-and-js-frameworks) （作成中）**

## はじめに

パフォーマンスは大きなテーマですが、いつも "バックエンド" や "管理者" の問題というわけではありません。フロントエンドの責任範囲でもあります。このフロントエンドパフォーマンスチェックリストは、フロントエンド開発者としてプロジェクト（個人でも業務でも）に充たる場合に、確認もしくは気にしておくべき項目を網羅的にリストアップしたものです。

### 使い方

各ルールには、このルールが重要である *理由* と 修正する *方法* を記載しています。より詳細な情報は、 🛠: ツール、 📖: 記事、 📹: 動画サイト のリンクを参照してください。

**フロントエンドパフォーマンスチェックリスト** は、どれも最高のパフォーマンススコアを達成するためには不可欠な項目ですが、どのルールを優先的に適用すべきかを３段階で示しています。

* ![Low][low] は、優先度が **低** であることを意味しています。
* ![Medium][medium] は、優先度が **中** であることを意味しています。 このルールの適用を避けるべきではありません。
* ![High][high] は、優先度が **高** であることを意味しています。 このルールに従い、推奨される方法で実装してください。

### パフォーマンスツール

ウェブサイト または アプリケーションのテストやモニタリングに使用できるツールのリスト:

 * 🛠 [WebPagetest - Website Performance and Optimization Test](https://www.webpagetest.org/)
 * 🛠 ☆ [Dareboost: Website Speed Test and Website Analysis](https://www.dareboost.com/) (use the coupon WPCDD20 for -20%)
 * 🛠 [Treo: Page Speed Monitoring](https://treo.sh/?ref=perfchecklist)
 * 🛠 [GTmetrix | Website Speed and Performance Optimization](https://gtmetrix.com/)
 * 🛠 [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
 * 🛠 [Web.dev](https://web.dev/measure)
 * 🛠 [Pingdom Website Speed Test](https://tools.pingdom.com)
 * 📖 [Make the Web Faster | Google Developers](https://developers.google.com/speed/)
 * 🛠 [Sitespeed.io - Welcome to the wonderful world of Web Performance](https://www.sitespeed.io/)
 * 🛠 [Calibre](https://calibreapp.com/)
 * 🛠 [Website Speed Test | Check Web Performance &raquo; Dotcom-Tools](https://www.dotcom-tools.com/website-speed-test.aspx)
 * 🛠 [Website and Server Uptime Monitoring - Pingdom](https://www.pingdom.com/product/uptime-monitoring/) ([Free Signup Link](https://www.pingdom.com/free))
 * 🛠 [Uptime Robot](https://uptimerobot.com)
 * 🛠 [SpeedCurve: Monitor front-end performance](https://speedcurve.com)
 * 🛠 [PWMetrics - CLI tool and lib to gather performance metrics](https://github.com/paulirish/pwmetrics)
 * 🛠 [Varvy - Page speed optimization]( https://varvy.com/pagespeed/)
 * 🛠 [Lighthouse - Google]( https://developers.google.com/web/tools/lighthouse/#devtools)
 * 🛠 [Checkbot browser extension - Checks for web performance best practices](https://www.checkbot.io/)
 * 🛠 [Yellow Lab Tools | Online test to help speeding up heavy web pages](https://yellowlab.tools/)
 * 🛠 [Speedrank - Web Performance Monitoring](https://speedrank.app/)
 * 🛠 [DebugBear - Monitor website performance and Lighthouse scores](https://www.debugbear.com/)
 * 🛠 [packtracker.io - Check your webpack bundle size on every pull request.](https://packtracker.io/)
 * 🛠 [Exthouse - Analyze the impact of a browser extension on web performance](https://github.com/treosh/exthouse)
 
### 参考文献

 * 📹 [The Cost Of JavaScript - YouTube](https://www.youtube.com/watch?v=_bzqF05xsC4) ([text version](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4))
 * [AddyOsmani.com - Start Performance Budgeting](https://addyosmani.com/blog/performance-budgets/)
 * 📖 [Get Started With Analyzing Runtime Performance  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)
 * 📖 [State of the Web | 2018_01_01](https://httparchive.org/reports/state-of-the-web?start=2018_01_01)
 * 📖 [Page Weight Doesn't Matter](https://www.speedshop.co/2015/11/05/page-weight-doesnt-matter.html)
 * 📖 [Front-End Performance Checklist 2018 [PDF, Apple Pages]](https://www.smashingmagazine.com/2018/01/front-end-performance-checklist-2018-pdf-pages/)
 * 📖 [Designing for Performance Weighing Aesthetics and Speed - By Lara Callender Hogan [eBook, Print]](http://designingforperformance.com/index.html)
 * 📖 [Varvy - Web performance glossary](https://varvy.com/performance/)
 * 📖 [fabkrum/web-performance-resources: Up to date collection of valuable web performance resources](https://github.com/fabkrum/web-performance-resources)
 * 📖 [Checkbot - Web Speed Best Practices](https://www.checkbot.io/guide/speed/)
 * 🛠 [Progressive Tooling - A list of community-built, third-party tools that can be used to improve page performance](https://progressivetooling.com/)

---

## HTML

![html]

- [ ] **HTML の軽量化（Minified）:** ![medium] HTML コードは圧縮され、コメント、空白、改行が本番のファイルから削除されていること。

    *理由:*
    > 不要なスペース、コメント、ブレークを全て削除すると、HTML のサイズが小さくなり、サイトのページの読み込み時間が短縮され、ユーザのダウンロードにかかる時間が明らかに軽減されます。

    *方法:*
    > ほとんどのフレームワークには、Web ページを容易に圧縮することができるプラグインがあります。自動的にジョブを実行できる多くの NPM モジュールを使用できます。

    * 🛠 [HTML minifier | Minify Code](http://minifycode.com/html-minifier/)
    * 🛠 [Online HTML Compressor](http://refresh-sf.com)
    * 📖 [Experimenting with HTML minifier — Perfection Kills](http://perfectionkills.com/experimenting-with-html-minifier/#use_short_doctype)

- [ ] **不要なコメントの削除:** ![low] コメントがページから削除されていることを確認してください。

    *理由:*
    > コメントはユーザにとって何も役に立たないので、本番のファイルからは削除すべきです。コメントを保持したくなるケースは、ライブラリのソースを保持する必要がある場合くらいです。

    *方法:*
    > ほとんどの場合、コメントは HTML 圧縮プラグインを使って削除することができます。

 * 🛠 [remove-html-comments - npm](https://www.npmjs.com/package/remove-html-comments)

- [ ] **不要な属性の削除:** ![low] `type="text/javascript"` や `type="text/css"` のようなタイプ属性は、もはや必要ではないため削除すべきです。

    ```html
    <!-- Before HTML5 -->
    <script type="text/javascript">
        // JavaScript code
    </script>

    <!-- Today -->
    <script>
        // JavaScript code
    </script>
    ```

    *理由:*
    > HTML5 ではデフォルトで text/css と text/javascript が含まれているため、タイプ属性は必要ありません。未使用のコードはページを重くするため、ウェブサイトやアプリで使用されないコードは削除すべきです。

    *方法:*
    > すべての `<link>` および `<script>` タグに type 属性がないことを確認してください。

    * 📖 [The Script Tag | CSS-Tricks](https://css-tricks.com/the-script-tag/)
   
- [ ] **CSS タグは必ず JavaScript タグの前に配置:** ![high] 必ず CSS が JavaScript コードの前にロードされることを確認してください。

    ```html
    <!-- Not recommended -->
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    <link rel="stylesheet" href="foo.css"/>

    <!-- Recommended -->
    <link rel="stylesheet" href="foo.css"/>
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    ```

    *理由:*
    > JavaScript の前に CSS タグを置くと、より効率的な並列ダウンロードが可能となり、ブラウザのレンダリング時間が短縮されます。

    *方法:*
    > `<head>` 内の `<link>` と `<style>` が、常に `<script>` の前にあることを確認してください。

    * 📖 [Ordering your styles and scripts for pagespeed](https://varvy.com/pagespeed/style-script-order.html)

- [ ] **iframe の数を最小限に抑える:** ![high] iframe は他の技術的な可能性がない場合にのみ使用してください。できる限り iframe の使用を避けましょう。

- [ ] **prefetch、dns-prefetch、prerender での事前読み込みによる最適化:** ![low] 一般的なブラウザでは、`<link>`タグに "rel" 属性のディレクティブ指定することで特定の URL を事前読み込みすることができます。

    *理由:*
    > 事前読込み（Prefetching）により、ブラウザはユーザが近い将来アクセスする可能性のあるコンテンツの表示に必要なリソースを事前に取得しておくことができます。ブラウザはこれらのリソースをキャッシュに保存するので、コンテンツが異なるドメインを使っている場合でも Web ページの読み込みを高速化できます。 Web ページの読み込みが完了し、アイドル時間が経過すると、ブラウザは他のリソースのダウンロードを開始します。ユーザが特定のリンク（事前読み込み済み）にアクセスすると、コンテンツは即時に提供されます。

    *方法:*
    > ⁃ `<link>` タグが`<head>` タグ内に あることを確認してください。

    * 📖 [What Is Prefetching and Why Use It](https://www.keycdn.com/support/prefetching)
    * 📖 [Prefetching, preloading, prebrowsing](https://css-tricks.com/prefetching-preloading-prebrowsing/)
    * 📖 [What is Preload, Prefetch, and Preconnect](https://www.keycdn.com/blog/resource-hints)

**[⬆ トップに戻る](#table-of-contents)**

## CSS

![css]

- [ ] **ファイルの軽量化（minification）:** ![high] すべての CSS ファイルは圧縮され、コメント、空白、改行が本番のファイルから削除されています。

    *理由:*
    > CSS ファイルの圧縮を行うと、コンテンツの読み込み時間が早くなりクライアントに送信されるデータが少なくなります。常に本番用の CSS ファイルは圧縮されていることが重要です。帯域幅やリソース使用量を削減したいビジネスユーザにとって有益です。

    *方法:*
    > ⁃ ビルドまたはデプロイメントの前または途中でファイルを自動的に圧縮するツールを使用します。

    * 🛠 [cssnano: A modular minifier based on the PostCSS ecosystem. - cssnano](https://cssnano.co/)
    * 🛠 [@neutrinojs/style-minify - npm](https://www.npmjs.com/package/@neutrinojs/style-minify)
    * 🛠 [Online CSS Compressor](http://refresh-sf.com)


- [ ] **ファイルの結合:** ![medium] CSS ファイルを1ファイルに結合します。 *（HTTP/2 では常に有効とは限りません）*

    ```html

    <!-- Not recommended -->
    <link rel="stylesheet" href="foo.css"/>
    <link rel="stylesheet" href="bar.css"/>

    <!-- Recommended -->
    <link rel="stylesheet" href="foobar.css"/>
    ```

    *理由:*
    > まだ HTTP/1 を使用していれば、ファイルを結合する必要があるかもしれません。もしサーバが HTTP/2 を使用している場合はその限りではありません。（テストを行う必要があります）

    *方法:*
    > ⁃ ビルド前かビルド中、もしくはデプロイ前かデプロイ中に、オンラインのツールもしくはプラグインを使ってファイルを結合します。 <br>
    ⁃ もちろん、結合によりプロジェクトが壊れないかどうかは確認してください。

    * 📖 [HTTP: Optimizing Application Delivery - High Performance Browser Networking (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
    * 📖 [Performance Best Practices in the HTTP/2 Era](https://deliciousbrains.com/performance-best-practices-http2/)

- [ ] **ノンブロッキング:** ![high] DOM の読み込みに時間がかかるのを防ぐため、CSS ファイルはノンブロッキングである必要があります。

    ```html
    <link rel="preload" href="global.min.css" as="style" onload="this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="global.min.css"></noscript>
    ```

    *理由:*
    > CSS ファイルは、ページの読み込みをブロックしレンダリングを遅延させる可能性があります。`preload` を使用すると、ブラウザがページのコンテンツを表示し始める前に CSS ファイルを読み込ませることができます。

    *方法:*
    > ⁃ `preload` の値を持つ `rel` 属性と、`as="style"` を `<link>` 要素に追加する必要があります。

    * 🛠 [loadCSS by filament group](https://github.com/filamentgroup/loadCSS)
    * 📖 [Example of preload CSS using loadCSS](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf)
    * 📖 [Preloading content with rel="preload"](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content)
    * 📖 [Preload: What Is It Good For? — Smashing Magazine](https://www.smashingmagazine.com/2016/02/preload-what-is-it-good-for/)

- [ ] **CSS クラスの長さ:** ![low] クラスの長さは（最終的に）HTML ファイルと CSS ファイルに（わずかな）影響を与える可能性があります。

    *理由:*
    > パフォーマンスへの影響も議論の余地がありますが、プロジェクトの命名規則を決めておくと、スタイルシートの保守性に大きな影響を与える可能性があります。BEM を使用する場合、必要以上の文字がクラスに含まれることがあります。名前や名前空間をしっかりと考え選択することは常に重要です。

    *方法:*
    > 文字数に制限を設定することは一部の人にとっては興味深いことですが、ウェブサイトをコンポーネントに分割することで、クラス（および宣言）の数と長さを減らすことができます。

    * 🛠 [long vs short class · jsPerf](https://jsperf.com/long-vs-short-class)

- [ ] **未使用の CSS:** ![medium] 未使用の CSS セレクタを削除する。

    *理由:*
    > 未使用の CSS セレクタを削除すると、ファイルサイズが削減できアセットの読み込みも早くなります。

    *方法:*
    > ⁃ ⚠️ 使用する CSS フレームワークにリセット CSS / ノーマライズ CSS のコードが含まれていないかどうかを常に確認してください。リセット CSS / ノーマライズ CSS ファイルに記載されている全てのコードを必要としない場合があります。

    * 🛠 [UnCSS Online](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **クリティカル CSS:** ![high] クリティカル CSS（または above the fold）とは、ファーストビューのレンダリングに使用されるすべての CSS です。主要な CSS の読み込み前にこれを `<style></style>` タグにインライン化（可能な限り圧縮）して記載します。

    *理由:*
    > インライン化したクリティカル CSS を使用すると、Web ページのレンダリングを高速化し、サーバへのリクエスト回数を減らすことができます。

    *方法:*
    > オンラインツール、または Addy Osmani が開発したようなプラグインを使用してクリティカル CSS を生成することができます。

    * 📖 [Understanding Critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)
    * 🛠 [Critical by Addy Osmani on GitHub](https://github.com/addyosmani/critical) automates this.
    * 📖 [Inlining critical CSS for better web performance | Go Make Things](https://gomakethings.com/inlining-critical-css-for-better-web-performance/)
     * 🛠 [Critical Path CSS Generator - Prioritize above the fold content :: SiteLocity](https://www.sitelocity.com/critical-path-css-generator)
     * 📖 [Reduce the size of the above-the-fold content
](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)

- [ ] **埋め込み または インライン CSS:** ![high] `<body>` 内で埋め込み CSS、またはインライン CSS を使うのは避けましょう。 *（HTTP/2 では無効）*

    *理由:*
    > 最初の理由の一つは、**コンテンツをデザインから分離** することがグッドプラクティスだからです。コードの保守性が向上し、サイトのアクセシビリティも向上します。パフォーマンスに関して言うと、HTML ページのファイルサイズと読み込み時間を短縮することができます。

    *方法:*
    > 常に外部スタイルシートを使用するか、`<head>` に CSS を埋め込みます。（他の CSS パフォーマンスルールに従います）

    * 📖 [Observe CSS Best Practices: Avoid CSS Inline Styles](https://www.lifewire.com/avoid-inline-styles-for-css-3466846)

- [ ] **スタイルシートの複雑さを分析する:** ![high] スタイルシートを分析すると、CSS セレクタの問題、冗長性、重複を見つけるのに役立ちます。

    *理由:*
    > CSS に冗長性や検証エラーがある場合は、CSS ファイルを分析しこれらの複雑なコードを削除すると、CSS ファイルの読み込みが高速化されます。（ブラウザが高速に読み取るためです）

    *方法:*
    > CSS プリプロセッサを使用して、CSS を整理する必要があります。下記のオンラインツールの一部はコードの分析と修正にも役立ちます。

    * 🛠 [TestMyCSS | Optimize and Check CSS Performance](http://www.testmycss.com/)
    * 🛠 [CSS Stats](https://cssstats.com/)
    * 🛠 [macbre/analyze-css: CSS selectors complexity and performance analyzer](https://github.com/macbre/analyze-css)
    * 🛠 [Project Wallace](https://www.projectwallace.com/) は  CSS Stats に似ていますが、変更を追跡できるように統計結果を長期間保存します。

**[⬆ トップに戻る](#table-of-contents)**

## Fonts

![fonts]

* 📖 [A Book Apart, Webfont Handbook](https://abookapart.com/products/webfont-handbook)

- [ ] **Webfont formats:** ![medium] You are using WOFF2 on your web project or application.

    *Why:*
    > According to Google, the WOFF 2.0 Web Font compression format offers 30% average gain over WOFF 1.0. It's then good to use WOFF 2.0, WOFF 1.0 as a fallback and TTF.

    *How:*
    > Check before buying your new font that the provider gives you the WOFF2 format. If you are using a free font, you can always use Font Squirrel to generate all the formats you need.

    * 📖 [WOFF 2.0 – Learn more about the next generation Web Font Format and convert TTF to WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Create Your Own @font-face Kits » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/)
    * 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Use `preconnect` to load your fonts faster:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

    *Why:*
    > When you arrived on a website, your device needs to find out where your site lives and which server it needs to connect with. Your browser had to contact a DNS server and wait for the lookup complete before fetching the resource (fonts, CSS files...). Prefetches and preconnects allow the browser to lookup the DNS information and start establishing a TCP connection to the server hosting the font file. This provides a performance boost because by the time the browser gets around to parsing the css file with the font information and discovering it needs to request a font file from the server, it will already have pre-resolved the DNS information and have an open connection to the server ready in its connection pool.

    *How:*
    > ⁃ Before prefetching your webfonts, use webpagetest to evaluate your website <br>
    ⁃ Look for teal colored DNS lookups and note the host that are being requested <br>
    ⁃ Prefetch your webfonts in your `<head>` and add eventually these hostnames that you should prefetch too

    * 📖 [Faster Google Fonts with Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Make Your Site Faster with Preconnect Hints | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Ultimate Guide to Browser Hints: Preload, Prefetch, and Preconnect - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [A Comprehensive Guide to Font Loading Strategies—zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)
    * 🛠 [typekit/webfontloader: Web Font Loader gives you added control when using linked fonts via @font-face.](https://github.com/typekit/webfontloader)

- [ ] **Webfont size:** ![medium] Webfont sizes don't exceed 300kb (all variants included)

 * 📖 [Font Bytes - Page Weight](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **Prevent Flash or Invisible Text:** ![medium] Avoid transparent text until the Webfont is loaded

 * 📖 [`font-display` for the Masses](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: The Future of Font Rendering on the Web](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ back to top](#table-of-contents)**

## Images

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **画像の最適化:** ![high] エンドユーザーに直接影響を与えることなく画像を圧縮し、最適化してください。

    *理由:*
    > 最適化された画像はより高速にブラウザに読み込まれるため、データの消費が少なくなります。

    *方法:*
    > ⁃ 可能であれば、CSS3 エフェクトを使用してください（小さな画像の代わりに） <br>
    ⁃ 可能であれば、画像にはテキストエンコードの代わりにフォントを使用してください <br>
    ⁃ SVG を使用してください <br>
    ⁃ ツールを使って、圧縮レベルを 85 未満に指定してください

    * 📖 [Image Optimization | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 📖 [Essential Image Optimization - An eBook by Addy Osmani](https://images.guide/)
    * 🛠 [TinyJPG – Compress JPEG images intelligently](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Online Image Optimizer](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - optimize and compress JPEG photos and PNG images](https://compressor.io/compress)
    * 🛠 [Cloudinary - Image Analysis Tool](https://webspeedtest.cloudinary.com)
    * 🛠 [ImageEngine - Image Webpage Loading Test](https://demo.imgeng.in)
    * 🛠 [SVGOMG - Optimize SVG vector graphics files](https://jakearchibald.github.io/svgomg/)


* [ ] **画像形式:** ![high] 画像形式を適切に選んでください。

    *理由:*
    > 画像が原因で Web サイトの速度を低下させないようにするには、画像に適した形式を選びます。写真の場合、PNG や GIF よりも JPEG が適しています。ただし、ファイルのサイズを削減できる next-gen 形式を確認することを忘れないでください。各画像形式には長所と短所がありますが、最も良い選択をするためにこれらのことを知っておくことが重要です。

    *方法:*
    > ⁃ [Lighthouse](https://developers.google.com/web/tools/lighthouse/) を使用して、画像が **next-gen 形式**  (like JPEG 2000m、JPEG XR、WebP など) を使用できるかを特定します。 <br>
    ⁃ 複数の異なる画像形式を比較してください。PNG8 よりも PNG16 を使用する方が良い場合もあります。

    * 📖 [Serve Images in Next-Gen Formats  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [What Is the Right Image Format for Your Website? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - The Clear Winner — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-bit vs 16-bit - What Color Depth You Should Use And 理由 It Matters - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **ベクター画像かラスター/ビットマップを使用する:** ![medium] ビットマップ画像よりもベクター画像を使用することをお勧めします（可能な場合）。

    *理由:*
    > ベクター画像 (SVG) はサイズが小さくなる傾向があり、レスポンシブでスケールすることができます。またこれらの画像は、CSS を使ってアニメーションしたり変更したりできます。


* [ ] **画像の大きさ:** ![medium] レンダリング時の画像サイズがわかっている場合は、`<img>` タグに `width` と `height` の属性を設定します。

    *理由:*
    > あらかじめ画像に高さと幅が設定されていれば、ページをローディングする時に画像表示に必要なスペースが確保されますが、もしこれらの属性が設定されていなければ、ブラウザは画像のサイズを認識できず適切なスペースを確保することができません。これにより、ページ（画像ファイル）のローディング中に、レイアウトが変更されるという影響が出てしまいます。

* [ ] **Base64 画像の使用を避ける:** ![medium] 小さな画像であれば base64 に変換することもできますが、実際これはベストプラクティスではありません。

    * 📖 [Base64 Encoding & Performance, Part 1 and 2 by Harry Roberts](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [A closer look at Base64 image performance – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [When to base64 encode images (and when not to) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
   * 📖 [Base64 encoding images for faster pages | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Lazy loading（遅延読み込み）:** ![medium] オフスクリーン画像（ブラウザに初期表示されない画像）は遅延ロードします（noscript fallback は常に提供されます）。

    *理由:*
    > 表示画面の応答時間を短縮し、ユーザーが必要としない不要な画像の読み込みを回避することができます。

    *方法:*
    > ⁃ [Lighthouse](https://developers.google.com/web/tools/lighthouse/) を使用して、**オフスクリーン画像** の数を特定します。<br>
    ⁃ 以下のような JavaScript プラグインを使用して、画像の遅延読み込みを行います。必ずオフスクリーン画像のみを遅延読み込み対象にしてください。 <br>
    ⁃ また、マウスオーバー時やユーザー操作時に表示される代替画像も遅延読み込みするようにしてください。

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 📖 [Lazy Loading Images and Video  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 Brilliant Ways to Lazy Load Images For Faster Page Loads - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **レスポンシブ画像:** ![medium] ディスプレイサイズに近い画像を利用するようにしてください。

    *理由:*
    > 画面が小さいデバイスでは、ビューポートよりも大きな画像を必要としません。1 つの画像をそれぞれの異なるサイズで複数枚用意しておくことをお勧めします。

    *方法:*
    > ⁃ ターゲットとするデバイス用に異なる画像サイズを作成します。<br>
    ⁃ `srcset` 属性や `picture` タグを使用して、各画像の複数のバリエーションを配信します。

     * 📖 [Responsive images - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ トップに戻る](#table-of-contents)**

## JavaScript

![javascript]

- [ ] **JS 圧縮:** ![high] 全ての JavaScript ファイルが圧縮され、コメント、空白、および改行がプロダクションファイルから削除されます *（HTTP/2を使用している場合でも有効です）*。

    *理由:*
    > 不要なスペース、コメント、ブレークをすべて削除すると、JavaScript ファイルのサイズが小さくなり、サイトのページの読み込み時間が短縮され、ユーザのダウンロードが明らかに軽くなります。

    *方法:*
    > ⁃ 以下に示すツールを使用して、ビルドまたはデプロイメントの前か最中にファイルを自動的に圧縮します。

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Online JavaScript Compressor](http://refresh-sf.com)
    * 📖 [Short read: How is HTTP/2 different? Should we still minify and concatenate?](https://scaleyourcode.com/blog/article/28)

* [ ] **JavaScriptを内部には無記載 :** ![medium] *（ウェブサイトでのみ有効です）* body 内部に複数の JavaScript コードを埋め込むことは避けてください。JavaScript コードを外部ファイル内に、最終的には `<head>` 、またはページの最後（`</body>` の前）で再グループ化します。

    *理由:*
    > JavaScript の埋め込みコードを直接 `<body>` に配置すると、DOM の構築中にページが読み込まれるため、ページの速度が低下する可能性があります。 最適なオプションは、DOM のブロックを回避するために、`async` または `defer` で外部ファイルを使用することです。 別のオプションは、`<head>` 内にいくつかのスクリプトを配置することです。`<head>` に配置するスクリプトは、ほとんどの場合、DOM がメイン処理に到達する前にロードする必要がある分析コードまたは小さなスクリプトです。

    *方法:*
    > すべてのファイルが `async` または `defer` を使用してロードされていることを確認し、`<head>` に挿入する必要があるコードかどうか見極めましょう。

     * 📖 [11 Tips to Optimize JavaScript and Improve Website Loading Speeds](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **ノンブロッキング JavaScript:** ![high] JavaScript ファイルは、`async` を使用して非同期でロードされるか、`defer` 属性を使用して遅延ロードされます。

    ```html
    <!-- Defer 属性 -->
    <script defer src="foo.js"></script>

    <!-- Async 属性 -->
    <script async src="foo.js"></script>
    ```

    *理由:*
    > JavaScript は、通常の HTML ドキュメント解析をブロックするため、パーサが `<script>` タグに到達すると（特に `<head>` 内にある）、フェッチと実行を停止します。スクリプトをページの上部に配置する場合は `async` または `defer` を追加することを強く推奨しますが、`</ body>` タグの直前ではあまり効果がありません。ただし、これらの属性を常時使用し、パフォーマンスの問題を回避することが望ましいです。

    *方法:*
    > ⁃ スクリプトタグの属性として、`async`（スクリプトが他のスクリプトに依存していない場合）または `defer`（スクリプトが他のスクリプトに依存、または非同期スクリプトに依存している場合）を追加します。 <br>
     ⁃ 小さなスクリプトは、非同期スクリプトの上にインラインスクリプトで配置することをお勧めします。

    * 📖 [Remove Render-Blocking JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)
    * 📖 [Defer loading JavaScript](https://varvy.com/pagespeed/defer-loading-javascript.html)

* [ ] **最適化およびアップデートされた JS ライブラリ:** ![medium] プロジェクトで使用される全ての JavaScript ライブラリが必要であって（単純な機能についてはバニラ JavaScript を推奨）、JavaScript ライブラリを最新バージョンへアップデートし、不必要なメソッドで JavaScript をうめつくさないでください。

    *理由:*
    > ほとんどの場合、新しいバージョンには最適化とセキュリティ修正が含まれています。最適化されたコードでプロジェクトを高速化し、古いプラグインを使うことなく、ウェブサイトまたはアプリの速度を落とさないようにしてください。

    *方法:*
    > プロジェクトで NPM パッケージを使用している場合、[npm-check](https://www.npmjs.com/package/npm-check) は、ライブラリをアップグレード／アップデートするための非常に興味深いライブラリです。
    > [Greenkeeper](https://greenkeeper.io/) は、依存関係を自動的に探し、新しいバージョンがリリースされる度にアップデートを提案します。

    * 📖 [You may not need jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Vanilla JavaScript for building powerful web applications](https://plainjs.com/)

- [ ] **依存関係のサイズ制限を確認:** ![low] 外部ライブラリは見極めてから使用してください。ほとんどの場合、同じ機能であればより軽いライブラリを使用します。

    *理由:*
    > [npm](https://www.npmjs.com/) にある745 000パッケージのいずれかを使用したくなるかもしれませんが、ニーズに最適なパッケージを選択する必要があります。例えば、MomentJS は素晴らしいライブラリですが、まったく使われることがない多くのメソッドを備えているため、Day.js が作成されました。Day.js は2 kB で、MomentJS は16.4 kB gz です。

    *方法:*
    > 常にニーズに合った最適で軽量なライブラリを比較して選択してください。[npm trend](http://www.npmtrends.com/) などのツールを使用して NPM パッケージのダウンロード数を比較したり、[Bundlephobia](https://bundlephobia.com/) を使用して依存関係のサイズを確認したりすることもできます。

    * 🛠 [ai/size-limit: Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 🛠 [js-dependency-viewer - npm](https://www.npmjs.com/package/js-dependency-viewer)
    * 📖 [Size Limit: Make the Web lighter — Martian Chronicles, Evil Martians’ team blog](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **JavaScript プロファイリング:** ![medium] JavaScript ファイル（および CSS）のパフォーマンスの問題を確認します。

    *理由:*
    > JavaScript が複雑になると、ランタイムのパフォーマンスが低下する可能性があります。 考えられるこれらの問題を特定することは、スムーズなユーザエクスペリエンスを提供するために不可欠です。

    *方法:*
    > Chrome 開発者ツールのタイムラインツールを使用してスクリプトイベントを評価し、時間がかかりすぎるイベントを見つけます。

     * 📖 [Speed Up JavaScript Execution  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [JavaScript Profiling With The Chrome Developer Tools — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [How to Record Heap Snapshots  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Chapter 22 - Profiling the Frontend - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)
    * 📖 [30 Tips To Improve Javascript Performance](http://www.monitis.com/blog/30-tips-to-improve-javascript-performance/)

- [ ] **Service Worker の使用:** ![medium] PWA で Service Worker を使用して、アプリケーションのユーザエクスペリエンスに影響を与えることなく、データをキャッシュしたり、重いタスクを実行したりします。
   
    * 📖 [Service Workers: an Introduction  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers/)
    * 📖 [Measuring the Real-world Performance Impact of Service Workers  |  Web  |  Google Developers](https://developers.google.com/web/showcase/2016/service-worker-perf)
    * 📖 [What Are Service Workers and How They Help Improve Performance](https://www.keycdn.com/blog/service-workers/)
    * 📹 [How does a service worker work? - YouTube](https://www.youtube.com/watch?v=__xAtWgfzvc)

**[⬆ トップに戻ります](#table-of-contents)**

## サーバ

![サーバサイド]

- [ ] **ウェブサイトが HTTPS を使用していること:** ![high] 

    *理由:*
    > HTTPS は、 e コマースウェブサイトだけではなく、データをやりとりする全てのウェブサイト用です。データとは、ユーザが共有するデータ、または外部エンティティと共有するデータです。今時の最新ブラウザは安全でないサイトの機能を制限しています。例えば、インスタンスが HTTPS を使用していない場合、位置情報、プッシュ通知、および Service Worker は機能しません。また、現在は SSL 証明書を使用したプロジェクトのセットアップが、以前よりもはるかに簡単になりました。（そして、 [Let's Encrypt](https://letsencrypt.org/) のおかげで無料です。）

 * 📖 [Why Use HTTPS? | Cloudflare](https://www.cloudflare.com/learning/security/why-use-https/)
 * 📖 [Enabling HTTPS Without Sacrificing Your Web Performance - Moz](https://moz.com/blog/enabling-https-without-sacrificing-web-performance)
 * 📖 [How HTTPS Affects Website Performance](https://wp-rocket.me/blog/https-affects-website-performance/)
 * 📖 [HTTP versus HTTPS versus HTTP2 - The real story | Tune The Web](https://www.tunetheweb.com/blog/http-versus-https-versus-http2/)
 * 📖 [HTTP vs HTTPS — Test them both yourself](https://www.httpvshttps.com/)

- [ ] **ページ容量 < 1500 KB (理想的には < 500 KB):** ![high] ページとリソースのサイズをできるだけ減らす。

    *理由:*
    > 500 KB 未満を目標にするのが理想ですが、 Web の状態では、ページ容量の中央値が約 1500 KB （モバイルでも）であることが示されています。ターゲットユーザ、ネットワーク接続、デバイスに応じて、可能な限り総キロバイト数を減らすことで、可能な限り最高のユーザ体験を提供することができます。

    *方法:*
    > ⁃ フロントエンドパフォーマンスチェックリスト内の全てのルールは、リソースとコードを可能な限り削減するのに役立ちます。

    * 📖 [Page Weight](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [What Does My Site Cost?](https://whatdoesmysitecost.com/)
    * 🛠 [web - Measure full page size in Chrome DevTools - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **ページ読み込み時間 < 3 秒:** ![high] ページの読み込み時間を可能な限り短縮して、コンテンツを素早くユーザに配信する。

    *理由:*
    > ウェブサイトやアプリが高速であればあるほど、離脱を増加する可能性を減らし、ユーザや将来のクライアントを失う可能性を減らします。主題に関する十分な調査は、この点を証明します。

    *方法:*

    > [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) や [WebPageTest](https://www.webpagetest.org/) などのオンラインツールを使用して、何が遅くなるかを分析し、読み込み時間を短縮するために、フロントエンドパフォーマンスチェックリストを利用します。

    * 🛠 [Compare your mobile site speed](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Test Your Mobile Website Speed and Performance - Think With Google](https://testmysite.thinkwithgoogle.com/intl/en-us)
    * 📖 [Average Page Load Times for 2018 - How does yours compare? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **最初の情報を受信する待ち時間 < 1.3 秒:** ![high] データを受信する前に、ブラウザが待機する時間をできる限り減らします。

    * 📖 [What is Waiting (TTFB) in DevTools, and what to do about it](https://scaleyourcode.com/blog/article/27)
    * 📖 [Monitoring your servers with free tools is easy](https://scaleyourcode.com/blog/article/7)
    * 📖 [Time to First Byte (TTFB)](https://varvy.com/pagespeed/ttfb.html)
    * 🛠 [Global latency testing tool](https://latency.apex.sh)

* [ ] **クッキーサイズ:** ![medium] クッキーを利用しているのであれば、各クッキーが4096バイトを超えないようにし、ドメイン毎に20を超えるクッキーが無いようにしてください。

    *理由:*
    > クッキーは、ウェブサーバとブラウザ間で HTTP ヘッダでやりとりされます。ユーザの応答時間への影響を最小限に抑えるために、クッキーのサイズをできる限り小さくすることが重要です。

    *方法:*
    > 不要なクッキーを排除します。

    * 📖 [Cookie specification: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    * 🛠 [Browser Cookie Limits](http://browsercookielimits.squawky.net/)
    * 📖 [Website Performance: Cookies Don't Taste So Good - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Google's Web Performance Best Practices #3: Minimize Request Overhead - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **HTTP リクエストの最小化:** ![high] リクエストされている全てのファイルが、ウェブサイトまたはアプリケーションに不可欠であることを常に確認してください。
 * 📖 [Combine external CSS](https://varvy.com/pagespeed/combine-external-css.html)
 * 📖 [Combine external JavaScript](https://varvy.com/pagespeed/combine-external-javascript.html)

- [ ] **CDN を使用してアセットを配信:** ![medium] CDN を利用して、コンテンツをより速く世界中に配信します。

 * 📖 [10 Tips to Optimize CDN Performance - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [HTTP Caching  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **同じプロトコルからファイルを提供:** ![high] 例えば、 HTTPS を使用しているウェブサイトで、 HTTP を使用したソースからファイルを提供するウェブサイトを作成しないでください。ウェブサイトが HTTPS を使用している場合、外部ファイルは同じプロトコルから取得する必要があります。

- [ ] **到達可能なファイルを提供:** ![high] 到達不能なファイルへのリクエストを避けます（404）。
 * 📖 [How to avoid bad requests](https://varvy.com/pagespeed/avoid-bad-requests.html)

- [ ] **HTTP キャッシュヘッダを適切に設定:** ![high] HTTP ヘッダを設定して、ブラウザとサーバ間の往復コストを回避します。
 * 📖 [Using cache-control for browser caching](https://varvy.com/pagespeed/cache-control.html)

- [ ] **GZIP / Brotli 圧縮の有効化:** ![high] GZIP や Brotli などの圧縮方法を利用して、 JavaScript ファイルのサイズを小さくします。ファイルのサイズを小さくすると、ユーザはアセットをより速くダウンロードできるようになり、パフォーマンスが向上します。

 * 🛠 [Check GZIP compression](https://checkgzipcompression.com/)
 * 🛠 [Check Brotli Compression](https://tools.keycdn.com/brotli-test)
 * 📖 [Can I use... Brotli](https://caniuse.com/#feat=brotli)

**[⬆ トップに戻る](#table-of-contents)**

---
## Performances and JS Frameworks

### Angular
 * 📖 [Angular Performance Checklist](https://github.com/mgechev/angular-performance-checklist)

### React

 * 📖 [Optimizing Performance - React](https://reactjs.org/docs/optimizing-performance.html)
 * 📖 [React image manipulation | Cloudinary](https://cloudinary.com/documentation/react_image_manipulation)
 * 📖 [Debugging React performance with React 16 and Chrome Devtools.](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad)

### Vue
 * 📖 [Vue - Useful Links|Style Guide and Performance](https://learn-vuejs.github.io/vue-patterns/useful-links/)

## Performances and CMS

### WordPress

* 🛠 [Test Your Website Speed | WordPress Hosting by @WPEngine](https://wpengine.com/speed-tool/)

#### Articles

 * 📖 [19 Tips to Speed Up WordPress Performance (Updated)](https://www.wpbeginner.com/wordpress-performance-speed/)
 * 📖 [Speed Up Your WordPress - How to Save Images Optimized for Web](https://www.wpbeginner.com/beginners-guide/speed-wordpress-save-images-optimized-web/)

#### Plugins recommended

* 🛠 [Caching Plugin for WordPress - Speed up your website with WP Rocket](https://wp-rocket.me/)
* 🛠 [WP-Sweep | WordPress.org](https://wordpress.org/plugins/wp-sweep/)
* 🛠 [Imagify Image Optimizer | WordPress.org](https://wordpress.org/plugins/imagify/)

---

## Translations

The Front-End Performance Checklist wants to also be available in other languages! Don't hesitate to submit your contribution!

* 🇵🇹 Portuguese: [fernandofawkes/Front-End-Performance-Checklist](https://github.com/fernandofawkes/Front-End-Performance-Checklist)
* 🇨🇳 Chinese: [JohnsenZhou/Front-End-Performance-Checklist](https://github.com/JohnsenZhou/Front-End-Performance-Checklist)
* 🇷🇺 Russian: [lex111/Front-End-Performance-Checklist](https://github.com/lex111/Front-End-Performance-Checklist)
* 🇫🇷 French: [WilliamDASILVA/Front-End-Performance-Checklist](https://github.com/WilliamDASILVA/Front-End-Performance-Checklist)
* 🇰🇷 Korean: [ParkSB/Front-End-Performance-Checklist](https://github.com/ParkSB/Front-End-Performance-Checklist)
* 🇪🇸 Spanish: [dagerzuga/Front-End-Performance-Checklist](https://github.com/dagerzuga/Front-End-Performance-Checklist)
* 🇻🇮 Vietnamese : [huynhan147/Front-End-Performance-Checklist](https://github.com/huynhan147/FrontEnd-Performance-Checklist)

## Contributing

**Open an issue or a pull request to suggest changes or additions.**

## Support

If you have any question or suggestion, don't hesitate to use Discord or Twitter:

* [Chat on Discord](https://discord.gg/btHQRkm)
* [Facebook](https://www.facebook.com/frontendchecklist/)
* [Twitter](https://twitter.com/thedaviddias)

## Author

**Build with ❤️ by [David Dias](https://github.com/thedaviddias)

## Contributors

This project exists thanks to all the people who contribute. [[Contribute]](.github/CONTRIBUTING.md).
<a href="https://github.com/thedaviddias/Front-End-Performance-Checklist/graphs/contributors">
    <img src="https://opencollective.com/front-end-checklist/contributors.svg?width=890" />
</a>


## Backers

Thank you to all our backers! 🙏 [[Become a backer](https://opencollective.com/front-end-checklist#backer)]

<a href="https://opencollective.com/front-end-checklist#backers" target="_blank"><img src="https://opencollective.com/front-end-checklist/backers.svg?width=890"></a>


## Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website. [[Become a sponsor](https://opencollective.com/front-end-checklist#sponsor)]

<a href="https://opencollective.com/front-end-checklist/sponsor/0/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/1/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/2/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/3/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/4/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/5/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/6/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/7/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/8/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/9/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/9/avatar.svg"></a>

## License

[MIT](LICENSE)

All icons are provided by [Icons8](https://icons8.com/)

**[⬆ back to top](#table-of-contents)**

[logo]: images/logo-front-end-performance-checklist.jpg
[html]: images/html.png
[css]: images/css.png
[fonts]: images/fonts.png
[images]: images/images.png
[javascript]: images/javascript.png
[server-side]: images/server-side.png

[low]: https://front-end-checklist.now.sh/low.svg
[medium]: https://front-end-checklist.now.sh/medium.svg
[high]: https://front-end-checklist.now.sh/high.svg
