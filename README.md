# CSS snippets for UltiSnips.vim
**Style faster.**

My collection of CSS snippets lets you type CSS faster. Just use these on a
Vim+UltiSnips setup and you can type *abbreviations* of declarations to expand
to full CSS like so:

```
db<tab>
m0<tab>
fl<tab>
```

To become:

``` css
display: block;
margin: 0;
float: left;
```

See [this list][list] for a full list of snippets.

Installation
------------

 * [Vim](http://www.vim.org)
 * [UltiSnips](https://github.com/SirVer/ultisnips)
 * [Pathogen](https://github.com/tpope/vim-pathogen) or [Vundle](http://github.com/gmarik/vundle) (optional but recommended)

Add to your .vimrc:

    Bundle 'SirVer/ultisnips'
    Bundle 'rstacruz/vim-ultisnips-css'

Reference
---------

<!-- reference start -->
| Snippet | Description |
| ---- | ---- |
| **@desktop** | `@media (min-width: 1201px) /* desktop */` |
| **@laptop** | `@media (min-width: 993px) /* laptop */` |
| **@mobile** | `@media (max-width: 992px) /* mobile */` |
| **@nondesktop** | `@media (max-width: 1200px) /* phone, tablet, laptop */` |
| **@phone** | `@media (max-width: 768px) /* phone */` |
| **@portrait** | `@media (max-width: 480px) /* portrait */` |
| **@tablet** | `@media (min-width: 769px) /* tablet, desktop */` |
| **an** | `animation: {name} {300ms linear infinite};` |
| **b** | `border: {solid 1px #333};` |
| **b0** | `border: 0;` |
| **bb** | `border-bottom: {solid 1px #333};` |
| **bb0** | `border-bottom: 0;` |
| **bblrad** | `border-bottom-left-radius: {3px};` |
| **bbrad** | `border-bottom-radius: {3px};` |
| **bbrrad** | `border-bottom-right-radius: {3px};` |
| **bcc** | `border-collapse: collapse;` |
| **bg** | `background: {#fff url(image.png) no-repeat left top fixed};` |
| **bga** | `background-attachment: {scroll|fixed|local};` |
| **bgaf** | `background-attachment: fixed;` |
| **bgal** | `background-attachment: local;` |
| **bgas** | `background-attachment: scroll;` |
| **bgc** | `background-color: {transparent};` |
| **bgclip** | `background-clip: padding-box;` |
| **bgi** | `background-image: {url()};` |
| **bgp** | `background-position: {x y};` |
| **bgr** | `background-repeat: {no-repeat};` |
| **bl** | `border-left: {solid 1px #333};` |
| **bl0** | `border-left: 0;` |
| **bold** | `font-weight: bold;` |
| **br** | `border-right: {solid 1px #333};` |
| **br0** | `border-right: 0;` |
| **brad** | `border-radius: {3px};` |
| **bs** | `box-shadow: {0 1px 2px #fff};` |
| **bsb** | `box-sizing: border-box;` |
| **bsp** | `box-sizing: padding-box;` |
| **bt** | `border-top: {solid 1px #333};` |
| **bt0** | `border-top: 0;` |
| **btlrad** | `border-top-left-radius: {3px};` |
| **btrad** | `border-top-radius: {3px};` |
| **btrrad** | `border-top-right-radius: {3px};` |
| **cb** | `clear: both;` |
| **cd** | `cursor: default;` |
| **cf** | `+clearfix` |
| **cf** | `clearfix()` |
| **cl** | `clear: left;` |
| **co** | `color: {#333};` |
| **cp** | `cursor: pointer;` |
| **cr** | `clear: right;` |
| **ct** | `cursor: text;` |
| **cu** | `cursor: {default|pointer|text};` |
| **cud** | `cursor: default;` |
| **cuew** | `cursor: ew-resize;` |
| **cuna** | `cursor: not-allowed;` |
| **cuns** | `cursor: ns-resize;` |
| **cup** | `cursor: pointer;` |
| **cut** | `cursor: text;` |
| **d** | `display: {none|inline|block};` |
| **db** | `display: block;` |
| **di** | `display: inline;` |
| **dib** | `display: inline-block;` |
| **dn** | `display: none;` |
| **dt** | `display: table;` |
| **dtc** | `display: table-cell;` |
| **dtr** | `display: table-row;` |
| **f** | `font: {italic bold 1em/1.5em serif};` |
| **ff** | `font-family: {sans-serif};` |
| **fl** | `float: left;` |
| **fn** | `float: none;` |
| **font** | `font: {italic bold 1em/1.5em serif};` |
| **fr** | `float: right;` |
| **fs** | `font-size: {1em};` |
| **fsi** | `font-style: italic;` |
| **fsn** | `font-style: normal;` |
| **fw1** | `font-weight: 100;` |
| **fw3** | `font-weight: 300;` |
| **fw5** | `font-weight: 500;` |
| **fw7** | `font-weight: 700;` |
| **fw9** | `font-weight: 900;` |
| **fwb** | `font-weight: bold;` |
| **fwn** | `font-weight: normal;` |
| **h** | `height: {0};` |
| **hlh** | `height: {0px}; line-height: {1.5};` |
| **italic** | `font-style: italic;` |
| **l** | `left: {0};` |
| **lb** | `left: {0}; bottom: {0};` |
| **lh** | `line-height: {1.5};` |
| **ls** | `letter-spacing: {0};` |
| **lt** | `left: {0}; top: {0};` |
| **m** | `margin: {0};` |
| **m0** | `margin: 0;` |
| **m0a** | `margin: 0 auto;` |
| **m0p0** | `margin: 0; padding: 0;` |
| **mah** | `max-height: {none};` |
| **maw** | `max-width: {none};` |
| **mb** | `margin-bottom: {0};` |
| **mh** | `min-height: {100%};` |
| **ml** | `margin-left: {0};` |
| **moa** | `margin: 0 auto;` |
| **mopo** | `margin: 0; padding: 0;` |
| **mr** | `margin-right: {0};` |
| **mt** | `margin-top: {0};` |
| **mw** | `min-width: {100%};` |
| **nr** | `no-repeat` |
| **o** | `overflow: {hidden|auto|scroll};` |
| **oa** | `overflow: auto;` |
| **oh** | `overflow: hidden;` |
| **op** | `opacity: {0};` |
| **os** | `overflow: scroll;` |
| **oxa** | `overflow-x: auto;` |
| **oxh** | `overflow-x: hidden;` |
| **oxs** | `overflow-x: scroll;` |
| **oya** | `overflow-y: auto;` |
| **oyh** | `overflow-y: hidden;` |
| **oys** | `overflow-y: scroll;` |
| **p** | `padding: {0};` |
| **p0** | `padding: 0;` |
| **pb** | `padding-bottom: {0};` |
| **pl** | `padding-left: {0};` |
| **poa** | `position: absolute;` |
| **pof** | `position: fixed;` |
| **por** | `position: relative;` |
| **pos** | `position: static;` |
| **pr** | `padding-right: {0};` |
| **pt** | `padding-top: {0};` |
| **r** | `right: {0};` |
| **ra** | `rgba({0, 0, 0}, {0.5})` |
| **rb** | `rgba(black, {0.2})` |
| **rb** | `right: {0}; bottom: {0};` |
| **rt** | `right: {0}; top: {0};` |
| **rw** | `rgba(white, {0.2})` |
| **rx** | `repeat-x` |
| **ry** | `repeat-y` |
| **ta** | `text-align: {left|right|center|justify};` |
| **tac** | `text-align: center;` |
| **taj** | `text-align: justify;` |
| **tal** | `text-align: left;` |
| **tar** | `text-align: right;` |
| **td** | `text-decoration: {none|underline|strikethrough};` |
| **tdlt** | `text-decoration: line-through;` |
| **tdn** | `text-decoration: none;` |
| **tdu** | `text-decoration: underline;` |
| **tf** | `transform: {scale(1.0)};` |
| **ti** | `text-indent: {0};` |
| **tl** | `table-layout: {fixed|auto};` |
| **tla** | `table-layout: auto;` |
| **tlf** | `table-layout: fixed;` |
| **ts** | `text-shadow: {0 1px 0 #333};` |
| **tst** | `transition: {all 300ms ease};` |
| **tt** | `text-transform: {capitalize|uppercase|lowercase};` |
| **ttc** | `text-transform: capitalize;` |
| **ttl** | `text-transform: lowercase;` |
| **ttu** | `text-transform: uppercase;` |
| **us** | `user-select: {none|text|toggle|element|elements|all};` |
| **usa** | `user-select: all;` |
| **usn** | `user-select: none;` |
| **ust** | `user-select: text;` |
| **v** | `visibility: {visible|hidden|collapse};` |
| **va** | `vertical-align: {top|bottom|baseline|middle};` |
| **vab** | `vertical-align: bottom;` |
| **vabl** | `vertical-align: baseline;` |
| **vam** | `vertical-align: middle;` |
| **vat** | `vertical-align: top;` |
| **vh** | `visibility: hidden;` |
| **vv** | `visibility: visible;` |
| **w** | `width: {0};` |
| **wh** | `width: {0}; height: {0};` |
| **zi** | `z-index: {1};` |
<!-- reference end -->

Contributing
------------

Just edit the YML file, don't edit the snippet files themselves.

Acknowledgements
----------------

© 2012, Rico Sta. Cruz. Released under the [MIT License](http://www.opensource.org/licenses/mit-license.php).

 * [My website](http://ricostacruz.com) (ricostacruz.com)
 * [Github](http://github.com/rstacruz) (@rstacruz)
 * [Twitter](http://twitter.com/rstacruz) (@rstacruz)
