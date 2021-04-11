<!DOCTYPE html>
<!-- saved from url=(0030)https://markdown-it.github.io/ -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    <title>markdown-it demo</title>
    
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <script type="text/javascript" async="" src="./README_files/linkid.js.download"></script><script async="" src="./README_files/analytics.js.download"></script><script src="./README_files/es5-shim.min.js.download"></script>
    <script src="./README_files/jquery.min.js.download"></script>
    <script src="./README_files/lodash.js.download"></script>
    <script src="./README_files/bootstrap.min.js.download"></script>
    <link rel="stylesheet" href="./README_files/bootstrap.css">
    <link rel="stylesheet" href="./README_files/github.min.css">
    <script src="./README_files/markdown-it.js.download"></script>
    <script src="./README_files/twemoji.min.js.download"></script>
    <link rel="stylesheet" href="./README_files/index.css">
    <script src="./README_files/index.js.download"></script>
    <!-- Ancient IE support - load shiv & kill broken highlighter--><!--[if lt IE 9]>
<script src="https://oss.maxcdn.com/html5shiv/3.7.2/html5shiv.min.js"></script>
<script>window.hljs = null;</script>
<![endif]-->
    <!-- GA counter-->
    <script>
      (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
      (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
      m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
      })(window,document,'script','//www.google-analytics.com/analytics.js','ga');
      
      ga('create', 'UA-26895916-4', 'auto');
      ga('require', 'displayfeatures');
      ga('require', 'linkid', 'linkid.js');
      ga('send', 'pageview');
      
    </script>
  </head>
  <body class="opt_linkify opt_typographer opt__highlight result-as-html" data-new-gr-c-s-check-loaded="14.1005.0" data-gr-ext-installed="" data-new-gr-c-s-loaded="14.1005.0">
    <div class="container">
      <h1>
        markdown-it <small>demo</small></h1>
      <div class="form-inline demo-options">
        <div class="checkbox not-strict">
          <label class="_tip" title="" data-original-title="enable html tags in source text">
            <input id="html" type="checkbox"> html
          </label>
        </div>
        <div class="checkbox not-strict">
          <label class="_tip" title="" data-original-title="produce xtml output (add / to single tags (&lt;br /&gt; instead of &lt;br&gt;)">
            <input id="xhtmlOut" type="checkbox"> xhtmlOut
          </label>
        </div>
        <div class="checkbox not-strict">
          <label class="_tip" title="" data-original-title="newlines in paragraphs are rendered as &lt;br&gt;">
            <input id="breaks" type="checkbox"> breaks
          </label>
        </div>
        <div class="checkbox not-strict">
          <label class="_tip" title="" data-original-title="autoconvert link-like texts to links">
            <input id="linkify" type="checkbox"> linkify
          </label>
        </div>
        <div class="checkbox not-strict">
          <label class="_tip" title="" data-original-title="do typographic replacements, (c) → © and so on">
            <input id="typographer" type="checkbox"> typographer
          </label>
        </div>
        <div class="checkbox not-strict">
          <label class="_tip" title="" data-original-title="enable output highlight for fenced blocks">
            <input id="_highlight" type="checkbox"> highlight
          </label>
        </div>
        <div class="form-group not-strict">
          <input class="form-control _tip" id="langPrefix" type="input" placeholder="language prefix" title="" data-original-title="css class language prefix for fenced code blocks">
        </div>
        <div class="checkbox">
          <label class="_tip" title="" data-original-title="force strict CommonMark mode - output will be equal to reference parser">
            <input id="_strict" type="checkbox"> CommonMark strict
          </label>
        </div>
      </div>
    </div>
    <div class="container full-height">
      <div class="row full-height">
        <div class="col-xs-6 full-height"><grammarly-extension data-grammarly-shadow-root="true" class="cGcvT" style="position: absolute; top: 0px; left: 0px; pointer-events: none;"></grammarly-extension>
          <div class="demo-control"><a class="source-clear" href="https://markdown-it.github.io/#">clear</a><a id="permalink" href="https://markdown-it.github.io/#md3=%7B%22source%22%3A%22---%5Cn!%5BMyntra%5D%28https%3A%2F%2Fimages.assettype.com%2Fafaqs%2Fimport%2Fall%2Fnews%2Fimages%2Fnews_story_grfx%2F2015%2F10%2F45950%2FMyntra-logo.jpg%29%5Cn%23%20Real%20Time%20Virtual_Shopping%5Cn!%5BSymbol%5D%28https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.nDJfNTlB_fpn99UmdqC11gHaFO%26pid%3DApi%26P%3D0%26w%3D251%26h%3D178%29%5Cn%5Cn%23%23%23%20%5BColab%20Link%5D%28https%3A%2F%2Fcolab.research.google.com%2Fdrive%2F1NlLnc1tkkRG3ifGo6NYaUd8jFsPKUH3U%23scrollTo%3DhiHMVbnhpX7g%29%5Cn---%5Cn%5Cn%23%23%20%2A%2AProject%20Description%2A%2A%3A%5Cn%5Cn%23%23%23%20Project%20Has%20been%20Divided%20In%20Two-Phase%5Cn%5Cn___%5Cn%23%23%23%20Stage%201%3A%20%5Cn%3E1.Nevigation%20at%20home%20page%5Cn%5Cn%3E2.%2A%2AFeature%20Extraction%2A%2A%5Bwhere%20User%20Can%20Extract%2Fask%20for%20similar%20pattern%20under%20their%20specification%5D%5Cn%5Cn%3E3.%2A%2AFace%20On%20Trial%2A%2A%20where%20user%20can%20take%20trial%20using%20their%20camera%20%26%20cloth%20they%20select%5Cn%5Cn---%5Cn%23%23%23%20Stage%202%3A%5Cn%3E1.%2A%2A3D%20model%20Creation%2A%2A%20%5Busing%20PIFuHD%20Model%5D%5Cn%5Cn%3E2.%2A%2ARendering%20of%203D%20model%2A%2A%20into%20human%20model%20and%20size%2Fmeasurement%20extraction%5Busing%20Unity%20%26%20Blender%5D%5Cn%5Cn%3E3.Providing%20%2A%2AVirtual%20Trial%20Room%2A%2A%20Feature%20to%20the%20user%20to%20try%20on%20the%20cloth%5Cn%5Cn%3E%3Ei%29%20if%20the%20size%20measurement%20of%20the%20person%20and%20cloth%20matches%2C%20the%20trial%20model%20will%20be%20generated.%20otherwise%2C%20it%20will%20show%20%5C%22size%20not%20matched%5C%22%2C%20ask%20the%20user%20to%20change%20selected%20clothes.%5Cn%5Cn%3E%3Eii%29once%20the%20Trial%20will%20be%20Done%20user%20can%20share%2Fdownload%20their%20trial%20model.%5Cn%20%5Cn%2A%2A%2A%5Cn%5Cn%23%23%20Research%20Paper%20Link%3A%5Cn%5Cn_%5BFace%20on%20Trail%5D%28http%3A%2F%2Falereimondo.no-ip.org%2FOpenCV%2Fuploads%2F37%2FCameraReadyPaper63.pdf%29%5Cn%5Cn_%5BPIFuHD%20Paper%5D%28https%3A%2F%2Farxiv.org%2Fpdf%2F2004.00452.pdf%29%5Cn%5Cn_%5BVTON%20Model%5D%28https%3A%2F%2Fminar09.github.io%2Fc3dvton%2Fcvprw20_3d.pdf%29%5Cn%5Cn%22%2C%22defaults%22%3A%7B%22html%22%3Afalse%2C%22xhtmlOut%22%3Afalse%2C%22breaks%22%3Afalse%2C%22langPrefix%22%3A%22language-%22%2C%22linkify%22%3Atrue%2C%22typographer%22%3Atrue%2C%22_highlight%22%3Atrue%2C%22_strict%22%3Afalse%2C%22_view%22%3A%22html%22%7D%7D" title="Share this snippet as link"><strong>permalink</strong></a></div>
          <textarea class="source full-height" spellcheck="false">---
__Advertisement :)__

- __[pica](https://nodeca.github.io/pica/demo/)__ - high quality and fast image
  resize in browser.
- __[babelfish](https://github.com/nodeca/babelfish/)__ - developer friendly
  i18n with plurals support and easy syntax.

You will like those projects!

---

# h1 Heading 8-)
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## Horizontal Rules

___

---

***


## Typographic replacements

Enable typographer option to see result.

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


&gt; Blockquotes can also be nested...
&gt;&gt; ...by using additional greater-than signs right next to each other...
&gt; &gt; &gt; ...or with spaces between arrows.


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)


## Images

![Minion](https://octodex.github.com/images/minion.png)
![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

Like links, Images also have a footnote style syntax

![Alt text][id]

With a reference later in the document defining the URL location:

[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"


## Plugins

The killer feature of `markdown-it` is very effective support of
[syntax plugins](https://www.npmjs.org/browse/keyword/markdown-it-plugin).


### [Emojies](https://github.com/markdown-it/markdown-it-emoji)

&gt; Classic markup: :wink: :crush: :cry: :tear: :laughing: :yum:
&gt;
&gt; Shortcuts (emoticons): :-) :-( 8-) ;)

see [how to change output](https://github.com/markdown-it/markdown-it-emoji#change-output) with twemoji.


### [Subscript](https://github.com/markdown-it/markdown-it-sub) / [Superscript](https://github.com/markdown-it/markdown-it-sup)

- 19^th^
- H~2~O


### [\&lt;ins&gt;](https://github.com/markdown-it/markdown-it-ins)

++Inserted text++


### [\&lt;mark&gt;](https://github.com/markdown-it/markdown-it-mark)

==Marked text==


### [Footnotes](https://github.com/markdown-it/markdown-it-footnote)

Footnote 1 link[^first].

Footnote 2 link[^second].

Inline footnote^[Text of inline footnote] definition.

Duplicated footnote reference[^second].

[^first]: Footnote **can have markup**

    and multiple paragraphs.

[^second]: Footnote text.


### [Definition lists](https://github.com/markdown-it/markdown-it-deflist)

Term 1

:   Definition 1
with lazy continuation.

Term 2 with *inline markup*

:   Definition 2

        { some code, part of Definition 2 }

    Third paragraph of definition 2.

_Compact style:_

Term 1
  ~ Definition 1

Term 2
  ~ Definition 2a
  ~ Definition 2b


### [Abbreviations](https://github.com/markdown-it/markdown-it-abbr)

This is HTML abbreviation example.

It converts "HTML", but keep intact partial entries like "xxxHTMLyyy" and so on.

*[HTML]: Hyper Text Markup Language

### [Custom containers](https://github.com/markdown-it/markdown-it-container)

::: warning
*here be dragons*
:::
</textarea>
        </div>
        <section class="col-xs-6 full-height">
          <div class="demo-control"><a href="https://markdown-it.github.io/#" data-result-as="html">html</a><a href="https://markdown-it.github.io/#" data-result-as="src">source</a><a href="https://markdown-it.github.io/#" data-result-as="debug">debug</a></div>
          <div class="result-html full-height"><hr>
<p class="line" data-line="1"><img src="./README_files/Myntra-logo.jpg" alt="Myntra"></p>
<h1 class="line" data-line="2">Real Time Virtual_Shopping</h1>
<p class="line" data-line="3"><img src="./README_files/th" alt="Symbol"></p>
<h3 class="line" data-line="5"><a href="https://colab.research.google.com/drive/1NlLnc1tkkRG3ifGo6NYaUd8jFsPKUH3U#scrollTo=hiHMVbnhpX7g">Colab Link</a></h3>
<hr>
<h2 class="line" data-line="8"><strong>Project Description</strong>:</h2>
<h3 class="line" data-line="10">Project Has been Divided In Two-Phase</h3>
<hr>
<h3 class="line" data-line="13">Stage 1:</h3>
<blockquote>
<p>1.Nevigation at home page</p>
</blockquote>
<blockquote>
<p>2.<strong>Feature Extraction</strong>[where User Can Extract/ask for similar pattern under their specification]</p>
</blockquote>
<blockquote>
<p>3.<strong>Face On Trial</strong> where user can take trial using their camera &amp; cloth they select</p>
</blockquote>
<hr>
<h3 class="line" data-line="21">Stage 2:</h3>
<blockquote>
<p>1.<strong>3D model Creation</strong> [using PIFuHD Model]</p>
</blockquote>
<blockquote>
<p>2.<strong>Rendering of 3D model</strong> into human model and size/measurement extraction[using Unity &amp; Blender]</p>
</blockquote>
<blockquote>
<p>3.Providing <strong>Virtual Trial Room</strong> Feature to the user to try on the cloth</p>
</blockquote>
<blockquote>
<blockquote>
<p>i) if the size measurement of the person and cloth matches, the trial model will be generated. otherwise, it will show “size not matched”, ask the user to change selected clothes.</p>
</blockquote>
</blockquote>
<blockquote>
<blockquote>
<p>ii)once the Trial will be Done user can share/download their trial model.</p>
</blockquote>
</blockquote>
<hr>
<h2 class="line" data-line="34">Research Paper Link:</h2>
<p class="line" data-line="36">_<a href="http://alereimondo.no-ip.org/OpenCV/uploads/37/CameraReadyPaper63.pdf">Face on Trail</a></p>
<p class="line" data-line="38">_<a href="https://arxiv.org/pdf/2004.00452.pdf">PIFuHD Paper</a></p>
<p class="line" data-line="40">_<a href="https://minar09.github.io/c3dvton/cvprw20_3d.pdf">VTON Model</a></p>
</div>
          <pre class="hljs result-src full-height"><code class="result-src-content full-height"></code></pre>
          <pre class="hljs result-debug full-height"><code class="result-debug-content full-height"></code></pre>
        </section>
      </div>
    </div>
    <div class="gh-ribbon"><a href="https://github.com/markdown-it/markdown-it" target="_blank">Fork me on GitHub</a></div>
  
</body><div id="vimeo-screen-recorder-container"></div><grammarly-mirror data-grammarly-shadow-root="true" class="cGcvT"></grammarly-mirror></html>