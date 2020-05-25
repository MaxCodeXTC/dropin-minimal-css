# Drop-in switcher for previewing minimal CSS frameworks

This is a quick drop-in CSS switcher to allow for previewing some of the many minimal CSS-only frameworks that are available. See the [demo](https://dohliam.github.io/dropin-minimal-css) or [drop the switcher](#usage) into your own page to see how [different frameworks](#list-of-frameworks) would look together with your content.

This project only includes _minimal_ frameworks, in other words, boilerplate / classless frameworks that require no adjustment of the corresponding HTML and can be simply dropped into the project to provide a starting point for further design. No additional javascript, compiling, pre-processors, or fiddling with classes should be required for these to look good and be responsive.

* [1 Usage](#usage)
  * [1.1 Keyboard shortcut](#keyboard-shortcut)
  * [1.2 Bookmarklet](#bookmarklet)
  * [1.3 API](#api)
* [2 Frameworks](#frameworks)
  * [2.1 Adding frameworks](#adding-frameworks)
  * [2.2 List of frameworks](#list-of-frameworks)
  * [2.3 Theme collections](#theme-collections)
* [3 See also](#see-also)
  * [3.1 Other similar collections](#other-similar-collections)
* [4 Acknowledgements](#acknowledgements)
* [5 License](#license)

## Usage

To use the CSS switcher, just add the following line anywhere within the body tag on your page:

```html
<script src="https://dohliam.github.io/dropin-minimal-css/switcher.js" type="text/javascript"></script>
```

That's it! You should now be able to cycle through the different frameworks by choosing them from the dropdown at the top of the page.

### Keyboard shortcut

You can quickly switch between frameworks by pressing the [modifier key or keys on your keyboard](https://github.com/dohliam/xsampa#access-keys) + `s` to focus the switcher dropdown menu, followed by the up and down keys to move up and down the list.

### Bookmarklet

The bookmarklet is a convenient way to preview how different CSS frameworks would look on any HTML page. Just paste the following code into your address bar to create a CSS switcher for any site:

```javascript
javascript:(function()%7Bvar%20body%20%3D%20document.getElementsByTagName('body')%5B0%5D%3Bscript%20%3D%20document.createElement('script')%3Bscript.type%3D%20'text%2Fjavascript'%3Bscript.src%3D%20'https%3A%2F%2Fdohliam.github.io%2Fdropin-minimal-css%2Fswitcher.js'%3Bbody.appendChild(script)%7D)()
```

Or alternatively, drag the link at the top of the [demo page](https://dohliam.github.io/dropin-minimal-css) to your browser's bookmark bar.

Boomarklet generated by the [Bookmarklet Creator](http://mrcoles.com/bookmarklet/). Thanks to [markdown-css](https://github.com/mrcoles/markdown-css) for the idea!

### API

There is a simple API available to allow linking directly to particular stylesheets on the demo page. For example:

https://dohliam.github.io/dropin-minimal-css/?sakura

The above links directly to the demo with [Sakura CSS](https://dohliam.github.io/dropin-minimal-css/?sakura).

## Frameworks

### Adding frameworks

If you know of a minimal framework that hasn't been included here, please create an [issue](https://github.com/dohliam/dropin-minimal-css/issues) or [pull request](https://github.com/dohliam/dropin-minimal-css/pulls) so that we can add it to the list!

### List of frameworks

* [a11yana](https://github.com/alexandersandberg/a11yana) by @alexandersandberg ([Preview](https://dohliam.github.io/dropin-minimal-css/?a11yana) · [MIT](https://github.com/alexandersandberg/a11yana/blob/master/LICENSE.md))
* [awsm](https://github.com/igoradamenko/awsm.css) by @igoradamenko ([Preview](https://dohliam.github.io/dropin-minimal-css/?awsm) · [MIT](https://github.com/igoradamenko/awsm.css/blob/master/LICENSE.md))
* [bahunya](https://github.com/Kimeiga/bahunya) by @Kimeiga ([Preview](https://dohliam.github.io/dropin-minimal-css/?bahunya) · [MIT](https://github.com/Kimeiga/bahunya/blob/master/LICENSE))
* [bare](https://github.com/longsien/BareCSS) by @longsien ([Preview](https://dohliam.github.io/dropin-minimal-css/?bare) · [MIT](https://github.com/longsien/BareCSS/blob/master/LICENSE))
* [base](https://github.com/matthewhartman/base) by @matthewhartman ([Preview](https://dohliam.github.io/dropin-minimal-css/?base) · [MIT](https://github.com/matthewhartman/base#license))
* [bullframe](https://github.com/marcop135/bullframe.css) by @marcop135 ([Preview](https://dohliam.github.io/dropin-minimal-css/?bullframe) · [MIT](https://github.com/marcop135/bullframe.css/blob/master/LICENSE.md))
* [bulma](https://github.com/jgthms/bulma) by @jgthms ([Preview](https://dohliam.github.io/dropin-minimal-css/?bulma) · [MIT](https://github.com/jgthms/bulma/blob/master/LICENSE))
* [caiuss](https://github.com/IonicaBizau/CaiuSS) by @IonicaBizau ([Preview](https://dohliam.github.io/dropin-minimal-css/?caiuss) · [MIT](https://github.com/IonicaBizau/CaiuSS/blob/master/LICENSE))
* [caramel](https://github.com/lumios/caramel) by @Lumios ([Preview](https://dohliam.github.io/dropin-minimal-css/?caramel) · [MIT](https://github.com/lumios/caramel/blob/master/LICENSE))
* [cardinal](https://github.com/cardinalcss/cardinalcss) by @cbracco ([Preview](https://dohliam.github.io/dropin-minimal-css/?cardinal) · [MIT](https://github.com/cardinalcss/cardinalcss/blob/master/LICENSE.md))
* [centurion](https://github.com/justinhough/Centurion) by @justinhough ([Preview](https://dohliam.github.io/dropin-minimal-css/?centurion) · [GPL](https://github.com/justinhough/Centurion/blob/master/LICENSE.md))
* [chota](https://github.com/jenil/chota) by @jenil ([Preview](https://dohliam.github.io/dropin-minimal-css/?chota) · [MIT](https://github.com/jenil/chota/blob/master/LICENSE))
* [cirrus](https://github.com/Spiderpig86/Cirrus) by @spiderpig86 ([Preview](https://dohliam.github.io/dropin-minimal-css/?cirrus) · [MIT](https://github.com/Spiderpig86/Cirrus/blob/master/LICENSE))
* [clmaterial](https://github.com/24aitor/CLMaterial) by @24aitor ([Preview](https://dohliam.github.io/dropin-minimal-css/?clmaterial) · [MIT](https://github.com/24aitor/CLMaterial/blob/master/LICENSE))
* [codify](https://github.com/zdroid/codify.css) by @zdroid ([Preview](https://dohliam.github.io/dropin-minimal-css/?codify) · [MIT](https://github.com/zdroid/codify.css/blob/master/LICENSE.md))
* [comet](https://github.com/marcbruederlin/comet) by @marcbruederlin ([Preview](https://dohliam.github.io/dropin-minimal-css/?comet) · [MIT](https://github.com/marcbruederlin/comet/blob/master/LICENSE))
* [concise](https://github.com/ConciseCSS/concise.css) by @ConciseCSS ([Preview](https://dohliam.github.io/dropin-minimal-css/?concise) · [MIT](https://github.com/ConciseCSS/concise.css/blob/master/LICENSE))
* [concrete](https://github.com/louismerlin/concrete.css) by @louismerlin ([Preview](https://dohliam.github.io/dropin-minimal-css/?concrete) · [MIT](https://github.com/louismerlin/concrete.css/blob/master/LICENSE))
* [cutestrap](https://github.com/tylerchilds/cutestrap) by @tylerchilds ([Preview](https://dohliam.github.io/dropin-minimal-css/?cutestrap) · [GPL](https://github.com/tylerchilds/cutestrap/blob/master/LICENSE))
* [flat-ui](https://github.com/designmodo/Flat-UI) by @Designmodo ([Preview](https://dohliam.github.io/dropin-minimal-css/?flat-ui) · [CC BY & MIT](https://github.com/designmodo/Flat-UI#copyright-and-license))
* [fluidity](https://github.com/mrmrs/fluidity) by @mrmrs ([Preview](https://dohliam.github.io/dropin-minimal-css/?fluidity) · [MIT](https://github.com/mrmrs/fluidity/blob/master/README.md))
* [furtive](https://github.com/johno/furtive) by @johno ([Preview](https://dohliam.github.io/dropin-minimal-css/?furtive) · [MIT](https://github.com/johno/furtive/blob/master/LICENSE))
* [generic](https://github.com/Vereis/generic.css) by @Vereis ([Preview](https://dohliam.github.io/dropin-minimal-css/?generic) · [MIT](https://github.com/Vereis/generic.css))
* [github-markdown](https://github.com/sindresorhus/github-markdown-css) by @sindresorhus ([Preview](https://dohliam.github.io/dropin-minimal-css/?github-markdown) · [MIT](https://github.com/sindresorhus/github-markdown-css/blob/gh-pages/license))
* [gutenberg](https://github.com/bafs/Gutenberg/) by @bafs ([Preview](https://dohliam.github.io/dropin-minimal-css/?gutenberg) · [MIT](https://github.com/BafS/Gutenberg/blob/master/LICENSE))
* [hack](https://github.com/egoist/hack) by @egoist ([Preview](https://dohliam.github.io/dropin-minimal-css/?hack) · [MIT](https://github.com/egoist/hack/blob/master/LICENSE))
* [hello](https://github.com/arp242/hello-css) by @arp242 ([Preview](https://dohliam.github.io/dropin-minimal-css/?hello) · [PD/ISC](https://github.com/arp242/hello-css))
* [hiq](https://github.com/jonathanharrell/hiq) by @jonathanharrell ([Preview](https://dohliam.github.io/dropin-minimal-css/?hiq) · [MIT](https://github.com/jonathanharrell/hiq/blob/master/license.md))
* [holiday](https://github.com/EvgenyOrekhov/holiday.css) by @EvgenyOrekhov ([Preview](https://dohliam.github.io/dropin-minimal-css/?holiday) · [MIT](https://github.com/EvgenyOrekhov/holiday.css/blob/master/LICENSE))
* [html-starterkit](https://github.com/zitrusfrisch/HTML-StarterKit) by @zitrusfrisch ([Preview](https://dohliam.github.io/dropin-minimal-css/?html-starterkit) · [MIT](https://github.com/zitrusfrisch/HTML-StarterKit#its-free))
* [hyp](https://github.com/krszwsk/hyp) by @krszwsk ([Preview](https://dohliam.github.io/dropin-minimal-css/?hyp) · [MIT](https://github.com/krszwsk/hyp/blob/master/LICENSE))
* [kathamo](https://github.com/kathamo/Kathamo) by @debashisbarman ([Preview](https://dohliam.github.io/dropin-minimal-css/?kathamo) · [MIT](https://github.com/kathamo/Kathamo/blob/master/LICENSE))
* [koochak](https://github.com/peyman3d/koochak) by @peyman3d ([Preview](https://dohliam.github.io/dropin-minimal-css/?koochak) · [MIT](https://github.com/peyman3d/koochak/blob/master/LICENSE))
* [kraken](https://github.com/cferdinandi/kraken) by @cferdinandi ([Preview](https://dohliam.github.io/dropin-minimal-css/?kraken) · [MIT](https://github.com/cferdinandi/kraken/blob/master/LICENSE.md))
* [kube](https://github.com/imperavi/kube) by @imperavi ([Preview](https://dohliam.github.io/dropin-minimal-css/?kube) · [MIT](https://github.com/imperavi/kube/blob/master/LICENSE))
* [latex](https://github.com/davidrzs/latexcss) by @davidrzs ([Preview](https://dohliam.github.io/dropin-minimal-css/?latex) · [MIT](https://github.com/davidrzs/latexcss/blob/master/LICENSE))
* [lemon](https://github.com/lucasarvelo/lemon) by @appalaszynski ([Preview](https://dohliam.github.io/dropin-minimal-css/?lemon) · [MIT](https://github.com/lucasarvelo/lemon/blob/master/LICENSE))
* [lit](https://github.com/Ajusa/lit) by @Ajusa ([Preview](https://dohliam.github.io/dropin-minimal-css/?lit) · [MIT](https://github.com/Ajusa/lit/blob/master/LICENSE))
* [lotus](https://github.com/goatslacker/lotus.css) by @goatslacker ([Preview](https://dohliam.github.io/dropin-minimal-css/?lotus) · [MIT](https://github.com/goatslacker/lotus.css#license))
* [markdown](https://github.com/mrcoles/markdown-css) by @mrcoles ([Preview](https://dohliam.github.io/dropin-minimal-css/?markdown) · [MIT](https://github.com/mrcoles/markdown-css/blob/master/license.txt))
* [marx](https://github.com/mblode/marx) by @mblode ([Preview](https://dohliam.github.io/dropin-minimal-css/?marx) · [MIT](https://github.com/mblode/marx/blob/master/LICENSE.md))
* [material](https://github.com/daemonite/material) by @daemonite ([Preview](https://dohliam.github.io/dropin-minimal-css/?material) · [MIT](https://github.com/Daemonite/material/blob/master/LICENSE))
* [materialize](https://github.com/Dogfalo/materialize) by @Dogfalo ([Preview](https://dohliam.github.io/dropin-minimal-css/?materialize) · [MIT](https://github.com/Dogfalo/materialize/blob/v1-dev/LICENSE))
* [mercury](https://github.com/wmeredith/MercuryCSS) by @wmeredith ([Preview](https://dohliam.github.io/dropin-minimal-css/?mercury) · [MIT](https://github.com/wmeredith/MercuryCSS/blob/master/LICENSE))
* [milligram](https://github.com/milligram/milligram) by @cjpatoilo ([Preview](https://dohliam.github.io/dropin-minimal-css/?milligram) · [MIT](http://cjpatoilo.mit-license.org/))
* [min](https://github.com/owenversteeg/min) by @owenversteeg ([Preview](https://dohliam.github.io/dropin-minimal-css/?min) · [MIT](https://github.com/owenversteeg/min#license))
* [mini](https://github.com/Chalarangelo/mini.css) by @Chalarangelo ([Preview](https://dohliam.github.io/dropin-minimal-css/?mini) · [MIT](https://github.com/Chalarangelo/mini.css/blob/master/LICENSE))
* [minimal](https://github.com/billyshall/minimalcss) by @billyshall ([Preview](https://dohliam.github.io/dropin-minimal-css/?minimal) · [MIT](https://github.com/billyshall/minimalcss/blob/master/license.txt))
* [minimal-stylesheet](https://github.com/chr15m/minimal-stylesheet) by @chr15m ([Preview](https://dohliam.github.io/dropin-minimal-css/?minimal-stylesheet) · [MIT](https://github.com/chr15m/minimal-stylesheet/blob/master/LICENSE))
* [mobi](https://github.com/mobi-css/mobi.css) by @xcatliu ([Preview](https://dohliam.github.io/dropin-minimal-css/?mobi) · [MIT](https://github.com/mobi-css/mobi.css/blob/master/LICENSE))
* [motherplate](https://github.com/leemunroe/motherplate) by @leemunroe ([Preview](https://dohliam.github.io/dropin-minimal-css/?motherplate) · [MIT](https://github.com/leemunroe/motherplate/blob/master/LICENSE))
* [mu](https://github.com/BafS/mu) by @BafS ([Preview](https://dohliam.github.io/dropin-minimal-css/?mu) · [MIT](https://github.com/BafS/mu/blob/gh-pages/LICENSE))
* [mui](https://github.com/muicss/mui) by @amorey ([Preview](https://dohliam.github.io/dropin-minimal-css/?mui) · [MIT](https://github.com/muicss/mui/blob/master/LICENSE.txt))
* [new](https://github.com/xz/new.css) by @3x ([Preview](https://dohliam.github.io/dropin-minimal-css/?new) · [MIT](https://github.com/xz/new.css/blob/master/LICENSE))
* [mvp](https://github.com/andybrewer/mvp) by @andybrewer ([Preview](https://dohliam.github.io/dropin-minimal-css/?mvp) · [MIT](https://github.com/andybrewer/mvp/blob/master/LICENSE))
* [no-class](https://github.com/davidpaulsson/no-class) by @davidpaulsson ([Preview](https://dohliam.github.io/dropin-minimal-css/?no-class) · [MIT](https://github.com/davidpaulsson/no-class/blob/master/LICENSE.txt))
* [normalize](https://github.com/necolas/normalize.css) by @necolas ([Preview](https://dohliam.github.io/dropin-minimal-css/?normalize) · [MIT](https://github.com/necolas/normalize.css/blob/master/LICENSE.md))
* [oh-my-css](https://github.com/egoist/oh-my-css) by @egoist ([Preview](https://dohliam.github.io/dropin-minimal-css/?oh-my-css) · [MIT](https://github.com/egoist/oh-my-css/blob/gh-pages/LICENSE))
* [paper](https://github.com/papercss/papercss) by @rhyneav ([Preview](https://dohliam.github.io/dropin-minimal-css/?paper) · [ISC](https://github.com/papercss/papercss/blob/master/license))
* [papier](https://github.com/alexanderGugel/papier) by @alexanderGugel ([Preview](https://dohliam.github.io/dropin-minimal-css/?papier) · [MIT](https://github.com/alexanderGugel/papier/blob/master/LICENSE.md))
* [pavilion](https://github.com/getpavilion/pavilion) by @getpavilion ([Preview](https://dohliam.github.io/dropin-minimal-css/?pavilion) · [MIT](https://github.com/getpavilion/pavilion/blob/master/license))
* [picnic](https://github.com/picnicss/picnic) by @FranciscoP ([Preview](https://dohliam.github.io/dropin-minimal-css/?picnic) · [MIT](https://github.com/picnicss/picnic/blob/master/LICENSE))
* [preface](https://github.com/cluzier/PrefaceCSS) by @cluzier ([Preview](https://dohliam.github.io/dropin-minimal-css/?preface) · [MIT](https://github.com/cluzier/PrefaceCSS/blob/master/LICENSE))
* [primer](https://github.com/primer/css) by @primer ([Preview](https://dohliam.github.io/dropin-minimal-css/?primer) · [MIT](https://github.com/primer/css/blob/master/LICENSE))
* [propeller](https://github.com/digicorp/propeller) by @digicorp ([Preview](https://dohliam.github.io/dropin-minimal-css/?propeller) · [MIT](https://github.com/digicorp/propeller/blob/master/LICENSE))
* [pure](https://github.com/yahoo/pure/) by @yahoo ([Preview](https://dohliam.github.io/dropin-minimal-css/?pure) · [BSD](https://github.com/yahoo/pure/blob/master/LICENSE.md))
* [roble](https://gitlab.com/violapeter/roble) by @violapeter ([Preview](https://dohliam.github.io/dropin-minimal-css/?roble) · [MIT](https://gitlab.com/violapeter/roble/-/blob/master/package.json))
* [sakura](https://github.com/oxalorg/sakura) by @oxalorg ([Preview](https://dohliam.github.io/dropin-minimal-css/?sakura) · [MIT](https://github.com/oxalorg/sakura/blob/master/LICENSE.txt))
* [sanitize](https://github.com/csstools/sanitize.css) by @csstools ([Preview](https://dohliam.github.io/dropin-minimal-css/?sanitize) · [CC0](https://github.com/csstools/sanitize.css/blob/master/LICENSE.md))
* [scooter](https://github.com/dropbox/scooter) by @dropbox ([Preview](https://dohliam.github.io/dropin-minimal-css/?scooter) · [Apache](https://github.com/dropbox/scooter/blob/master/LICENSE.md))
* [semantic-ui](https://github.com/Semantic-Org/Semantic-UI) by @Semantic-Org ([Preview](https://dohliam.github.io/dropin-minimal-css/?semantic-ui) · [MIT](https://github.com/Semantic-Org/Semantic-UI/blob/master/LICENSE.md))
* [shoelace](https://github.com/claviska/shoelace-css) by @claviska ([Preview](https://dohliam.github.io/dropin-minimal-css/?shoelace) · [MIT](https://github.com/claviska/shoelace-css/blob/master/LICENSE.md))
* [siimple](https://github.com/siimple/siimple) by @jmjuanes ([Preview](https://dohliam.github.io/dropin-minimal-css/?siimple) · [MIT](https://github.com/siimple/siimple/blob/develop/LICENSE))
* [simple](https://github.com/tukangslicing/simplecss) by @neculaesei ([Preview](https://dohliam.github.io/dropin-minimal-css/?simple) · [MIT](https://opensource.org/licenses/mit-license.php))
* [skeleton](https://github.com/dhg/Skeleton) by @dhg ([Preview](https://dohliam.github.io/dropin-minimal-css/?skeleton) · [MIT](https://github.com/dhg/Skeleton/blob/master/LICENSE.md))
* [skeleton-framework](https://github.com/skeleton-framework/skeleton-framework) by @skeleton-framework ([Preview](https://dohliam.github.io/dropin-minimal-css/?skeleton-framework) · [MIT](https://github.com/skeleton-framework/skeleton-framework/blob/master/LICENSE))
* [skeleton-plus](https://github.com/oltdaniel/skeleton-plus) by @oltdaniel ([Preview](https://dohliam.github.io/dropin-minimal-css/?skeleton-plus) · [MIT](https://github.com/oltdaniel/skeleton-plus/blob/master/LICENSE))
* [snack](https://github.com/snack-ui/snack) by @nzbin ([Preview](https://dohliam.github.io/dropin-minimal-css/?snack) · [MIT](https://github.com/snack-ui/snack/blob/master/LICENSE))
* [spectre](https://github.com/picturepan2/spectre) by @picturepan2 ([Preview](https://dohliam.github.io/dropin-minimal-css/?spectre) · [MIT](https://github.com/picturepan2/spectre/blob/master/LICENSE))
* [style](https://github.com/ungoldman/style.css) by @ungoldman ([Preview](https://dohliam.github.io/dropin-minimal-css/?style) · [ISC](https://github.com/ungoldman/style.css/blob/master/license.md))
* [stylize](https://github.com/vasanthv/stylize.css) by @vasanthv ([Preview](https://dohliam.github.io/dropin-minimal-css/?stylize) · [MIT](https://github.com/vasanthv/stylize.css/blob/master/LICENSE))
* [tachyons](https://github.com/tachyons-css/tachyons/) by @tachyons-css ([Preview](https://dohliam.github.io/dropin-minimal-css/?tachyons) · [MIT](https://github.com/tachyons-css/tachyons/blob/master/license))
* [tacit](https://github.com/yegor256/tacit) by @yegor256 ([Preview](https://dohliam.github.io/dropin-minimal-css/?tacit) · [MIT](https://github.com/yegor256/tacit/blob/master/LICENSE))
* [tent](https://github.com/sitetent/tentcss) by @ulinaaron ([Preview](https://dohliam.github.io/dropin-minimal-css/?tent) · [MIT](https://github.com/sitetent/tentcss/blob/master/LICENSE))
* [thao](https://github.com/ThaoFramework/Thao/) by @Sanfra1407 ([Preview](https://dohliam.github.io/dropin-minimal-css/?thao) · [Apache](http://www.apache.org/licenses/LICENSE-2.0))
* [vanilla](https://github.com/bradleytaunt/vanilla-css) by @bradleytaunt ([Preview](https://dohliam.github.io/dropin-minimal-css/?vanilla) · [MIT](https://github.com/bradleytaunt/vanilla-css/blob/master/LICENSE))
* [vital](https://github.com/doximity/vital) by @doximity ([Preview](https://dohliam.github.io/dropin-minimal-css/?vital) · [Apache](https://github.com/doximity/vital/blob/master/LICENSE.md))
* [water](https://github.com/kognise/water.css) by @kognise ([Preview](https://dohliam.github.io/dropin-minimal-css/?water) · [MIT](https://github.com/kognise/water.css/blob/master/LICENSE.md))
* [wing](https://github.com/KingPixil/wing/) by @KingPixil ([Preview](https://dohliam.github.io/dropin-minimal-css/?wing) · [MIT](https://github.com/KingPixil/wing/blob/master/LICENSE))
* [writ](https://github.com/programble/writ) by @causal-agent ([Preview](https://dohliam.github.io/dropin-minimal-css/?writ) · [ISC](https://github.com/programble/writ/blob/master/LICENSE))
* [yamb](https://github.com/runxel/yamb-css) by @runxel ([Preview](https://dohliam.github.io/dropin-minimal-css/?yamb) · [Blue Oak](https://github.com/runxel/yamb-css/blob/master/LICENSE.md))
* [yorha](https://github.com/metakirby5/yorha) by @metakirby5 ([Preview](https://dohliam.github.io/dropin-minimal-css/?yorha) · [MIT](https://github.com/metakirby5/yorha/blob/master/LICENSE))

### Theme collections

* **[asciidoctor-skins](https://github.com/https://github.com/darshandsoni/asciidoctor-skins)** by @darshandsoni:
  * [ads-gazette](https://github.com/darshandsoni/asciidoctor-skins) by @darshandsoni ([Preview](https://dohliam.github.io/dropin-minimal-css/?ads-gazette) · [MIT](https://github.com/darshandsoni/asciidoctor-skins/blob/gh-pages/LICENSE))
  * [ads-medium](https://github.com/darshandsoni/asciidoctor-skins) by @darshandsoni ([Preview](https://dohliam.github.io/dropin-minimal-css/?ads-medium) · [MIT](https://github.com/darshandsoni/asciidoctor-skins/blob/gh-pages/LICENSE))
  * [ads-notebook](https://github.com/darshandsoni/asciidoctor-skins) by @darshandsoni ([Preview](https://dohliam.github.io/dropin-minimal-css/?ads-notebook) · [MIT](https://github.com/darshandsoni/asciidoctor-skins/blob/gh-pages/LICENSE))
  * [ads-tufte](https://github.com/darshandsoni/asciidoctor-skins) by @darshandsoni ([Preview](https://dohliam.github.io/dropin-minimal-css/?ads-tufte) · [MIT](https://github.com/darshandsoni/asciidoctor-skins/blob/gh-pages/LICENSE))
* **[bootswatch](https://github.com/https://github.com/thomaspark/bootswatch)** by @thomaspark:
  * [boot-cerulean](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-cerulean) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-cosmo](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-cosmo) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-cyborg](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-cyborg) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-darkly](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-darkly) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-flatly](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-flatly) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-journal](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-journal) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-lumen](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-lumen) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-paper](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-paper) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-readable](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-readable) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-sandstone](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-sandstone) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-slate](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-slate) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-spacelab](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-spacelab) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-superhero](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-superhero) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
  * [boot-yeti](https://github.com/thomaspark/bootswatch) by @thomaspark ([Preview](https://dohliam.github.io/dropin-minimal-css/?boot-yeti) · [MIT](https://github.com/thomaspark/bootswatch/blob/gh-pages/LICENSE))
* **[markdowncss](https://github.com/https://github.com/markdowncss)** by @johnotander:
  * [md-air](https://github.com/markdowncss/air) by @johnotander ([Preview](https://dohliam.github.io/dropin-minimal-css/?md-air) · [MIT](https://github.com/markdowncss/air/blob/master/LICENSE))
  * [md-modest](https://github.com/markdowncss/modest) by @johnotander ([Preview](https://dohliam.github.io/dropin-minimal-css/?md-modest) · [MIT](https://github.com/markdowncss/modest/blob/master/LICENSE))
  * [md-retro](https://github.com/markdowncss/retro) by @johnotander ([Preview](https://dohliam.github.io/dropin-minimal-css/?md-retro) · [MIT](https://github.com/markdowncss/retro/blob/master/LICENSE))
  * [md-splendor](https://github.com/markdowncss/splendor) by @johnotander ([Preview](https://dohliam.github.io/dropin-minimal-css/?md-splendor) · [MIT](https://github.com/markdowncss/splendor/blob/master/LICENSE))
* **[w3c-core](https://github.com/https://www.w3.org/StyleSheets/Core/)** by @Bert Bos:
  * [w3c-chocolate](https://www.w3.org/StyleSheets/Core/) by @Bert Bos ([Preview](https://dohliam.github.io/dropin-minimal-css/?w3c-chocolate) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-midnight](https://www.w3.org/StyleSheets/Core/) by @Bert Bos ([Preview](https://dohliam.github.io/dropin-minimal-css/?w3c-midnight) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-modernist](https://www.w3.org/StyleSheets/Core/) by @Bert Bos ([Preview](https://dohliam.github.io/dropin-minimal-css/?w3c-modernist) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-oldstyle](https://www.w3.org/StyleSheets/Core/) by @Bert Bos ([Preview](https://dohliam.github.io/dropin-minimal-css/?w3c-oldstyle) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-steely](https://www.w3.org/StyleSheets/Core/) by @Bert Bos ([Preview](https://dohliam.github.io/dropin-minimal-css/?w3c-steely) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-swiss](https://www.w3.org/StyleSheets/Core/) by @Bert Bos ([Preview](https://dohliam.github.io/dropin-minimal-css/?w3c-swiss) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-traditional](https://www.w3.org/StyleSheets/Core/) by @Bert Bos ([Preview](https://dohliam.github.io/dropin-minimal-css/?w3c-traditional) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))
  * [w3c-ultramarine](https://www.w3.org/StyleSheets/Core/) by @Bert Bos ([Preview](https://dohliam.github.io/dropin-minimal-css/?w3c-ultramarine) · [W3C](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document))

## See also

* [workflow](https://github.com/dohliam/workflow) - Quick prototyping script for creating rich html and pdfs from markdown documents (based on dropin-minimal-css)
* [asciidoctor-skins](https://github.com/darshandsoni/asciidoctor-skins) - CSS stylesheets for asciidoctor (with a switcher based on dropin-minimal-css)

### Other similar collections

* [CSS Bed](https://github.com/ubershmekel/cssbed) by @ubershmekel
* [classless-css](https://github.com/dbohdan/classless-css) by @dbohdan
* [cleanrmd](https://github.com/gadenbuie/cleanrmd) by @gadenbuie
* [awesome-css-frameworks](https://github.com/troxler/awesome-css-frameworks) by @troxler

## Acknowledgements

* Sample HTML5 markup based on [html5-test-page](https://github.com/cbracco/html5-test-page) by @cbracco (MIT)
* Example images in the demo are by [MichaelMaggs](https://commons.wikimedia.org/wiki/User:MichaelMaggs) on [Wikimedia Commons](https://commons.wikimedia.org)
* Example videos provided by the [Blender Foundation](https://peach.blender.org/) via the [HTML5-Test-Videos](https://github.com/benhosmer/HTML5-Test-Videos) project
* Embedded audio [Night Owl](https://freemusicarchive.org/music/Broke_For_Free/Directionless_EP/Broke_For_Free_-_Directionless_EP_-_01_Night_Owl) by [Broke For Free](https://freemusicarchive.org/music/Broke_For_Free) at the [Free Music Archive](https://freemusicarchive.org/)
* Special thanks to [Tacit CSS](https://github.com/yegor256/tacit), which was the original inspiration for making this list to answer the question "Where can I find more frameworks like Tacit?"
* Table of contents made with [tocdown](https://github.com/dohliam/tocdown)

## License

MIT.
